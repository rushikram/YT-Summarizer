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


🛠️ Tech Stack
Category	Technology
Frontend	Streamlit (Python web framework)
AI Model	Gemini 1.5 Flash (Google's generative AI)
APIs	YouTube Transcript API
Env Mgmt	python-dotenv (for API key security)
Deployment	Compatible with Streamlit Cloud, AWS, GCP, etc.

## Limitations

Transcript Availability

Only works with videos that have enabled captions (auto-generated or manual).

Fails on videos with disabled transcripts or region-locked content.

AI Constraints

Gemini 1.5 Flash has a ~300-word output limit (hardcoded in the prompt).

May struggle with highly technical content or non-English transcripts.

Performance

Longer videos (>30 mins) may hit API timeout limits.

No caching: Repeated requests for the same video trigger new API calls.

Security

Requires exposing Google API keys in client-side code (mitigated via .env).

YouTube Specifics

Only supports standard YouTube URLs (e.g., ?v=ID). Shorts/embedded links may fail.



