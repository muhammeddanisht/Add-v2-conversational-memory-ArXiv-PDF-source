# RAG Chatbot — LangChain + FAISS + Groq

A Retrieval-Augmented Generation (RAG) chatbot built with LangChain, FAISS vector database, 
and Llama 3.1 via Groq API. Progressively built from basic RAG to conversational memory.

### v2 — Conversational Memory (`rag_v2_arxiv_memory.ipynb`)
- Added `create_history_aware_retriever` for context-aware retrieval
- `chat_history` stores full Q&A scroll, sent with every invoke
- Source: "Attention Is All You Need" (ArXiv 1706.03762)
- Follow-up questions answered using conversation context

## Tech Stack
- LangChain + LangChain-Classic
- FAISS (vector database)
- all-MiniLM-L6-v2 (HuggingFace embeddings)
- Llama 3.1 8B via Groq API (free)
- Google Colab (T4 GPU)

## Run
Open either notebook in Google Colab. Add `GROQ_API_KEY` to Colab Secrets. Run all cells.
