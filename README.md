# Streamlit RAG Chatbot

A Retrieval-Augmented Generation (RAG) chatbot built with Streamlit that allows users to upload PDF documents and ask questions using semantic search and LLaMA models via Groq.

## Features
- PDF document upload
- Semantic search using HuggingFace embeddings
- Chroma vector database
- LLaMA model inference via Groq
- Streamlit UI

## Tech Stack
- Python
- Streamlit
- LangChain
- HuggingFace Embeddings
- Chroma DB
- Groq (LLaMA)

## Setup
```bash
pip install -r requirements.txt
streamlit run app.py
