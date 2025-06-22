Sure! Here’s a clean, polished version of your text with fresh relatable emojis, without the console formatting:

---

# 🎥 **YouTube Comment Sentiment Analyzer**

A complete solution for analyzing **YouTube video comment sentiment** using a **Multinomial Naive Bayes (MNB)** classifier trained on custom-labeled data. This tool processes up to 500 top-level English comments, classifies them as **positive** or **negative**, and presents a detailed sentiment summary highlighting both ratios and the most extreme comments.

---

## ⚡ **Features**

* 🔍 Fetches up to 500 top-level comments from any public YouTube video
* 🧼 Cleans comments (filters by language, length, removes symbols/emojis)
* 🧠 Predicts sentiment using a trained **Naive Bayes** model
* 📊 Displays sentiment breakdown, positive percentage, and confidence scores
* 💬 Highlights the most positive and most negative comments
* 🌐 Interactive frontend for user input

---

## 🤖 **Model Overview**

* **Training Data:** DAIR-AI Text Emotion Classification Dataset (\~42k samples)
* **Preprocessing:**

  * Converts text to lowercase
  * Removes punctuation and emojis
  * Tokenizes text
  * Removes stop words
  * Applies lemmatization
* **Algorithm:** Multinomial Naive Bayes (MNB)
* **Vectorization:** Uses `TfidfVectorizer` with up to 4-grams

---

## 🚀 **How to Get Started**

1️⃣ **Clone the repository**
Clone the project from GitHub and navigate into the directory.

2️⃣ **Install dependencies**
Make sure to install all required Python packages listed in `requirements.txt`.

3️⃣ **Set up the YouTube Data API**

* Create a project in **Google Cloud Console** and enable the **YouTube Data API v3**.
* Generate your **API key**.
* Add your API key to the `fetch_comments.py` file in the `project/res` directory.

4️⃣ **Run the app**
Launch the web application to start analyzing YouTube video comments!

---
