# 🚀 HireSense AI 
### AI-Powered Interview Preparation with Real-Time Multimodal Feedback

**[Live Demo](https://hireesense.lovable.app/)** HireSense AI is a high-performance web application designed to bridge the gap between technical knowledge and communication mastery. It leverages a multimodal AI pipeline to analyze not just **what** you say, but **how** you say it.

---

## 🎯 The Problem
Traditional interview prep tools are static. They focus on Q&A content while ignoring critical delivery signals. **HireSense AI** solves this by providing dual-track analysis:
* 👉 **Content:** Logic, relevance, and structure.
* 👉 **Delivery:** Speech patterns, behavioral signals, and engagement.

## ⚙️ Core Features

### 🎤 Multimodal Input
* **Text:** Direct input for logic evaluation.
* **Audio:** High-fidelity recording with Whisper-powered transcription.
* **Video:** Browser-based capture for behavioral tracking.

### ⚡ Real-Time Feedback (Live Processing)
The system uses lightweight browser-based heuristics to provide immediate visual cues:
* **Audio:** Volume levels and speaking pace estimation.
* **Speech:** Pause and filler-word detection.
* **Video:** Face detection, movement tracking, and engagement indicators.

### 🧠 AI Evaluation (Post-Response)
Detailed analysis driven by Large Language Models (LLMs):
* **Scoring:** 1–10 quantitative performance metric.
* **Content:** Identification of strengths and structural weaknesses.
* **Delivery:** Feedback on confidence, clarity, and non-verbal cues.
* **Optimization:** AI-generated "Improved Response" for iterative learning.

---

## 🧱 System Architecture
* **No code low code platform:** Lovable AI
* **Frontend:** React, Tailwind CSS.
* **Client-Side Intelligence:** Web Audio API, MediaPipe, face-api.js.
* **Backend/Services:** Node.js / FastAPI.
* **AI Pipeline:** OpenAI GPT (Evaluation/Logic), OpenAI Whisper (STT).

## 🔄 Workflow
1.  **Selection:** User chooses a target job role.
2.  **Interaction:** AI generates a role-specific question; user responds via text/audio/video.
3.  **Live Analysis:** Indicators provide real-time performance cues.
4.  **Processing:** Audio is transcribed; video signals are aggregated.
5.  **Synthesis:** GPT evaluates the combined data points.
6.  **Reporting:** User receives a structured, actionable feedback dashboard.

---

## 🔐 Security & Data
* **Zero-Persistence:** Audio and video are processed temporarily; no sensitive data is stored permanently.
* **Secure Config:** API keys managed via environment variables.

## ⚠️ Known Limitations
* **MVP Scope:** Focused on core behavioral signals, not deep emotion detection.
* **Input Sensitivity:** AI feedback quality is dependent on microphone/camera clarity.
* **Non-Production:** Built as a functional prototype to demonstrate multimodal integration.

---

## 👤 Author
**Sumaya Fathima**
*AI Application Builder | BIT Student at Liwa University*

---
⭐ *If you found this project useful, consider starring the repository!*
