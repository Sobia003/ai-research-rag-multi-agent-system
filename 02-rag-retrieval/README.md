# AI Research – RAG Retrieval

This workflow enables users to interact with previously uploaded research documents through an AI-powered Retrieval-Augmented Generation (RAG) system.

### Workflow Features
- Accepts questions through an n8n chat interface.
- Extracts document titles and user questions using JavaScript.
- Retrieves relevant document chunks from Supabase Vector Store.
- Uses Google Gemini embeddings for semantic retrieval.
- Processes retrieved document context using a Gemini language model.
- Generates context-grounded answers without inventing information.

### Technologies Used
- n8n
- Google Gemini
- Supabase Vector Store
- Retrieval-Augmented Generation (RAG)
- JavaScript
- LangChain

### Workflow File
See `rag-retrieval-public.json` for the exported n8n workflow.

### Setup
1. Import the JSON workflow into n8n.
2. Configure your own Supabase and Google Gemini credentials.
3. Ensure research documents have already been ingested into the Supabase `documents` table.
4. Test the chat interface with questions about your uploaded documents.

### How It Works
User Question → Code Processing → Vector Search → Retrieved Context → Gemini Response

### Project Note
This workflow is the retrieval component of the AI Research, RAG & Multi-Agent System.
