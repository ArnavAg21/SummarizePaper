# 🧠 SummarizePaper

A full-stack web application that automatically summarizes research papers using **Hugging Face Transformer models**.  
Built with **Python**, **Django**, **HTML**, **CSS**, **JavaScript**, and **MySQL (or SQLite)** for the backend.

---

## 🚀 Overview

This app allows users to summarize scientific papers from sources like arXiv.  
It provides a simple, intuitive web interface to paste or upload content and instantly get concise summaries powered by NLP models.

The project demonstrates integration between web frameworks and AI APIs — ideal for showcasing practical machine learning and web development skills.

---

## ⚙️ Features

- ✨ AI-based text summarization (using Hugging Face models)  
- 🌐 Responsive UI built with HTML, CSS, and JavaScript  
- 🧩 Django backend with database integration  
- 🗃️ Stores summaries and original text  
- 💬 Easy to deploy locally or on the web  
- 🧠 Extendable for sentiment analysis, translation, or classification  

---

## 🧰 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | HTML, CSS, JavaScript |
| **Backend** | Python, Django |
| **Database** | MySQL / SQLite |
| **AI Models** | Hugging Face Transformers |
| **License** | MIT License |

---

## 🧩 Installation Guide

1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/AI-Research-Paper-Summarizer.git
cd AI-Research-Paper-Summarizer

2️⃣ Set Up Virtual Environment (Optional but Recommended)
python -m venv venv
# Activate:
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run Migrations and Start Server
python manage.py migrate
python manage.py runserver


Now open your browser and go to
👉 http://127.0.0.1:8000/

📦 Example Usage

Paste the abstract or text of a research paper.

Click “Summarize”.

Instantly receive a concise AI-generated summary.

Optionally, save or copy the result.

🏷️ Attribution

This repository is based on the open-source SummarizePaper
 project,
licensed under the MIT License.

Original authors: SummarizePaper Contributors
Customized and maintained for educational purposes by Arnav Agarwal.

🪄 Future Enhancements

🧾 PDF upload & automatic extraction

🌍 Multilingual summarization

🔐 User authentication for saving summaries

📊 Dashboard for recent summaries and analytics

☁️ Deployable to Render / Heroku / Railway

📜 License

This project is licensed under the MIT License — you are free to use, modify, and share it
as long as attribution is preserved.

🌟 Acknowledgements

Special thanks to the open-source community and Hugging Face for providing the NLP models that power this project.
