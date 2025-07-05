# Retrieval-Augmented Generation (RAG) — From Scratch

This project implements a simple and professional **Retrieval-Augmented Generation (RAG)** pipeline using Python and HuggingFace Transformers. It combines semantic search with generative reasoning, enabling accurate question-answering over a custom document corpus.

---

## Features

- Document chunking using tokenizer length
- Embedding generation with HuggingFace models
- Query-to-document similarity via cosine similarity
- Top-K retrieval of relevant information
- Ready for integration with LLMs like Gemini or OpenAI

---

## Project Structure

- `main_notebook.ipynb`: Core logic for chunking, embedding, retrieval, and similarity
- `requirements.txt`: List of required Python packages
- `.env`: For storing API keys (e.g., `GEMINI_API_KEY`)

---

## Getting Started
1. **Clone the repository**
   ```bash
  
   git clone https://github.com/Shalha-Mucha18/Build-RAG.git

2. **Install dependencies**
    ```bash
    pip install -r requirements.txt
3. **Add your Gemini or OpenAI key to .env**
   ```bash
   GEMINI_API_KEY=your-api-key-here
4. **Launch the notebook**
   
   Open main_notebook.ipynb in Jupyter or VS Code and run all cells.    
    

