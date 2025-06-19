# 🎓 UVic Assistant – RAG Chatbot Project

This is a university assistant chatbot built using Retrieval-Augmented Generation (RAG) techniques to help students at the **University of Victoria (UVic)** find answers from the university website, documents, and sitemap.

The assistant uses **Ollama** for language modeling, **LanceDB** for vector storage, and has a **Python backend** with a **Vue.js frontend**.

---

## 📌 Features

- 🔍 Answers questions using university web data (RAG-based)
- 🧠 Uses embeddings + vector search (LanceDB)
- 💬 Natural language interface powered by Ollama
- 🖥️ Web-based UI with Vue.js frontend
- 📄 Sitemap ingestion for contextual answers

---

## 🛠️ Tech Stack

| Layer      | Tools Used                         |
|------------|------------------------------------|
| LLM        | Ollama (e.g., Mistral, LLaMA3)     |
| Embedding  | Ollama Embedding Models            |
| Vector DB  | LanceDB                            |
| Backend    | Python (FastAPI / Flask / etc.)    |
| Frontend   | Vue.js                             |
| Data       | UVic Sitemap / Web Pages           |

---

## 🚀 Getting Started

### 🧰 Prerequisites

- Python 3.10+
- Node.js & npm (for Vue frontend)
- Git
- Ollama installed and running locally (https://ollama.com/)
- Chrome/Firefox for scraping, or existing sitemap files

### 📦 Installation

1. Clone the repository:
   git clone https://github.com/ArchanaRadhakrishnanS/RAGProjects.git
   cd RAGProjects
