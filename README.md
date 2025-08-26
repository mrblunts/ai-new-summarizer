# News Article Summarizer & Sentiment Analyzer

This project is a Streamlit web app that lets you paste a news article URL, then uses AI to summarize the article and analyze its sentiment (positive, neutral, negative).

## Features

- **Paste a news article link**
- **AI-powered summarization** using Hugging Face Transformers
- **Sentiment analysis** (positive, neutral, negative)
- **Cyberpunk theme** by default for a modern look
- **Smiley face theme toggle icon**

## Tech Stack

- Python
- Streamlit (UI)
- Hugging Face Transformers (NLP)
- Requests, BeautifulSoup4 (web scraping)

## How to Run Locally

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
2. Run the app:
   ```
   streamlit run src/main.py
   ```

## Deployment

Deploy easily on [Streamlit Cloud](https://streamlit.io/cloud) by connecting your GitHub repo.

## Usage

1. Paste a news article URL.
2. Click **Summarize & Analyze**.
3. View the summary and sentiment tone.

---

**Note:** For best results, use news articles
