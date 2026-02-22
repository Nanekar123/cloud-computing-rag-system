📘 Cloud Computing RAG System
Retrieval-Augmented Generation using Ollama + FAISS
👩‍💻 Author

Supriya Nanekar
AI/ML Assignment – Retrieval-Augmented Generation (RAG)

📌 Project Overview

This project implements a Retrieval-Augmented Generation (RAG) system to answer questions based on a Cloud Computing PDF (110 pages).

The system retrieves relevant information from the document using semantic search and generates accurate answers using a local Large Language Model (LLM) powered by Ollama (Llama3).

This project demonstrates practical understanding of:

Retrieval-Augmented Generation (RAG)

Vector Databases (FAISS)

Embeddings

Prompt Engineering

Local LLM Deployment

Model Evaluation

🎯 Objective

To build a question-answering system that:

Uses Cloud Computing notes as a knowledge base

Retrieves relevant content using vector similarity

Generates context-aware answers

Minimizes hallucination

Works completely offline

📂 Dataset

File Name: CloudComputingNotes.pdf

Pages: 110

Type: Text-based academic notes

Domain: Cloud Computing

Topics Covered:

Cloud Computing Basics

Service Models (IaaS, PaaS, SaaS)

Deployment Models

Virtualization

Elasticity

Load Balancing

Security Challenges

Multi-tenancy

🏗️ System Architecture

PDF
↓
Text Extraction
↓
Text Chunking
↓
Embedding Generation
↓
FAISS Vector Store
↓
Retriever (Top-K Similarity Search)
↓
Ollama (Llama3 LLM)
↓
Generated Answer

🛠️ Technologies Used

Python

LangChain

Ollama (Local LLM)

FAISS (Vector Database)

Sentence Transformers

PyPDF

⚙️ Installation & Setup
1️⃣ Install Required Libraries
pip install langchain
pip install langchain-community
pip install sentence-transformers
pip install faiss-cpu
pip install pypdf
2️⃣ Install Ollama

Download Ollama from:

https://ollama.com

Pull the model:

ollama pull llama3

Run the model:

ollama run llama3

Keep Ollama running in the background.

🚀 How to Run the Project

Clone this repository

Place CloudComputingNotes.pdf inside the project folder

Open the Jupyter Notebook

Run all cells sequentially

The system will:

Extract text from the PDF

Create text chunks

Generate embeddings

Build FAISS vector store

Retrieve relevant content

Generate answers using Ollama

📊 Evaluation

The system was tested using 12 Cloud Computing questions.

Evaluation Criteria

Relevance (5)

Completeness (5)

Hallucination Check (5)

⭐ Average Score: 13.4 / 15
🔍 Improvements Implemented

Increased chunk size (800)

Added chunk overlap (150)

Increased retriever k value

Improved prompt structure

Structured answer formatting

📈 Baseline vs Improved System
Metric	Baseline	Improved
Retrieval Accuracy	Medium	High
Completeness	Medium	High
Hallucination	Low	Very Low
Average Score	12.1	13.4
✅ Key Features

✔ Fully Offline (No OpenAI API required)
✔ Semantic Search using FAISS
✔ Context-based Answer Generation
✔ Reduced Hallucination
✔ Academic Evaluation Included

📎 Repository Structure
cloud-rag-project/
│
├── CloudComputingNotes.pdf
├── rag_notebook.ipynb
├── README.md
└── requirements.txt
🏁 Conclusion

The implemented RAG system successfully retrieves and generates accurate answers from Cloud Computing notes. The improved version demonstrates better retrieval quality, improved completeness, and minimal hallucination.

This project showcases practical implementation of modern AI retrieval systems using open-source tools and local LLMs.