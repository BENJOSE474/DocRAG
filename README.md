# 📄 DocRAG

DocRAG is a **Retrieval-Augmented Generation (RAG)** system that lets you query documents intelligently using LLMs.  
It combines **document ingestion, embedding-based retrieval, and large language model generation** to provide accurate, context-aware answers.

---

## 🚀 Features

- 📚 Upload and index your own documents (PDF, text, etc.)
- 🔍 Semantic search powered by vector embeddings
- 💬 Natural language Q&A over your knowledge base
- 🖥️ Streamlit web app interface
- ⚡ Command-line interface for quick queries

---

## 📂 Project Structure
DocRAG/
│── data/ # Store your documents here
│── src/ # Core logic (ingestion, embeddings, retrieval, generation)
│── main.py # CLI entry point
│── streamlit_app.py # Streamlit web application
│── requirements.txt # Dependencies

---

## 🛠️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/BENJOSE474/DocRAG.git
cd DocRAG
pip install -r requirements.txt
⚡ Usage
1. Run from CLI

Index your documents and ask questions directly:

python main.py --docs ./data --query "What is this document about?"

2. Run Streamlit App

Launch the interactive web app:

streamlit run streamlit_app.py


Upload documents via the UI and start asking questions.


