# MULTIMODAL-AI-STUDY-ASSISTANT
A full-stack, multimodal AI educational platform powered by Google Gemini 2.5 Flash, Streamlit, and PyNgrok. Features real-time streaming chat, multi-paper PYQ analytics, automated handwritten notes grading, document/media parsing, dynamic study roadmaps, and multilingual audio synthesis.
# Multimodal AI Study Assistant 🎓🤖

An all-in-one, cloud-hosted AI educational suite designed to streamline academic workflows, automate active learning, and consolidate document and media processing into a single interactive workspace. Built with **Streamlit**, **Google Gemini 2.5 Flash**, and **PyNgrok**.

---

## 🌟 Key Features

* **⚡ Real-Time Streaming Doubt Engine:** Multi-turn conversational study assistant powered by `gemini-2.5-flash` with sub-second token delivery.
* **📄 Multi-Format Ingestion:** Direct parsing for PDFs, Word (`.docx`), PowerPoint (`.pptx`), handwritten scans, audio (`.mp3`), and video (`.mp4`).
* **📊 Multi-Paper PYQ Trend Analyzer:** Ingests up to 4 past-year exam papers simultaneously to identify topic weightings and high-frequency questions.
* **📝 Handwritten Notes Evaluator & Mock Test FSM:** Interactive Finite State Machine that converts student notes into tailored practice exams and generates objective, professor-level grading reports.
* **📅 Dynamic Exam Roadmap Engine:** Automatically calculates exam date deltas to output personalized, day-by-day study schedules.
* **🔊 Multilingual Audio Teacher:** Synthesizes summaries and lecture scripts into natural spoken MP3 audio in English, Hindi, Kannada, and French using `gTTS`.
* **🛡️ Fault-Tolerant Infrastructure:** Built-in `safe_stream_generator` with exponential backoff retries to prevent crash events during high API load.

---

## 🛠️ Tech Stack

* **Core AI Model:** Google Gemini 2.5 Flash (`google-genai` SDK)
* **Frontend Framework:** Streamlit
* **Deployment & Ingress:** PyNgrok
* **Document & Vision Parsing:** PyPDF, Python-Docx, Python-PPTX, Pillow (PIL)
* **Audio Synthesis:** Google Text-to-Speech (gTTS)
* **Language/Environment:** Python 3.10+

---

## 🚀 Getting Started

### Prerequisites

* Python 3.10 or higher
* Google Gemini API Key
* Ngrok Auth Token

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Multimodal-AI-Study-Assistant.git](https://github.com/YOUR_USERNAME/Multimodal-AI-Study-Assistant.git)
   cd Multimodal-AI-Study-Assistant
