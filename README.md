# Enterprise-Chatbot

An enterprise-ready chatbot application built with Python and Flask that allows users to query internal documents using intelligent retrieval and vector search (FAISS).

This project provides a complete pipeline for document ingestion, preprocessing, indexing, and a simple web-based chat interface.

---

## Overview

Enterprise-Chatbot is designed to help organizations build a private knowledge assistant.  
It ingests documents (such as PDFs), converts them into searchable representations, stores them in a FAISS vector store, and retrieves relevant information in response to user queries.

The architecture is modular and can be easily extended with modern large language models or external APIs.

---

## Features

- Document ingestion and indexing
- Text preprocessing pipeline
- Vector search using FAISS
- Flask-based backend
- Web-based chat interface
- Modular and extensible design
- Suitable foundation for enterprise knowledge assistants

---

## Architecture

1. Documents are loaded and parsed.
2. Text is cleaned and preprocessed.
3. Embeddings are generated and stored in a FAISS index.
4. User queries are embedded and matched against the index.
5. Relevant content is returned to the chat interface.

---

## Requirements

- Python 3.9 or higher
- pip

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Bikramkarki10/Enterprise-Chatbot.git
cd Enterprise-Chatbot
