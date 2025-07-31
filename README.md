# Chalkboard.ai

**Chalkboard.ai** is an AI-powered note-taking tool that transcribes lecture videos and generates customizable study notes using the LLaMA 3 model. Built during the LabLab.ai LLaMA3 Hackathon, it helps students save time by summarizing full-length lecture content into clear, editable study materials. Team was chosen as one of 5 finalists from 500+ teams and 7500+ participants (Top 1% of competitors).

---

## 🎯 Project Purpose

Chalkboard is designed for students who miss lectures or want fast, structured reviews of course material. Users can upload a video (or YouTube link), auto-generate a transcript using AssemblyAI, and then summarize it into notes with adjustable detail using LLaMA 3.

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit, HTML, CSS
- **Backend**: Python
- **LLM**: Meta LLaMA 3 (via GroqCloud)
- **Transcription**: AssemblyAI
- **Database**: MongoDB (via `pymongo`)

---

## 🔧 Features

- 🧠 Transcribe YouTube links or local video files into structured text  
- ✂️ Summarize transcripts into **concise or comprehensive notes** using LLaMA 3  
- ✏️ Edit notes directly in the browser interface  
- 📂 Save notes into named folders with **MongoDB** for reuse  
- 📄 Export notes as `.pdf` or `.docx`  
- 🧪 Future roadmap: Q&A on video content + calendar integration

---

## 🚀 Getting Started

```bash
pip install -r requirements.txt
streamlit run backend/app.py
