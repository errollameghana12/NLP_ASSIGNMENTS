# 🧠 NLP Preprocessing Engine – Internship Assignment (Feb 2026)

## 📌 Overview

This project is part of the **Data Science Internship – February 2026** assignment.
The goal is to build a **robust and reusable NLP preprocessing pipeline** that can clean and transform noisy real-world text data into structured and meaningful tokens.

---

## 🎯 Objectives

* Design a scalable NLP preprocessing pipeline
* Handle noisy data (emojis, URLs, repeated characters, etc.)
* Apply text normalization techniques
* Perform token-level analytics
* Build clean and modular Python functions

---

## ⚙️ Features Implemented

* Convert text to lowercase
* Remove URLs and email patterns
* Remove numbers
* Remove special characters and emojis
* Handle repeated characters (e.g., "soooo" → "so")
* Remove extra spaces
* Remove short tokens (≤ 2 characters)
* Preserve meaningful words like **"no"** and **"not"**

---

## 🛠️ Technologies Used

* Python
* Regular Expressions (`re`)
* Collections (`Counter`)
* Jupyter Notebook / Google Colab

---

## 📂 Project Structure

```
NLP-Preprocessing-Engine/
│── preprocessing.ipynb
│── README.md
```

---

## 🚀 How It Works

### 1. Preprocessing Function

The function `preprocess_text(text)`:

* Ta
