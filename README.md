RAG Chatbot



A full-stack retrieval-augmented generation (RAG) chatbot that lets you upload documents and ask natural language questions about them.



How it works

1. Upload a PDF or TXT file through the web UI

2. Documents are chunked, embedded, and stored in ChromaDB

3. Questions are embedded and matched against stored chunks via semantic search

Visual Demo

1. ![Flask development server running on port 8000](docs/screenshots/flask-startup.png)

2. ![Chatbot answering questions about an uploaded PDF](docs/screenshots/chatbot-demo.png)
