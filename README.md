# ScholarRAG

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![LangChain](https://img.shields.io/badge/LangChain-Framework-green)
![FAISS](https://img.shields.io/badge/FAISS-Vector_Store-orange)
![Wikipedia](https://img.shields.io/badge/Wikipedia-Integration-lightgrey)
![RAG](https://img.shields.io/badge/RAG-Enabled-purple)

**ScholarRAG** is a hybrid Retrieval-Augmented Generation (RAG) chatbot designed to answer research-based queries by:
- Searching a local vector store of academic papers
- Supplementing responses with live Wikipedia content (optional)
- Returning answers with citations when available

---

## 🎯 Features

- Upload and index PDF research papers
- Ask natural language questions to extract knowledge from your dataset
- Wikipedia fallback integration if local documents lack sufficient context
- Uses LangChain, FAISS, and OpenAI or other LLM backends
