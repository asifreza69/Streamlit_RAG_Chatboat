# 🧠 Interactive Streamlit RAG Chatbot

An interactive Retrieval-Augmented Generation (RAG) chatbot built with Streamlit that allows users to upload PDF documents and ask intelligent questions using semantic search and LLM-powered reasoning.

The application uses HuggingFace embeddings, Chroma vector database, and LLaMA models via Groq to provide fast and accurate document-based answers.

---

## 🚀 Features
- Upload and chat with multiple PDF documents
- Semantic search using vector embeddings
- Context-aware answers using RAG architecture
- Powered by LLaMA models via Groq
- Clean and interactive Streamlit UI
- Conversation history support

---

## 🏗️ RAG Architecture

PDFs → Text Chunking → Embeddings → Chroma Vector DB
                                   ↓
User Question → Similarity Search → LLaMA (Groq) → Answer

---

## 🛠️ Tech Stack
- Frontend: Streamlit
- LLM: LLaMA (via Groq API)
- Embeddings: HuggingFace Sentence Transformers
- Vector Store: Chroma DB
- Framework: LangChain
- Language: Python

---

## 📂 Project Structure

streamlit-rag-chatbot/
├── app.py              # Streamlit UI
├── rag.py              # RAG pipeline logic
├── requirements.txt    # Project dependencies
├── README.md           # Project documentation
├── .gitignore

---

## ⚙️ Installation

1. Clone the repository
   git clone https://github.com/your-username/streamlit-rag-chatbot.git
   cd streamlit-rag-chatbot

2. Create virtual environment (recommended)
   python -m venv myenv
   myenv\Scripts\activate   # Windows

3. Install dependencies
   pip install -r requirements.txt

---

## 🔑 Environment Variables

Create a .env file in the project root:

GROQ_API_KEY=your_groq_api_key_here

---

## ▶️ Run the Application

streamlit run app.py

Open browser at: http://localhost:8501

---

## 📌 Use Cases
- Document-based Question Answering
- Research paper analysis
- Resume and report summarization
- Internal knowledge base chatbot
- Learning and experimenting with RAG systems

---

## 📈 Future Enhancements
- Multi-turn conversational memory
- Support for more document formats
- Streaming responses
- Cloud deployment

---

## 👨‍💻 Author

Md Asif  
NIT Bhopal  

---

⭐ If you like this project, don’t forget to star the repository!
