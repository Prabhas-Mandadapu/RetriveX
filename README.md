# RetriveX
multimodel Retrieval-Augmented Generation (RAG) system leveraging a Large Language Model (LLM) for OFFLINE mode that can ingest, index, and query diverse data formats such as DOC, PDF, Images and voice recordings within a unified semantic retrieval framework


# 🧠 Multi-Modal Offline Retrieval-Augmented Generation (RAG) System

An **offline, privacy-preserving AI-powered knowledge retrieval system** that enables **natural language querying across multiple data formats** such as PDFs, Word documents, images, and audio files using a **Retrieval-Augmented Generation (RAG)** architecture with **local Large Language Models (LLMs)**.

---

## 📌 Project Overview

**Main Project Review – 1**  
**Department:** CSE – AIML (CSM)  
**Institution:** Vasireddy Venkatadri Institute of Technology (VVIT)

### 🎯 Problem Statement
Design and build a **multi-modal Retrieval-Augmented Generation (RAG) system** that works entirely in **offline mode**, capable of ingesting, indexing, and querying diverse data formats (DOC, PDF, Images, Voice) within a unified semantic retrieval framework.

---

## 🚀 Key Features

- 📁 Multi-modal file upload (PDF, DOCX, Images, Audio)
- 🔍 Semantic similarity search using FAISS
- 🧩 Text chunking & embedding generation
- 🤖 Offline LLM integration (Mistral, LLaMA, Qwen)
- 🧠 Retrieval-Augmented answer generation
- 📚 Source attribution for answers
- 🕒 Query history logging
- ❤️ System health monitoring
- 🔐 Fully offline & privacy-preserving

---

## 🏗️ System Architecture

User Query
↓
Frontend (React UI)
↓
FastAPI Backend
↓
Retriever (FAISS Vector Database)
↓
Relevant Context Chunks
↓
Local LLM (Mistral / LLaMA / Qwen)
↓
Final Answer + Source References


---

## 🧩 Project Modules

### 1️⃣ RAG Pipeline & AI Model Integration
**Tools:** Sentence-Transformers, FAISS, Local LLMs, Python  

- Generate semantic embeddings
- Index vectors using FAISS
- Retrieve relevant chunks
- Provide context to local LLMs
- Tune model parameters for accuracy

---

### 2️⃣ API Development & System Integration
**Tools:** FastAPI, Python, REST APIs  

- File upload & processing APIs
- Query handling endpoints
- Query history retrieval
- System health monitoring
- Offline environment configuration

---

### 3️⃣ Frontend Development & Documentation
**Tools:** ReactJS, Tailwind CSS  

- Web-based user interface
- File upload & query interaction
- Clean and user-friendly design
- System documentation & reports

---

### 4️⃣ Backend & Agent Development
**Tools:** Python, FastAPI, Tesseract OCR, Whisper, PDF & DOCX libraries  

- Agent-based backend architecture
- Modality-specific agents:
  - 📄 PDF / DOCX processing
  - 🖼️ Image OCR
  - 🎙️ Audio transcription
- Automatic file-type detection
- Data cleaning & preprocessing

---

## 🧠 Technologies Used

| Category | Tools |
|--------|------|
| Language | Python |
| Backend | FastAPI |
| Frontend | ReactJS, Tailwind CSS |
| Vector Database | FAISS |
| Embeddings | Sentence-Transformers |
| OCR | Tesseract |
| Speech-to-Text | Whisper |
| LLMs | Mistral, LLaMA, Qwen |
| Deployment | Offline / Local |

---

## 🧪 Functional Requirements

- File upload and management  
- Multi-modal data processing  
- Text chunking  
- Embedding generation  
- Vector storage and indexing  
- Natural language query handling  
- Context retrieval  
- Answer generation using RAG  
- Source attribution  
- Query history logging  
- System health monitoring  

---

## 👥 Team Members

| Name | Role |
|----|----|
| **Paruchuri Usha Kiran** | RAG Pipeline & AI Integration |
| **Jakka Charishma** | API Development & System Integration |
| **Kakumanu Ravi Chandra** | Frontend Development & Documentation |
| **Mandadapu Prabhas** | Backend & Agent Development |

**Batch:** 6  
**Project Guide:** *Dr. V. Muralidhar*

---

## 🛡️ Why Offline RAG?

- Complete data privacy  
- No cloud dependency  
- Suitable for healthcare, legal, enterprise, and academic use cases  
- Explainable & trustworthy AI responses  

---

## 🔮 Future Enhancements

- Support for additional data formats
- Multilingual query support
- Improved ranking strategies
- Advanced UI analytics dashboard
- Role-based access control

---

## 📜 License

This project is developed for **academic purposes** under  
**Dr.V.Muralidhar ,VVIT – Department of CSE (AIML)**.
