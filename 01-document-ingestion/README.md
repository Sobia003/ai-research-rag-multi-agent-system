# AI Research Document Ingestion

This workflow automates the ingestion of research PDF documents using n8n.

### Workflow Features
- PDF document upload through an n8n form.
- Automatic text extraction.
- Document splitting into smaller chunks.
- Google Gemini embedding generation.
- Storage of document chunks and embeddings in Supabase Vector Store.

### Technologies
- n8n
- Google Gemini Embeddings
- Supabase Vector Store
- PDF Processing
- RAG Pipeline

### Workflow File
See `document-ingestion-public.json` for the exported n8n workflow.

### Setup
Import the JSON file into n8n, configure your own Google Gemini and Supabase credentials, and configure the form trigger before running.
