# RAG-retrieval-augmented-generation

Overview

A local question-answering system built with LangChain and TinyLlama. It loads documents (text files and PDFs), splits them into chunks, converts them into embeddings using HuggingFace models, and stores them in a FAISS vector store. When you ask a question, it retrieves the most relevant chunks and passes them to TinyLlama to generate an answer , all running locally on CPU, no API keys needed.

How It Works
Load and split documents (PDFs/text)
Convert text into embeddings
Store embeddings in ChromaDB
Retrieve relevant chunks for a query
Generate answers using a language model

Tech Stack
Python
LangChain
ChromaDB
How to Run
Install dependencies
pip install -r requirements.txt
Add documents to the data/ folder
Run main.ipynb and start querying
Use Cases
Document Q&A
Study assistant
Custom knowledge chatbot
