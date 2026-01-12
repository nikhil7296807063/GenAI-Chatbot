# GenAI-Chatbot

## 📄🤖 Document-Based GenAI Chatbot (PDF Question Answering)

This repository contains a **Document-Aware Generative AI Chatbot** that allows users to **upload a PDF file and ask questions directly from its content**. The chatbot intelligently understands, processes, and responds to user queries by **learning from the uploaded document**, providing accurate and context-specific answers.

The project is built using **Large Language Models (LLMs)**, **OpenAI API**, and **LangChain**, demonstrating a real-world **Retrieval-Augmented Generation (RAG)** use case for document-based question answering systems.

---

## 🎯 Project Overview

* Upload a **PDF document**
* Extract and process text from the document
* Convert document content into embeddings
* Retrieve the most relevant sections based on user queries
* Generate **context-aware answers strictly based on the uploaded PDF**

This approach ensures responses are **grounded in the document**, reducing hallucinations and improving accuracy.

---

## 🧠 Key Features

* 📄 **PDF Upload & Processing**
* 🔍 **Semantic Search using Embeddings**
* 🧠 **Context-Aware Question Answering**
* 🔗 **LangChain-based Retrieval Pipeline**
* 🤖 **LLM-powered answer generation**
* 🔐 **Secure API key management using environment variables**
* ♻️ **Reusable & extensible architecture**

---

## 🛠️ Tech Stack

* **Language:** Python
* **GenAI:** OpenAI API (LLMs & Embeddings)
* **Framework:** LangChain
* **Document Loader:** PDF Loader (LangChain)
* **Vector Store:** FAISS / Chroma (or pluggable)
* **Environment:** dotenv
* **Version Control:** Git & GitHub

---

## ⚙️ How It Works (Architecture Flow)

1. User uploads a **PDF document**
2. PDF content is **extracted and split into chunks**
3. Chunks are converted into **vector embeddings**
4. Embeddings are stored in a **vector database**
5. User asks a question in the chatbot
6. Relevant document chunks are retrieved using **semantic similarity**
7. LLM generates an answer **based only on retrieved content**

---

## 🚀 Use Cases

* Document Q&A system
* Internal knowledge assistant
* Policy / manual / research paper analysis
* Resume, report, or contract understanding
* Enterprise AI POCs

---

## 🔮 Future Enhancements

* Multi-document support
* Web UI using Streamlit or React
* Support for DOCX, TXT, and URLs
* Chat history persistence
* Role-based access & authentication
* Docker & Kubernetes deployment
* CI/CD pipeline integration

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙌 Author

**Nikhil Khandelwal**
Software Engineer | DevOps | GenAI & LLM Explorer

