# Equity Research Tool Using RAG

A RAG-powered equity research assistant that lets users input 
2-3 financial article links and ask questions about their content. 
Retrieves precise insights from the articles using semantic search 
and generates accurate answers via LLM.

## What It Does

- Ingests 2-3 financial article URLs as knowledge source
- Chunks and embeds article content for semantic retrieval
- Answers user questions grounded strictly in the articles
- Eliminates manual reading — get insights instantly

## Tech Stack

- **LangChain** — RAG pipeline and document processing
- **Google PaLM LLM** — response generation
- **FAISS** — vector similarity search
- **Python** — core logic

## Architecture
```
Article URLs → LangChain Document Loader → Text Chunking
→ FAISS Embeddings → User Query → Similarity Search
→ Retrieved Context → PaLM LLM → Accurate Answer
```

## Use Case

Equity analysts and investors input recent earnings reports,
news articles, or research papers and ask targeted questions:

- "What was the revenue growth mentioned in this article?"
- "What risks did the CEO highlight?"
- "Compare the margins across these two reports"

## Setup
```bash
git clone https://github.com/Fahd-8/Equity-Research-Tool-Using-RAG
cd Equity-Research-Tool-Using-RAG
pip install -r requirements.txt
jupyter notebook Equity_Research_Tool\(RAG_Langchain\).ipynb
```

---
Built by [Fahad Zaman](https://github.com/Fahd-8) — AI Engineer
