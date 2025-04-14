# fake_news_detector
from pathlib import Path

readme_content = """
# 📰 Fake News Detection App

A machine learning-powered web app to detect whether a news article is **Real or Fake**.  
Users can input news content in three ways:

✅ Paste the news article manually  
✅ Provide a URL to scrape and analyze the article  
✅ Upload an image of a printed or screenshot article (OCR-supported)

It also analyzes the **sentiment** (Positive, Negative, or Neutral) of the news content.

---

## 📸 Screenshot (UI Preview)

![App Preview](news_image.png)

---

## 🚀 Features

- 🔍 **Real or Fake Prediction** using a trained ML model (`Multinomial Naive Bayes`)
- 💬 **Sentiment Analysis** using `TextBlob`
- 🌐 **Web Scraping** from any valid article URL
- 📷 **Image Upload & OCR** (Extracts text from images)
- 📥 **Downloadable result report**
- 🔁 **Model Retraining Option** using a new `news.csv` dataset
- 🔐 **Secure and User-Friendly Interface** using Streamlit

---

## 📁 Project Structure

