# 📄 DocRAG

DocRAG is a **Retrieval-Augmented Generation (RAG)** system that allows you to query your own documents using Large Language Models (LLMs).  
It combines **document ingestion, embeddings, semantic retrieval, and generative AI** to give accurate, context-aware answers.

---

## 🚀 Features

- 📚 Upload and index your own documents (PDF, TXT, etc.)
- 🔍 Semantic search powered by embeddings
- 💬 Natural language Q&A over your documents
- 🖥️ Interactive **Streamlit web app**
- ⚡ **Command-line interface (CLI)** for quick queries

---

## 📂 Project Structure

DocRAG/
│── data/ # Store your documents here
│── src/ # Core logic (ingestion, embeddings, retrieval, generation)
│── main.py # CLI entry point
│── streamlit_app.py # Streamlit web application
│── requirements.txt # Dependencies

yaml
Copy code

---

## 🛠️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/BENJOSE474/DocRAG.git
cd DocRAG
pip install -r requirements.txt
⚡ Usage
▶️ Run from CLI
Index your documents and ask questions directly:

bash
Copy code
python main.py --docs ./data --query "What is this document about?"
🖥️ Run Streamlit App
Launch the interactive web app:

bash
Copy code
streamlit run streamlit_app.py
Upload documents via the UI and start asking questions.

🔑 Configuration
Place your documents inside the data/ folder.

Update .env or configuration files inside src/ with your API keys (e.g., OpenAI, Hugging Face, etc.).

Modify embedding/retrieval settings in src/ if needed.

🖼️ Example Workflow
Add your PDFs or text files to the data/ folder.

Run:

bash
Copy code
python main.py --query "Summarize chapter 1"
Or launch the Streamlit app and upload documents interactively.

Get precise, context-driven answers from your documents 🎯

🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to open a PR or raise an issue.

📜 License
This project is licensed under the MIT License.
