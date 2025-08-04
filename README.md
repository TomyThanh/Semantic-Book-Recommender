# 📚✨ Semantic Book Recommender

![Repo Size](https://img.shields.io/badge/Status-Ready-blueviolet?style=for-the-badge&logo=bookstack)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-555555?style=for-the-badge&logo=gradio&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-HuggingFace-FFCC00?style=for-the-badge&logo=huggingface&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> **“Find the book you didn’t know you needed.”**  
> An AI-powered, semantic book recommender with its own search bar, running as an interactive HTML/Gradio web app.

---

## 🚀 What It Does

The **Semantic Book Recommender** takes your query (topic, feeling, vague description – you name it) and finds **semantically matching books**, not just keyword hits.  
It combines:
- 📖 Semantic search over book descriptions & metadata  
- 🧠 Transformer-based embeddings (HuggingFace, etc.)  
- 🔍 A custom, smart search bar  
- 🌐 Interactive control via **Gradio** (HTML frontend)  

---

## ✨ Features

- 🎯 **Semantic recommendations** – understand meaning, not just words  
- 🧠 **Transformer embeddings** for deep context matching  
- 🔎 **Custom live search bar** (autocomplete-style, if implemented)  
- 🌈 **Interactive web interface** with Gradio – no CLI fuss  
- 📚 Works with any kind of text input: mood, genre, theme, quotes, etc.  
- 💡 Shows *why* a book was recommended (semantic match reasoning)  
- 🚀 Real-time ranking & similar suggestions  
- 🛠️ Easily extendable: add more books, change models, fine-tune  

---

## 🧰 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFCC00?style=for-the-badge&logo=huggingface&logoColor=black)  
![Gradio](https://img.shields.io/badge/Gradio-555555?style=for-the-badge&logo=gradio&logoColor=white)  
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)  
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)  

---

## 🛠️ Installation & Quickstart

```bash
# Clone repository
git clone https://github.com/YourUser/Semantic-Book-Recommender.git
cd Semantic-Book-Recommender

# (Optional) Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
# .\venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
