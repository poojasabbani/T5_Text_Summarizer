# T5 Text Summarizer

> An AI-powered text summarization web application built using a fine-tuned T5-small Transformer model, FastAPI, and Hugging Face Transformers.

---

## Project Overview

AI Text Summarizer is a Natural Language Processing (NLP) application that generates concise and meaningful summaries from long pieces of text using a fine-tuned **T5-small Transformer model**.

The application provides a simple web interface where users can input large text passages and receive high-quality abstractive summaries in real time.

---

## Features

- Generate abstractive summaries from long text
- Fine-tuned T5-small Transformer model
- FastAPI backend
- Simple HTML user interface
- Local inference (No external API required)
- Fast response time
- Easy to extend and deploy

---

## Tech Stack

### Backend
- FastAPI
- Python

### Machine Learning
- Hugging Face Transformers
- PyTorch
- T5-small

### Frontend
- HTML
- Jinja2 Templates

---

## Project Structure

```
AI-Text-Summarizer/
│
├── app.py
├── README.md
├── requirements.txt
├── .gitignore
│
├── templates/
│   └── index.html
│
└── saved_summary_model/
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/ai-text-summarizer.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Application

Start the FastAPI server

```bash
uvicorn app:app --reload
```

Open your browser

```
http://127.0.0.1:8000
```

---

## Model Information

This project uses a **fine-tuned T5-small Transformer model** for abstractive text summarization.

> **Note:** The trained model is **not included** in this repository because the model file exceeds GitHub's 100 MB file size limit.

To run the project locally, place the trained model inside:

```
saved_summary_model/
```

---

## Future Improvements

- PDF summarization
- DOCX summarization
- Multiple summary lengths
- Batch summarization
- Hugging Face Hub integration
- Docker deployment
- Cloud deployment

---

## Learning Outcomes

This project helped me gain practical experience with:

- Transformer-based NLP
- Fine-tuning Hugging Face models
- FastAPI development
- Model deployment
- Text preprocessing
- Building AI-powered web applications

---

## Author

**Pooja Sabbani**

B.Tech Robotics Engineering

Machine Learning & AI Enthusiast

GitHub: https://github.com/yourusername