RAG Chatbot

A full-stack retrieval-augmented generation (RAG) chatbot that lets you upload documents and ask natural language questions about them.

How it works:

1. Upload a PDF or TXT file through the web UI

2. Documents are chunked, embedded, and stored in ChromaDB

3. Questions are embedded and matched against stored chunks via semantic search

Visual Demonstration:

<img width="855" height="187" alt="Startup" src="https://github.com/user-attachments/assets/2000ab48-a1cb-42da-9336-df510454813c" />

<img width="1470" height="956" alt="UI:Results" src="https://github.com/user-attachments/assets/41fdb4aa-e3f3-4dac-bf3c-70a8d89c5759" />

How to run the program:

1. Open the terminal on your computer.
2. Activate Python virtual environment (source venv/bin/activate)
3. Start the Flask server (PORT=8000 python app.py)
4. Wait until Terminal shows `Running on http://127.0.0.1:8000`
5. Head to any browser and open the chatbot at (http://localhost:8000) then upload a document and ask any question.
