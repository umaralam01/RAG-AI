# 🚀 RAG AI

**Multimodal Retrieval-Augmented Generation (RAG) System for PDFs, Audio, and Images**

---

## 🌟 Overview

NovaRAG AI is a **Flask-based multimodal RAG system** that allows you to:

- Upload **PDFs, audio files, and images**  
- Ask **natural language questions** about the uploaded content  

It integrates multiple AI models to process **text, voice, and images** and combines them into a single intelligent retrieval system.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📄 **PDF Upload** | Extracts text page-wise and stores embeddings for semantic search |
| 🎧 **Audio Upload** | Transcribes and translates Hindi/English audio using Whisper |
| 🖼️ **Image Upload** | Extracts text using OCR (Tesseract) and generates embeddings |
| 💬 **Ask Questions** | Query across all uploaded content using LLaMA 3.2 |
| 🔍 **Vector Search** | Uses ChromaDB for embedding-based retrieval |
| ⚙️ **Local AI** | Fully offline, runs with LLaMA 3.2 (Ollama) |
| 🤖 **Context-aware Answers** | Provides intelligent answers with references to page/segment |

---

## 🧠 Tech Stack

| Category | Technology |
|----------|------------|
| Backend Framework | Flask |
| Embeddings | Sentence Transformers (`all-MiniLM-L6-v2`, `clip-ViT-B-32`) |
| Audio Transcription | OpenAI Whisper |
| OCR Engine | Tesseract OCR + Pillow |
| Vector Database | ChromaDB |
| LLM Backend | Ollama (LLaMA 3.2) |
| Frontend | HTML, CSS, JS (Flask Templates) |

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/umaralam01/NovaRAG-AI.git
