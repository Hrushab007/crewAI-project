Local News Digest AI - README
 Introduction
 This project is a Local AI News Summarizer built using Google Colab, Gradio, and the
 Google Gemini API. It automatically fetches the latest Pune news articles from the
 Times of India RSS feed, summarizes them using Gemini AI, and categorizes them into
 predefined categories such as:
 Local News
 Politics
 Business
 Sports
 Technology
 Entertainment
 Lifestyle
 Features
 Fetches top 5 latest Pune news articles from the Times of India RSS feed.
 Scrapes full article content using BeautifulSoup.
 Summarizes news articles using Google Gemini 1.5 Flash model.
 Classifies articles into predefined categories with text indicators.
 Clean, user-friendly Gradio interface.
 One-click button to generate the daily news digest.
 Accordion-based UI for expandable results display.
 Tech Stack
 Python
 Google Colab
 Gradio
 Google Gemini API (
 BeautifulSoup4
 Requests
 JSON
 RSS feed parsing
 gemini-1.5-flash )
 How It Works
 1. User clicks the "Generate Today's Digest" button in the Gradio interface.
 2. The app fetches the top 5 latest news articles from the Pune RSS feed.
 3. Full article content is retrieved and cleaned using BeautifulSoup.
 4. Google Gemini 1.5 Flash model summarizes and classifies the articles.
 5. Summaries and categories are displayed in an accordion view.
 6. Users can click "Read Full Article" to view the complete story.
 Requirements
 Python 3.8+
Google Colab environment
 Gradio library
 BeautifulSoup4
 Requests library
 Google Generative AI Python SDK
 Times of India RSS feed URL for Pune news
 Setup Instructions
 1. Open the project in Google Colab.
 2. Install necessary libraries:
 pip install gradio beautifulsoup4 requests google-generativeai
