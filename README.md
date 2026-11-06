# AI Research, RAG & Multi-Agent System

An integrated AI-powered research system built with **n8n, Google Gemini, and Supabase**. This project consists of three connected workflows designed to process research documents, retrieve relevant information, and support intelligent multi-agent tasks.

## Project Overview

The system is divided into three major workflows:

### 1. AI Research Document Ingestion
- Accepts research PDF documents.
- Extracts text and processes document content.
- Splits content into smaller chunks.
- Generates vector embeddings using Gemini.
- Stores document chunks and embeddings in Supabase Vector Store.

### 2. RAG-Based Document Retrieval
- Retrieves relevant information from stored research documents.
- Uses semantic search to find matching document content.
- Provides context-grounded responses based on retrieved information.
- Helps users search and understand research material more efficiently.

### 3. Multi-Agent System
- Implements an AI multi-agent workflow.
- Organizes tasks across specialized AI agents.
- Uses AI-powered reasoning and workflow orchestration.
- Demonstrates an agent-based approach to handling complex tasks.

## Technologies Used

- n8n – Workflow automation and orchestration
- Google Gemini – AI models and embeddings
- Supabase – Database and vector storage
- Retrieval-Augmented Generation (RAG)
- JavaScript – Workflow logic and data processing
- APIs and HTTP Requests

## Project Structure

- `01-document-ingestion/` – PDF processing and embedding workflow.
- `02-rag-retrieval/` – Document retrieval workflow.
- `03-multi-agent-system/` – Multi-agent workflow.

## Key Learning Outcomes

- Building AI-powered automation workflows.
- Processing and managing research documents.
- Working with vector databases and embeddings.
- Implementing semantic retrieval.
- Exploring multi-agent orchestration.
- Integrating AI models with external services.

## Note

This project was developed as part of a practical AI workflow development sprint. The workflows demonstrate document processing, retrieval-based AI, and multi-agent automation using n8n.

**Author:** Sobia Khan
