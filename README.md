# YouTube Transcript Summarizer

A Streamlit web application that generates detailed summaries from YouTube video transcripts using Google's Gemini AI.

## Features

- Extracts transcripts from YouTube videos
- Generates concise summaries (under 300 words) using Gemini 1.5 Flash AI
- Displays video thumbnail for visual reference
- Simple and intuitive interface

## Prerequisites

Before you begin, ensure you have the following:

- Python 3.7 or higher installed
- A Google API key with access to Gemini AI
- YouTube video links you want to summarize

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/youtube-transcript-summarizer.git
   cd youtube-transcript-summarizer

2Create and activate a virtual environment (recommended):

    ```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required dependencies:

```bash
pip install -r requirements.txt

Create a .env file in the project root and add your Google API key:

env
GOOGLE_API_KEY=your_api_key_here
Usage
Run the Streamlit application:

```bash
streamlit run app.py
The application will open in your default web browser.

Enter a YouTube video URL in the input field.

Click "Get Detailed Notes" to generate the summary.

View the generated summary below the video thumbnail.

Dependencies
streamlit

python-dotenv

google-generativeai

youtube-transcript-api

Configuration
The application can be configured by modifying the following:

.env file: Add your Google API key

app.py: Modify the prompt text or summary length as needed

Limitations
Only works with videos that have transcripts available

May not work with age-restricted or private videos

Summary quality depends on the original video content and transcript accuracy

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements.
