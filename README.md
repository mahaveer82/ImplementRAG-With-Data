# 🍷 Wine Recommendation using RAG (Retrieval-Augmented Generation)

This project demonstrates the **RAG (Retrieval-Augmented Generation)** concept using a dataset of wine reviews. It combines **Sentence Transformers**, **Qdrant Vector DB**, and **LLMs** to recommend wines through intelligent search based on natural language prompts.

---

## 📚 Project Overview

- **Data Loading**: A CSV file with wine reviews is processed and cleaned.
- **Embedding & Storage**: Sentence Transformers generate vector embeddings; vectors are stored in **Qdrant**.
- **RAG Pipeline**: A prompt is passed to an LLM, which retrieves relevant vectors and uses that context to generate accurate wine recommendations.

This project helped me understand and implement **semantic search**, **vector databases**, and **retrieval-augmented generation** end-to-end.

---

## 🧱 Tech Stack

| Component        | Tool/Library                     |
|------------------|----------------------------------|
| Embedding Model  | Sentence Transformers (`all-MiniLM`) |
| Vector DB        | Qdrant (local or cloud)          |
| RAG Backend      | LangChain or Custom Logic        |
| Dataset          | Wine Reviews CSV (`wine_data.csv`) |
| Language         | Python                           |
| LLM              | OpenAI / Local LLM (optional)    |

---
