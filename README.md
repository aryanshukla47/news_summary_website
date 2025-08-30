News Summarization using NLP
Overview

This project is an AI-powered news summarization system built with Python and Machine Learning techniques.
It leverages both extractive and abstractive Natural Language Processing (NLP) methods to generate concise summaries of lengthy news articles. The system is designed to help users stay up-to-date with current events quickly and efficiently by reducing the time spent reading multiple articles.

Features

Extractive Summarization – Identifies the most important sentences and generates a direct summary.

Abstractive Summarization – Produces a paraphrased summary in natural language, not limited to original text.

Customizable Summaries – Users can select the desired length of summaries.

Multilingual Support – Summarization available in multiple languages (English, Spanish, French, German, Chinese).

RESTful API Access – Summarization functionality can be accessed programmatically for integration into other applications.

Installation

Clone the repository:

git clone [https://github.com/aryanshukla47/news-summarization-nlp.git](https://github.com/aryanshukla47/news_summary_website/tree/main)

cd news-summarization-nlp


Install dependencies:

pip install -r requirements.txt


Run the application:

python app.py

Usage

Open the web app in your browser at:

http://localhost:5000/


Enter the news article text or URL.

Choose extractive or abstractive summarization.

Select the summary length and click Summarize.

The generated summary will be displayed instantly.

API Usage

Send a POST request to the API endpoint with:

text → The article text

technique → "extractive" or "abstractive"

length → Desired summary length
