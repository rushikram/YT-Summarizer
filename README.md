📺 YouTube Transcript Summarizer
This is a Streamlit-based web application that extracts the transcript of a YouTube video and summarizes it using Google's Gemini language model. The summary is presented in bullet points and limited to 300 words.

🚀 Features
Extracts transcripts from YouTube videos using youtube-transcript-api

Generates concise and informative summaries using Google's Gemini (via google.generativeai)

Displays the video thumbnail for visual context

Clean, interactive UI with Streamlit

🛠️ Requirements
Python 3.8+

A valid Google API key for Gemini (via Google AI Studio)

YouTube video with a public transcript

📦 Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/youtube-transcript-summarizer.git
cd youtube-transcript-summarizer
Create a virtual environment (optional but recommended):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Set up your environment variables:

Create a .env file in the root directory and add your Google API key:

ini
Copy
Edit
GOOGLE_API_KEY=your_google_api_key_here

RESULTS:
Home Page:
![Screenshot 2025-05-24 124431](https://github.com/user-attachments/assets/76148d10-f6d0-4721-a6d4-be3d5fd08ed6)
After Interaction :
![Screenshot 2025-05-24 124830](https://github.com/user-attachments/assets/f4af3550-ef1f-41f3-a2fa-7ef87850e941)
![Screenshot 2025-05-24 124904](https://github.com/user-attachments/assets/e9fab184-8b25-4129-ae37-9fb508a90982)


