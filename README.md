# 📚 Study Material Generator

> **AI-Powered Lecture Notes → Summary, Flashcards & MCQs**

## 📖 Overview

Study Material Generator is an AI-powered application that converts lecture notes (PDF or Text) into structured study materials such as summaries, flashcards, and multiple-choice questions (MCQs). The project uses **Ollama**, **LangChain**, and **Streamlit** to provide an efficient, offline, and user-friendly learning experience without requiring any paid APIs.

---

## 🎯 Objectives

- Generate concise summaries from lecture notes.
- Create flashcards for quick revision.
- Generate MCQs for self-assessment.
- Export study materials into Word documents.
- Provide a simple and interactive web interface.
- Work completely offline using a Local LLM.

---

## ✨ Features

- 📄 PDF & Text Upload
- 🤖 AI-Powered Summary Generation
- 🧠 Flashcard Generation
- ❓ MCQ Generation
- 📥 Word (.docx) Export
- 🔒 Offline Processing using Ollama
- 💻 Streamlit Web Interface
- 📚 Modular Project Architecture

---

## 🛠 Tech Stack

### Programming Language
- Python 3.10+

### AI & NLP
- Ollama
- LangChain
- ChromaDB
- Llama 3.1
- Mistral 7B

### Frontend
- Streamlit

### PDF Processing
- pdfplumber
- PyPDF2

### Export
- python-docx

### Tools
- Git
- GitHub
- VS Code

---

## 📂 Project Structure

```text
study-material-generator/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── config/
├── docs/
├── scripts/
├── src/
└── tests/
```

---

## ⚙️ Workflow

1. Upload PDF or Text Notes
2. Extract Text
3. Clean & Process Text
4. Generate Embeddings (Optional)
5. Process using Local LLM (Ollama)
6. Generate:
   - Summary
   - Flashcards
   - MCQs
7. Export as Word Document

---

## 👥 Team Members & Roles

| Team Member | Role |
|--------------|------|
| **Alok Tripathi** | Team Lead & Prompt/LLM Engineer |
| **Gaurav Singh** | RAG & Backend Pipeline Engineer |
| **Akshat Kumar Shukla** | Ingestion Engineer |
| **Alok Pal** | Frontend / Streamlit Developer |
| **thealok144** | Export & QA Engineer |
| **Adarsh Pal** | Documentation, DevOps & Demo Lead |

---

## 🧪 Testing

Run all tests

```bash
pytest
```

---

## 🔮 Future Enhancements

- OCR Support
- Multi-language Support
- Cloud Deployment
- User Authentication
- Mobile App
- AI Chat Assistant
- Dark Mode

---

## 🤝 Contributing

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

---

## 📜 License

This project is developed for educational purposes as a B.Tech CSE Mini Project.

---

## ⭐ Support

If you like this project, please **Star ⭐ the repository** and contribute to its development.

---

## 🙏 Acknowledgements

- Ollama
- LangChain
- Streamlit
- ChromaDB
- GitHub
- Python Community

---

### ❤️ Made with Python, Streamlit, LangChain & Ollama
