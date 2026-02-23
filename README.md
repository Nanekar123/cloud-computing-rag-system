# ☁️ Cloud Computing RAG System using Ollama + LangChain

## 👩‍🎓 Student Details

**Name:** Supriya Nanekar
**Subject:** Cloud Computing
**Project Type:** AI-based Study Assistant

---

## 📌 Project Overview

This project is an **AI-powered Cloud Computing Assistant** that answers user questions based on a given PDF (study material).

The system uses **RAG (Retrieval Augmented Generation)** to retrieve relevant content from documents and generate accurate answers using a **local LLM (Ollama - phi3 model)**.

---

## 🎯 Objective

The main objective of this project is to:

* Convert cloud computing notes into a searchable knowledge base
* Retrieve relevant information based on user queries
* Generate accurate and meaningful answers using AI

---

## 🛠️ Technologies Used

* Python
* LangChain
* ChromaDB (Vector Database)
* HuggingFace Embeddings
* Ollama (phi3 model - local LLM)
* PyPDF Loader
* NLTK

---

## 🔁 System Workflow

1. Load PDF using PyPDFLoader
2. Split document into smaller chunks
3. Convert text into vector embeddings
4. Store embeddings in ChromaDB
5. Retrieve similar chunks using similarity search
6. Send retrieved context to Ollama LLM
7. Generate final answer

---

## 🧠 What is RAG?

**RAG (Retrieval Augmented Generation)** is a technique that combines:

* **Retrieval** → searching relevant information from documents
* **Generation** → generating answers using a language model

This improves accuracy and ensures answers are based on real data.

---

## 📂 Project Structure

```
cloud-computing-rag-system/
│
├── data/
│   └── cloud1.pdf
│
├── notebooks/
│   └── Cloud_RAG_Assistant.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```
git clone https://github.com/Nanekar123/cloud-computing-rag-system.git
cd cloud-computing-rag-system
```

### 2️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 3️⃣ Run Ollama Model

```
ollama run phi3
```

### 4️⃣ Launch Notebook

```
jupyter notebook
```

Open:

```
notebooks/Cloud_RAG_Assistant.ipynb
```

---

## 🧪 Sample Questions Tested

* What is cloud computing?
* Explain IaaS, PaaS, SaaS
* What is virtualization?
* Explain public cloud and private cloud
* What is scalability in cloud computing?
* Explain elasticity in cloud computing

---

## 📈 Output

The system generates answers based only on the provided PDF data, ensuring **accuracy and relevance**.

---

## ✅ Advantages

* Works completely offline using Ollama
* No API cost required
* Accurate answers from study material
* Useful for exam preparation

---

## ⚠️ Limitations

* Answers only from uploaded PDF
* Requires local setup
* Depends on quality of input data

---

## 🚀 Future Improvements

* Add web interface using Streamlit
* Support multiple PDFs
* Add voice input
* Deploy on cloud

---

## 🙏 Conclusion

This project demonstrates how **Cloud Computing concepts** can be integrated with **AI and RAG architecture** to build an intelligent study assistant.

---

## 📚 Acknowledgement

This project is developed as part of **Cloud Computing Academic Assignment**.
