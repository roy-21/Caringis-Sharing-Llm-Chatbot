# 🚗 Car-ing is Sharing: LLM Chatbot Prototype

An AI-powered chatbot prototype built using pre-trained Large Language Models (LLMs) from Hugging Face.
This project demonstrates multiple NLP capabilities including sentiment analysis, translation, question answering, and summarization.

---

## 👨‍💻 Author

**Sojib Chandra Roy**
📧 [rcsojib.cse1@gmail.com](mailto:rcsojib.cse1@gmail.com)

---

## 📌 Project Overview

This project was developed as part of an AI/NLP prototype for **Car-ing is Sharing**, a car sales and rental company.

The chatbot is designed to assist customers and support agents by performing various natural language processing tasks using LLMs.

---

## ⚙️ Features

### 1️⃣ Sentiment Analysis

* Classifies car reviews as **Positive** or **Negative**
* Model: `distilbert-base-uncased-finetuned-sst-2-english`
* Metrics:

  * Accuracy
  * F1 Score

---

### 2️⃣ Translation (English → Spanish)

* Translates customer reviews into Spanish
* Model: `Helsinki-NLP/opus-mt-en-es`
* Evaluation Metric:

  * BLEU Score

---

### 3️⃣ Question Answering (QA)

* Extracts answers from reviews based on user questions
* Model: `deepset/minilm-uncased-squad2`

---

### 4️⃣ Text Summarization

* Generates concise summaries (~50 tokens)
* Model: `cnicu/t5-small-booksum`

---

## 📊 Technologies Used

* Python 🐍
* Hugging Face Transformers 🤗
* PyTorch 🔥
* Evaluate Library 📏
* Pandas 📊

---

## 📁 Dataset

* `car_reviews.csv` → Contains customer reviews and sentiment labels
* `reference_translations.txt` → Contains reference Spanish translations for BLEU evaluation

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/car-ing-is-sharing-llm-chatbot.git
cd car-ing-is-sharing-llm-chatbot
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the project

```bash
python src/main.py
```

---

## 📈 Output

The program will:

* Print sentiment predictions with confidence scores
* Display Accuracy & F1 Score
* Show translated text + BLEU score
* Answer a question from a review
* Generate a summary of the last review

---

## 🎯 Future Improvements

* Add Streamlit or Flask UI
* Deploy as a web chatbot
* Add multilingual support
* Improve model performance with fine-tuning

---

## ⭐ If you like this project

Give it a star on GitHub and feel free to fork!

---
