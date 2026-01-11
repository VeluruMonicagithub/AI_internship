# 🎙️ Live Meeting Summarizer

An AI-powered system that listens to meetings, understands who said what, and turns long conversations into clean, structured summaries.  
Built during an internship as a collaborative project 💻✨

---

## 🚨 Problem Statement

Online meetings generate long audio recordings, but:
- 📝 Manual note-taking is inefficient  
- 🗣️ Speaker identification is difficult  
- ⏳ Important points get lost  

We needed an **automated, intelligent solution** to capture, analyze, and summarize meetings in real time.

---

## 🎯 Project Objective

This system:
- 🎧 Captures live meeting audio  
- ✍️ Converts speech to text  
- 👥 Identifies different speakers  
- 🧠 Generates AI-based structured summaries  

---

## ⚙️ System Overview

**Processing Pipeline:**

Live Audio → Speech-to-Text → Speaker Diarization → AI Summarization → Display & Export

---

## 🧩 Technologies Used

- **Speech-to-Text:** Vosk / Whisper  
- **Speaker Diarization:** pyannote.audio  
- **Summarization Models:** LLaMA 3.1, T5, BART  
- **Frontend:** Streamlit  
- **Backend:** Python  

📊 Performance:
- STT Word Error Rate (WER) < 15%  
- Diarization error < 20%  
- Summarization ROUGE score > 0.4  

---

## 🖥️ User Interface

- 🎛️ Start / Stop recording controls  
- 📜 Live transcription  
- 🗂️ Speaker-wise transcript  
- 📝 Final AI-generated summary  
- 🚦 Status indicators for each stage  

---

## 📤 Export & Sharing

- 📄 One-click download (PDF, Markdown)  
- 📧 Email summary feature  
- 🕒 Meeting logs stored with timestamps  

---

## 👥 Team & Contribution

This project was developed as a **collaborative internship project**.

**Contributors:**
- Monica  
- Julfa  
- Sharmila  
- Suraj  
- Arya  

---



