# MindfulChat Pro

A simple AI chatbot for mental health support. Talk to an AI companion that listens and provides helpful responses.

## What it does

- Chat with an AI about your feelings and thoughts
- Get mental health tips and coping strategies
- Available 24/7, no signup required
- Detects crisis situations and provides help resources
- Tracks your mood over time

## Files

- `Chatbot/main.py` - Main chatbot app
- `Chatbot/project/` - Website landing page

## Tech used

- Python + Streamlit (chatbot)
- React + TypeScript (website)

## How to run

### Run the chatbot
1. Install Python packages:
   ```bash
   pip install streamlit groq transformers
   ```

2. Get a Groq API key from [groq.com](https://groq.com) and add it to the code

3. Run the app:
   ```bash
   cd Chatbot
   streamlit run main.py
   ```

### Run the website (optional)
1. Install Node.js packages:
   ```bash
   cd Chatbot/project
   npm install
   ```

2. Start the website:
   ```bash
   npm run dev
   ```

## Important

This is just an AI chatbot, not real therapy. If you're having serious problems, please talk to a real doctor or counselor.
