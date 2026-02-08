# Local RAG Pipeline with LangChain, Ollama & Chroma

This project demonstrates a **local Retrieval-Augmented Generation (RAG) pipeline** built step-by-step using:

- Python
- LangChain
- Ollama (local embeddings)
- Chroma (vector database)

The notebook walks through the complete lifecycle of building a RAG foundation — from loading raw text to semantic retrieval — without relying on cloud APIs.

---

## Overview

Retrieval-Augmented Generation (RAG) improves LLM responses by retrieving relevant context from external data before generating answers.

This implementation covers:

1. Loading raw text documents  
2. Splitting text into semantic chunks  
3. Generating embeddings locally  
4. Storing vectors in a persistent database  
5. Querying using semantic similarity search

## Requirements

### Python Packages

Install dependencies:

pip install \
  langchain \
  langchain-community \
  langchain-text-splitters \
  langchain-chroma \
  chromadb \
  ollama


## Learning Outcomes

This project demonstrates understanding of:-

RAG system fundamentals
Embedding workflows
Vector databases
Local LLM infrastructure
LangChain pipeline composition