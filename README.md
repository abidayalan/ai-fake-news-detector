# 🤖 AI Fake News Detector

An AI-powered web application that detects whether a news article is **Real or Fake** using **Machine Learning and Natural Language Processing (NLP)**.

This project analyzes news text entered by the user and predicts its authenticity using a trained machine learning model.

---

## 📌 Project Overview

Fake news has become a major issue in the digital era. This project aims to provide a simple tool that can help identify potentially misleading or fake news articles using artificial intelligence.

The system uses a **TF-IDF vectorizer** and a **Logistic Regression model** to classify news content as **REAL** or **FAKE**.

Users can simply paste a news headline or article into the web interface and the system will analyze it instantly.

---

## ✨ Features

- 📰 Detects whether a news article is **Fake or Real**
- 🤖 AI-based text classification using Machine Learning
- 📊 Displays **prediction confidence score**
- 🌙 Modern **dark-themed professional UI**
- ⚡ Fast prediction through a Flask web application
- 💻 Easy to run locally

---

## 🧠 Machine Learning Workflow

1. Load and preprocess the news dataset
2. Convert text into numerical features using **TF-IDF Vectorization**
3. Train a **Logistic Regression classifier**
4. Save the trained model using **Pickle**
5. Use Flask to create a web interface for predictions

---

## 🛠️ Tech Stack

**Programming Language**
- Python

**Machine Learning**
- Scikit-learn
- Pandas
- NumPy
- TF-IDF Vectorizer
- Logistic Regression

**Web Development**
- Flask
- HTML
- CSS

---

## 📂 Project Structure

AI-powered Fake News Detector using Machine Learning and Flask
fake-news-detector
│
├── app.py # Flask web application
├── model.py # Model training script
├── news.csv # Dataset
├── model.pkl # Trained ML model
├── vectorizer.pkl # TF-IDF vectorizer
│
├── templates
│ └── index.html # Frontend UI
│
└── README.md


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/ai-fake-news-detector.git

2️⃣ Navigate to the Project Folder
cd ai-fake-news-detector

3️⃣ Install Required Libraries
pip install pandas scikit-learn flask nltk

4️⃣ Train the Model
python model.py

5️⃣ Run the Web Application
python app.py

6️⃣ Open in Browser
http://127.0.0.1:5000/

🖥️ How It Works
User enters a news article or headline.
The system converts the text into numerical features using TF-IDF.
The trained machine learning model analyzes the input.
The system predicts whether the news is REAL or FAKE.
The prediction and confidence score are displayed on the webpage.

🚀 Future Improvements
Add deep learning models for better accuracy
Highlight suspicious words in the article
Add support for URL-based news verification
Deploy the application online
Improve dataset size for better performance

👨‍💻 Author
Abi
AI / Machine Learning Project
Built for learning and academic purposes.


