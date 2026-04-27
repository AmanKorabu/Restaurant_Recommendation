# 🍽️ DineMatch  AI

### *Where Taste Meets Intelligence — Personalized Restaurant Discovery in Bangalore*

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-2.0%2B-000000?style=flat-square&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0%2B-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.0-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

---

## 📖 Overview

**DineMatch  AI** isn't just another restaurant finder — it's your personal dining companion that understands your taste. 

Unlike traditional platforms that serve generic "top-rated" lists, our engine dives deep into what people *actually say* about restaurants. By analyzing thousands of customer reviews using Natural Language Processing, DineMatch  AI discovers hidden gems that match your unique preferences, not just popular opinion.

### 🎯 Why DineMatch  AI?

| Traditional Recommenders | DineMatch  AI |
|--------------------------|----------------|
| "Here are the top 10 restaurants in Bangalore" | "Here are 10 restaurants similar to your favorite spot" |
| Based only on ratings & price | Based on *what people actually say* in reviews |
| Ignores cuisine context & dining experience | Understands semantic meaning through NLP |
| Static lists, no personalization | Dynamic, taste-matched recommendations |

---

## ✨ Features That Make Us Different

### 🔥 Core Intelligence
- **NLP-Powered Review Analysis** — Uses TF-IDF vectorization to extract meaningful patterns from unstructured customer feedback
- **Multi-Factor Matching** — Combines cuisine type, cost brackets, ratings, and review sentiment
- **Real-Time Inference** — Pre-computed similarity matrix (`.pkl`) ensures sub-100ms response times

### 🎨 User Experience
- **Smart Auto-Complete** — AJAX-powered search with keyboard navigation (↑/↓/Enter)
- **Glassmorphism UI** — Modern, light-themed interface with smooth hover states
- **Responsive Dashboards** — Clean, formatted results that work on desktop & mobile

### 🏗️ Technical Excellence
- **Modular Architecture** — Separation of training pipeline (Jupyter) and inference server (Flask)
- **Production-Ready** — Pre-trained model loading, no redundant computations
- **Data Integrity** — Automatic cleaning & preprocessing pipeline

---

## 📁 Project Structure
**DineMatch  AI** 
```
restaurant_recommendation/
├── Dataset/
│   └── zomato.csv                          # Zomato Bangalore dataset (download from Kaggle)
├── Flask/
│   ├── app1.py                             # Main Flask application
│   ├── train_model.py                      # Model training script
│   ├── restaurant.pkl                      # Trained model (generated)
│   ├── restaurant1.csv                     # Processed data (generated)
│   ├── templates/
│   │   ├── index.html                      # Home page
│   │   ├── web.html                        # Recommendation input page
│   │   └── result.html                     # Results page
│   └── static/
│       ├── css/
│       │   └── main.css                    # All styles
│       ├── js/
│       │   └── main.js                     # Frontend JS
│       └── images/                         # Static images
├── Model/
│   └── Restaurant_Recommendation_System.ipynb   # Jupyter notebook with full analysis
├── requirements.txt
└── README.md
```

---

## 🚀 Quick Start Guide

### Step 1: Clone & Environment

```bash
git clone https://github.com/yourusername/SmartDining-AI.git
cd SmartDining-AI/Flask
pip install -r ../requirements.txt
```
### Step 2: Train the Model
```bash
jupyter notebook Restaurant_Recommendation_System.ipynb
```
### Step 3: Run the App
```bash
python app1.py
```
### Step 4: Open Browser
```bash
Go to http://localhost:5000
```

### 📊 Dataset
Feature	Description
Source	Zomato Bangalore restaurants
Size	3,000+ restaurants
Review Count	10,000+ customer reviews

🛠️ Tech Stack
Backend: Flask, Python

ML: scikit-learn (TF-IDF, Cosine Similarity)

Frontend: HTML,CSS,Tailwind CSS, JavaScript

NLP: NLTK
📝 License
MIT License

### 👨‍💻 Developer - Aman Korabu

<div align="center">
⭐ Star this repo if you find it useful! ⭐

Built during SmartInternz AI Internship

</div> ```
