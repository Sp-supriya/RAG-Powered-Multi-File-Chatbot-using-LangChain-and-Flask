# RAG-Powered Multi-File Chatbot 🧠💬

This is a Retrieval-Augmented Generation (RAG) based chatbot built with Flask, LangChain, FAISS, and HuggingFace models. Users can upload multiple document types (PDF, Word, PPT, etc.) and ask natural language questions. The system retrieves the most relevant chunks and answers using a local extractive QA model.

## 🚀 Features
- Supports file uploads: `.pdf`, `.txt`, `.csv`, `.docx`, `.pptx`
- Uses FAISS for vector store and similarity search
- CrossEncoder for reranking retrieved chunks
- Extractive QA powered by HuggingFace (`roberta-base-squad2`)
- Clean Flask-based frontend

## 🛠️ Technologies Used
- Flask
- LangChain
- FAISS
- HuggingFace Transformers
- SentenceTransformers
- HTML/CSS

## 🏁 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/rag-chatbot
   cd rag-chatbot
