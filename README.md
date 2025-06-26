# newspaper-summarizer
PROJECT CATEGORY
# 🗞️ News Summarizer Web App

🔍 **Summarize the latest headlines from [Times of India](https://timesofindia.indiatimes.com) in seconds.**

---

## 🚀 Overview

This web application allows users to **select a topic** (e.g., Business, Tech, Cricket) and receive **real-time news summaries** powered by machine learning. It fetches the latest headlines from the Times of India and uses a transformer-based NLP model to generate concise summaries.

> Built for the curious reader, the distracted scroller, and the time-crunched professional.

---

## ⚙️ Tech Stack

- **Frontend**: [Streamlit](https://streamlit.io/)
- **Web Scraping**: `requests`, `BeautifulSoup`
- **Summarization**: `transformers` with `distilbart-cnn-12-6` model
- **Model Runtime**: Uses `CUDA` (GPU) if available, falls back to CPU

---

## 🧠 Features

✅ Topic-based news fetching  
✅ Extracts real headlines and article content  
✅ Summarizes long articles using Hugging Face Transformers  
✅ Interactive web interface via Streamlit  
✅ Works locally and can be deployed on Streamlit Cloud

---

## 🎯 Topics Available

- India  
- World  
- Business  
- Tech  
- Cricket  
- Sports  
- Entertainment  
- Auto  
- TV

---

## 💻 How to Run Locally

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/news-summarizer.git
   cd news-summarizer



🔒 Notes
This app scrapes content from a third-party website (Times of India). Use responsibly.


Hugging Face’s summarization models are used under their licensing terms.


Heavy GPU models may take time or require sufficient hardware.



👨‍💻 Author
Built with data, dialogue, and dedication by ✨ ANURAG SAINI ✨
