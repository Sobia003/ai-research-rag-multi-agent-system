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

## Project Workflows

### 1. AI Research – Document Ingestion
Upload research PDFs, extract their text, split content into chunks, generate embeddings using Google Gemini, and store them in Supabase Vector Store.

📁 [View Document Ingestion](./01-document-ingestion/)

### 2. AI Research – RAG Retrieval
Retrieve relevant information from stored research documents using semantic search and generate context-grounded answers with Google Gemini.

📁 [View RAG Retrieval](./02-rag-retrieval/)

### 3. Multi-Agent System
Explore a multi-agent AI architecture built with n8n, demonstrating collaboration between AI agents in an automated workflow.

📁 [View Multi-Agent System](./03-multi-agent-system/)

### 4. Autonomous HubSpot Lead Follow-up Agent

An AI-powered lead decision workflow built with n8n, HubSpot, and Google Gemini. It evaluates contact information, scores and prioritizes leads, recommends follow-up actions, and generates personalized email drafts.

📁 [View Autonomous HubSpot Lead Follow-up Agent](https://github.com/Sobia003/04-autonomous-lead-follow-up-agent)

### 5. Travel Agency AI Booking Agent

An end-to-end AI-powered travel booking system built with n8n, Google Gemini, Stripe, and Gmail. Features conversational tour booking, availability checks, automated payment links, and payment confirmation emails through Stripe webhooks.

📁 [View Travel Agency AI Booking Agent](https://github.com/Sobia003/travel-agency-ai-booking-agent)

### 6. Doctor Appointment Automation

An automated appointment booking and payment workflow built with n8n, Google Sheets, Stripe, Gmail, and Google Calendar. It validates appointment requests, checks slot availability, creates payment links, and confirms bookings after successful payment.

📁 [View Doctor Appointment Automation](https://github.com/Sobia003/doctor-appointment-automation)

### 7. Lead Management System

An automated lead management workflow built with n8n and HubSpot CRM. It captures and validates leads, creates CRM contacts and deals, assigns sales representatives, and sends automated email notifications.

📁 [View Lead Management System](https://github.com/Sobia003/lead-management-system)

### 8. Reminder AI Chat Assistant

An AI-powered reminder assistant built with n8n and Google Calendar. It creates, lists, and updates calendar events through natural-language chat, with Asia/Karachi timezone handling.

📁 [View Reminder AI Chat Assistant](https://github.com/Sobia003/reminder-ai-chat-assistant)
