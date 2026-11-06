# AI Research – Multi-Agent System

This workflow uses five specialized AI agents to transform retrieved PDF evidence into a structured research report.

## How It Works

1. **Research Coordinator:** Understands the research question and creates a research plan.
2. **Research Agent:** Reviews evidence retrieved from the selected PDF.
3. **Analysis Agent:** Identifies key findings, patterns, and relationships.
4. **Fact-Checking Agent:** Verifies claims against the supplied evidence and identifies unsupported statements.
5. **Report Generation Agent:** Produces a structured research report based on the previous agents' outputs.

## Technologies Used
- n8n
- Google Gemini
- Supabase Vector Store
- AI Agents
- Retrieval-Augmented Generation (RAG)
- JavaScript

## Key Features
- Five specialized agents with separate responsibilities
- Evidence-based research and analysis
- Fact-checking and identification of evidence gaps
- Structured research report generation
- Retrieval from the selected PDF using Supabase metadata

## Setup
1. Import the workflow JSON into n8n.
2. Configure your own Google Gemini and Supabase credentials.
3. Ensure the selected PDF has already been processed and stored in the Supabase `documents` table with its `document_title` metadata.
4. Test the workflow using a document filename and research question.

## Workflow
User Request → Document Selection → Research Planning → Evidence Retrieval → Research → Analysis → Fact-Checking → Report Generation
