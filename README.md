# **Sentiment Analysis on Tweets Using Logistic Regression**

Welcome to my repository! Here, you'll find my work on **Sentiment Analysis** applied to Twitter data, where I used **Logistic Regression** to classify tweets as either **positive** or **negative** based on their sentiment. This project is an excellent example of applying natural language processing (NLP) and machine learning algorithms to analyze real-time text data from social media.

---

## **Project Overview 🚀**

In this project, I used the **Twitter API** to gather tweet data and performed sentiment analysis using a machine learning model—**Logistic Regression**. I demonstrated how to:
- **Collect tweets using Twitter's API**.
- **Preprocess and clean tweet data for analysis**.
- **Apply TF-IDF vectorization** to convert text data into numerical format.
- **Train and evaluate a Logistic Regression model** for sentiment classification.
- **Visualize the sentiment distribution** and model performance.

---

## **How to Use the Code 🧑‍💻**

Follow these steps to replicate the sentiment analysis task:

### **1. Set Up Twitter Developer Account 📝**
To collect tweets, you'll need a **Twitter Developer** account:
- Go to [Twitter Developer](https://developer.twitter.com/) and sign up.
- Create a **project** and an **application** to get your **API keys** and **access tokens**.
- Store these credentials securely, as you'll use them to authenticate with Twitter's API.

### **2. Install Required Libraries 📦**
Install the required Python libraries:
```bash
pip install tweepy scikit-learn pandas matplotlib seaborn
