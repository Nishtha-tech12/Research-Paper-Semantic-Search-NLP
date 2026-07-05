# AI Research Paper Assistant (RAG + NLP + Gemini)

> An end-to-end AI system that retrieves research papers using semantic search, extracts keywords and entities, summarizes content, and generates final intelligent explanations using Google Gemini.
---
## Project Overview

This project is a **Retrieval-Augmented Generation (RAG) based NLP system** that helps users understand research topics by combining multiple AI techniques.

It takes a user query and:
- Retrieves relevant research papers
- Extracts key information (keywords + entities)
- Summarizes each paper
- Generates a final intelligent explanation using Gemini

This demonstrates a real-world **hybrid NLP + LLM architecture**.
---

## System Architecture

User Query <br>
↓ <br>
Sentence Transformer (Embeddings) <br>
↓ <br>
FAISS Vector Search <br>
↓ <br>
Top 5 Research Papers <br>
↓ <br>
Keyword Extraction <br>
↓ <br>
BART Summarization (per paper) <br>
↓ <br>
Google Gemini API (Final reasoning & synthesis) <br>
↓ <br>
Entity + Keyword Aggregation <br>
↓ <br>
Final Structured Output

## Key Features

- Semantic search using Sentence Transformers  
- Fast similarity search with FAISS  
- Abstractive summarization using BART  
- Keyword extraction from research papers  
- Google Gemini-powered reasoning  
- Entity extraction (authors, datasets, models)  
- Structured and explainable final output  

---

## 🛠️ Tech Stack

- Python
- Sentence Transformers  
- FAISS (Facebook AI Similarity Search)  
- HuggingFace Transformers (BART)  
- Google Generative AI (Gemini API)  
- NLP techniques (keyword + entity extraction)

---
