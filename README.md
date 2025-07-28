# 📊 Sentiment Analysis Web App

This is a simple web application built using **Flask** that performs **sentiment analysis** on user-provided text using **TextBlob**. It classifies the input as **Positive**, **Negative**, or **Neutral**, and displays **polarity** and **subjectivity** scores.

---

## 🚀 Features

- Analyze the **sentiment** of any text.
- View:
  - 🟢 Sentiment Label (Positive / Negative / Neutral)
  - 📈 Polarity Score (range: -1 to +1)
  - 🧠 Subjectivity Score (range: 0 to 1)
- Stylish, modern **Glassmorphism UI** with animated buttons and custom badges.

---

## 🛠️ Installation & Running

1. **Clone or download** this repository.

2. **Install dependencies**:
   ```bash
   pip install flask textblob
   python -m textblob.download_corpora
