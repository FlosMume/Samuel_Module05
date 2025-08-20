# 🌐 LLM Boot Camp – Week 5: Embedding Database Optimization

This project implements a **hybrid retrieval system** that combines **semantic (vector) search** using **FAISS** with **keyword-based search** using **SQLite FTS5**, enabling more accurate and robust document retrieval. By fusing both methods, the system leverages the strengths of dense vector similarity and exact keyword matching to improve relevance over either method alone.

The index stores document chunks along with metadata (title, author, year, etc.) and supports fast querying via a **FastAPI endpoint**. Retrieval performance is evaluated using **Recall@3** across 10+ test