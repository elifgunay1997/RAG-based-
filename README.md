# 🧠 RAG-Based Document Question Answering System

This project builds a **Retrieval-Augmented Generation (RAG)** pipeline that allows users to upload documents (PDFs) and ask questions in natural language. It retrieves relevant content from the document and uses a Large Language Model (LLM) to generate answers.

---

## 🎯 Project Goal

To enable users to chat with documents and get intelligent, context-aware responses by combining vector similarity search with generative AI.

---

## 🔧 Tech Stack

- 🧾 **LangChain** – LLM orchestration
- 🔍 **FAISS** – Vector similarity search
- 📄 **PyMuPDF** – Extract text from PDFs
- 🧠 **OpenAI / Local LLMs** – Text generation
- 🔡 **HuggingFace Embeddings** – For vector representations
- 🌐 **Streamlit** – Simple interactive web UI (optional)

---

## ⚙️ How It Works

1. **Upload PDF**
2. Extract text and split into chunks
3. Convert chunks into vector embeddings
4. Store in a FAISS vector database
5. Accept user question
6. Retrieve relevant document chunks
7. Use LLM to generate a contextual answer

---

## 🚀 Installation

```bash
git clone https://github.com/elifgunay1997/rag-question-answering.git
cd rag-question-answering
pip install -r requirements.txt
