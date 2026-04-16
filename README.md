📚 RAG-Based Competitive Exam Preparation System
🚀 Overview

This project is a Retrieval-Augmented Generation (RAG) system designed to help students prepare for competitive exams by enabling intelligent question answering from study materials such as PDFs.

Instead of relying only on general AI knowledge, this system retrieves relevant content from your own documents and uses it to generate accurate, context-based answers.

🎯 Features
📄 Upload and process PDF study materials
✂️ Automatic text chunking for efficient retrieval
🔎 Semantic search using vector embeddings
🤖 AI-powered question answering using retrieved context
⚡ Event-driven architecture using Inngest
🧠 Context-aware responses (RAG pipeline)
📚 Ideal for competitive exams like:
GATE
UPSC
GRE
Technical interviews

🏗️ Architecture

The system follows a RAG pipeline:
'''PDF → Chunking → Embeddings → Vector DB → Query → Context Retrieval → LLM Answer'''
Components:
FastAPI → Backend server
Inngest → Event-driven workflows
OpenAI API → Embeddings + LLM responses
Qdrant → Vector database
Custom Pipeline:
        data_loader.py → PDF processing & embedding
        vector_db.py → Storage & retrieval
        main.py → Workflow orchestration


⚙️ Installation
1️⃣ Clone the repository
'''git clone <your-repo-url>
cd <project-folder>'''
