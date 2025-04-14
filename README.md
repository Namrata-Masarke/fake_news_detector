# 📰 Fake News Detection App

A powerful and interactive Streamlit web application to detect **fake news** using **Machine Learning**, **OCR**, and **Sentiment Analysis**.

---

## 🚀 Features

- 🔍 Detect fake/real news from:
  - Manually pasted news text
  - News article URLs (auto scraping)
  - Uploaded images (via OCR using Tesseract)
- 💬 Sentiment analysis using TextBlob
- 🧠 Confidence score with prediction
- 🔁 Retrain the model using a custom `news.csv`
- 📥 Download prediction result as `.txt`
- 🖼️ Upload image files to extract and verify news content
- 📜 Logging supported (`app.log`)

---

## 🧰 Tech Stack

- Python
- Streamlit
- scikit-learn
- TextBlob
- BeautifulSoup
- Tesseract OCR
- PIL (Pillow)
- Logging

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/fake-news-detector.git
cd fake-news-detector



2. Create a Virtual Environment (optional but recommended)
bash
Copy code
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows
3. Install Dependencies
Install all required libraries using pip:

bash
Copy code
pip install -r requirements.txt
4. Install Tesseract OCR Engine
Windows: Download EXE from Tesseract OCR
Linux:
bash
Copy code
sudo apt install tesseract-ocr
Mac:
bash
Copy code
brew install tesseract
📁 Required Files
model.pkl: Pre-trained ML model and vectorizer (generated after training)

news.csv: Dataset used for model training (text and label columns)

news_image.png: Optional UI image

app.log: Auto-generated logs

result.txt: Downloadable prediction output

💡 How to Use
Launch the App
Run the following command to start the app:

bash
Copy code
streamlit run app.py
Interface Options
Paste News Article: Manually enter the article content.

Paste Article URL: Enter the link to a news article; it will be scraped automatically.

Upload News Image: Upload an image; OCR will extract and analyze the text.

Results
🧠 Prediction: Shows whether the article is Fake or Real

💯 Confidence: Prediction probability

💬 Sentiment: Positive / Negative / Neutral

📥 Option: Download results as .txt file

🔄 Retraining the Model
Click the "🔁 Retrain the Model" button. Ensure news.csv is present in the root directory.

📓 Logging
All predictions and events are logged in app.log for audit or debugging purposes.

🧑‍💻 Author
Name: Namrata Masarke

Email: namratamasarke@gmail.com

LinkedIn: LinkedIn Profile

GitHub: GitHub Profile

📄 License
This project is open-source and available under the MIT License.

📸 Sample Screenshots
1. Home Page

2. Text-based Input

3. URL-based Input

4. Image Upload with OCR

🚀 Usage Demo
To run the app, follow these steps:

Open a terminal and navigate to the project directory.

Run the following command:

bash
Copy code
streamlit run app.py
The app will launch in your browser. You'll be able to:

Paste a news article text directly

Paste a URL and scrape the news article

Upload an image with OCR for extracting news text

Once you've provided an input, the app will display:

Whether the news is real or fake

The confidence level of the prediction

The sentiment of the article (Positive / Negative / Neutral)

The option to download the result as a .txt file
