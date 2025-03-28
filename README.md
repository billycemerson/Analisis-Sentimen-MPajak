This project focuses on **Sentiment Analysis of MPajak App Reviews** from Google Play Store. The sentiment is determined based on user ratings:
- **Positive Sentiment:** Ratings 4-5
- **Negative Sentiment:** Ratings 1-3

The goal is to analyze user feedback and classify sentiments effectively.

## 📂 Project Structure
This project consists of:

1. **Code**
   - **Data Collection:**
     - Using `google-play-scraper` to extract reviews from the Google Play Store.
   - **Preprocessing:**
     - Case folding
     - Tokenization
     - Cleaning (removing unnecessary characters, URLs, etc.)
     - Normalization using a custom dictionary
     - Stopword removal
     - Stemming
   - **Feature Extraction & Balancing:**
     - Keras Tokenizer for text processing
     - SMOTE for handling class imbalance
   - **Model Training & Evaluation:**
     - Using **LSTM** for sentiment classification.
     - Performance evaluation using accuracy, precision, recall, and F1-score.

## 🚀 Technologies & Frameworks
- **Python** (pandas, numpy, seaborn, scikit-learn)
- **Natural Language Processing** (Keras Tokenizer, Text Preprocessing)
- **Machine Learning** (LSTM, SMOTE for data balancing)
- **Web Scraping** (`google-play-scraper` for review extraction)
