# 🎓 EduX – AI-Powered Cognitive Learning Chatbot

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-2.3.3-green?logo=flask)](https://flask.palletsprojects.com/)
[![Ollama](https://img.shields.io/badge/Ollama-LLM-orange)](https://ollama.ai)

EduX is an intelligent, **AI-driven tutoring platform** designed to boost academic performance through personalized instruction powered by **LLMs**, **cognitive learning science**, and **real-time feedback loops**.

GitHub Repo: [github.com/Kunalchandra007](https://github.com/Kunalchandra007](https://github.com/Kunalchandra007/Edux))

---

## 🚀 Key Features

- 🧠 Adaptive chatbot using Mistral, Dolphin, Wizard-Math models  
- 🔄 Dynamic teaching stages: intro, assessment, follow-up, summary  
- 📈 Dashboard with analytics: track accuracy, time, improvement  
- 📺 Slide extractor from YouTube lectures using OCR + CV  
- 📝 Quiz generator and answer evaluator  
- ✍️ Summarization tool for fast review  

---

## 📦 Benefits of Using Ollama

Ollama provides **lightweight, local LLMs** tailored for offline, secure AI apps:

- ✅ **Runs models locally** (no cloud dependencies, no latency)  
- ✅ **Lightweight deployments** – no GPU needed for basic tasks  
- ✅ **Easy model switching** – supports Mistral, LLaMA, WizardCoder, etc.  
- ✅ **Faster iteration** for testing prompt engineering  
- ✅ **Privacy-first** AI development (great for education)

---

## 🏗️ Project Structure

educational-chatbot/
├── app.py
├── requirements.txt
├── static/
├── templates/
├── modules/
├── database/
├── logs/
└── README.md


---

## ⚙️ How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/Kunalchandra007/edux.git
cd edux
```
2. Install Dependencies
```bash
pip install -r requirements.txt
```
🧪 Also install Tesseract OCR:
Download: https://github.com/UB-Mannheim/tesseract/wiki
Ensure it's added to your system PATH.

3. Install Ollama & Models
```bash
# Install Ollama: https://ollama.ai/download
ollama pull mistral-openorca:latest
ollama pull wizard-math:7b
ollama pull dolphin-mistral:latest
ollama pull mistral:7b-instruct
ollama run mistral
```
4. Run the Flask App
```bash
flask run
```
📊 Dashboard & Analytics
Track response accuracy and time

Review last 10 questions

Performance-based difficulty adjustment

🎯 Use Cases
🧑‍🎓 Students practicing subjects

👩‍🏫 Teachers creating quick assessments

📖 Learners reviewing long videos

🧠 Daily quizzes for memory training

📁 Logs & Debugging
All events are logged in logs/app.log. Useful for:

Login issues

Model errors

Slide extraction failures

🙌 Author
Made with ❤️ by Kunal Chandra
Driven by a passion for AI and education.

