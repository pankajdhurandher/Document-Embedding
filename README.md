# 📄 Document Embedding

A Python-based document embedding pipeline that loads documents, splits them into smaller chunks, generates embeddings, and stores them in a vector database for semantic search and RAG applications.

## 🚀 Features

* Load PDF, TXT, and DOCX documents
* Text extraction and chunking
* Generate document embeddings
* Store embeddings using ChromaDB
* Perform semantic similarity search
* Jupyter notebooks for experimentation
* Secure API key management using `.env`

## 🛠️ Tech Stack

* Python
* LangChain
* ChromaDB
* Groq
* Ollama
* Jupyter Notebook
* UV

## 🔄 Workflow

```text
Document
   ↓
Document Loader
   ↓
Text Chunking
   ↓
Embedding Model
   ↓
ChromaDB
   ↓
Semantic Search
   ↓
Relevant Chunks
   ↓
RAG Application
```

## 📁 Project Structure

```text
Document-Embedding/
├── data/
│   ├── pdf/
│   ├── text_files/
│   └── word_files/
├── notebook/
│   ├── document.ipynb
│   └── pdf_loader.ipynb
├── src/
├── .gitignore
├── pyproject.toml
├── requirements.txt
├── uv.lock
└── README.md
```

## ⚙️ Setup

Clone the repository:

```bash
git clone https://github.com/pankajdhurandher/Document-Embedding.git
cd Document-Embedding
```

Create and activate a virtual environment:

```bash
python -m venv .venv
```

Windows:

```powershell
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Or using UV:

```bash
uv sync
```

Create a `.env` file and add your API key:

```env
GROQ_API_KEY=your_api_key
```

Run the notebooks:

```text
notebook/document.ipynb
notebook/pdf_loader.ipynb
```

## 🔮 Future Improvements

* Complete RAG question-answering pipeline
* FastAPI backend
* Document upload API
* Web interface
* Docker support
* Retrieval evaluation

## 👨‍💻 Author

**Pankaj Dhurandher**

GitHub: https://github.com/pankajdhurandher
