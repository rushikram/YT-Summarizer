markdown
# YouTube Transcript Summarizer

A Streamlit application that generates summaries from YouTube video transcripts using Google's Gemini AI.

## Features

- Extracts transcripts from YouTube videos
- Generates concise summaries (under 300 words) using Gemini 1.5 Flash
- Displays video thumbnail for visual reference
- Simple and intuitive interface

## Prerequisites

Before you begin, ensure you have:

- Python 3.7 or higher installed
- A Google API key with access to Gemini AI
- A YouTube video URL to summarize

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/youtube-transcript-summarizer.git
   cd youtube-transcript-summarizer
Create and activate a virtual environment (recommended):

bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required packages:

bash
pip install -r requirements.txt
Create a .env file in the project root and add your Google API key:

env
GOOGLE_API_KEY=your_api_key_here
Usage
Run the Streamlit application:

bash
streamlit run app.py
Open the application in your browser (usually http://localhost:8501)

Enter a YouTube video URL in the input field

Click "Get Detailed Notes" to generate the summary

View the video thumbnail and generated summary

##Technologies Used

Streamlit - Web application framework

Google Gemini AI - AI model for text generation

YouTube Transcript API - For fetching video transcripts

python-dotenv - For environment variable management

##Limitations

Works only with videos that have available transcripts

May not handle very long videos optimally due to token limits

Requires a valid Google API key

