# 🔍 RAG Pipeline with LangChain, Gemini API, Wikipedia & Arxiv

This is an end-to-end **Retrieval-Augmented Generation (RAG)** project built using **LangChain**, **FAISS**, and **Google Generative AI (Gemini Pro)** that allows answering questions by retrieving relevant information from a custom PDF, Wikipedia, and Arxiv.

---

## 🧠 Project Overview

The goal of this project is to create an intelligent chatbot using a RAG pipeline that:

- Loads and processes documents from different sources
- Creates vector embeddings for efficient retrieval
- Uses Google Gemini API to generate context-aware responses
- Combines PDF, Wikipedia, and Arxiv content for multi-source reasoning
- Deploys with Streamlit/FastAPI for easy interaction

---

## 🔧 Tech Stack

- `LangChain`
- `FAISS` (Vector Store)
- `Google Generative AI (Gemini Pro)`
- `pypdf` (PDF parsing)
- `BeautifulSoup` (Web scrapers)
- `Wikipedia`, `Arxiv` loaders
- `Python-dotenv`
- `Streamlit`, `LangServe`, `FastAPI`
- `Uvicorn`, `sse_starlette`

---

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/rag-pipeline-genai.git
cd rag-pipeline-genai
