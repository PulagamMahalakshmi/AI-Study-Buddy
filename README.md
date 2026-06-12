# 📚 AI Study Buddy - AI Powered Learning Assistant

AI Study Buddy is an AI-powered educational assistant that helps students learn faster by providing topic explanations, summarizing notes, generating quizzes, creating flashcards, and answering doubts using Large Language Models (LLMs).

The application is built using **Python, Streamlit, NLP techniques, PDF processing, and Groq LLM API**.

---

## 🚀 Features

### 🤖 AI Tutor
- Ask questions and get simple explanations
- Provides:
  - Direct Answer
  - Step-by-step Explanation
  - Examples
  - Quick Revision Points

### 📖 Topic Explainer
- Explains any technical or academic topic
- Supports different learning levels:
  - Beginner
  - Intermediate
  - Advanced

### 📝 Notes Summarizer
- Converts lengthy notes into:
  - Short Summary
  - Important Points
  - Exam Revision Tips

### 📄 PDF Study Material Analyzer
- Upload PDF notes
- Extracts text automatically
- Uses extracted content for learning tools

### ❓ Quiz Generator
- Creates MCQ-based quizzes from notes
- Provides:
  - Questions
  - Options
  - Correct Answers
  - Explanations

### 🗂️ Flashcard Generator
- Creates quick revision flashcards
- Helps students prepare efficiently

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Frontend
- Streamlit

### AI / LLM
- Groq API
- Llama 3.3 Model

### Libraries
- PyPDF2
- python-dotenv
- Groq SDK

### Concepts Used
- Natural Language Processing
- Prompt Engineering
- API Integration
- PDF Text Extraction

---

## 📂 Project Structure
AI-Study-Buddy
│
├── app.py
├── gemini_helper.py
├── requirements.txt
├── README.md
├── .env
│
└── modules
├── chatbot.py
├── flashcard_generator.py
├── pdf_reader.py
├── quiz_generator.py
├── summarizer.py
└── topic_explainer.py