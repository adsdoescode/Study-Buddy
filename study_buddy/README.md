# Study Buddy 📚

An AI-powered study buddy for students, built with Flask + Gemini API.

## Quick Start (3 steps!)

### 1. Add your API key
Open the `.env` file in this folder and replace the placeholder with your Gemini API key:
```
GEMINI_API_KEY=your-actual-key-here
```
> You can get a free key from [Google AI Studio](https://aistudio.google.com/apikey)

### 2. Run the app
**Double-click `run.bat`** — that's it!

It will install everything automatically and start the server.

### 3. Open in browser
Go to **http://localhost:5000** in your browser.

---

## How it works

- **Frontend** (`index.html`): The chat UI where you type questions
- **Backend** (`app.py`): Flask server that talks to Google's Gemini AI
- **Settings sidebar** (⚙️ button): Customize the system prompt to change how your buddy behaves

## Customizing your buddy

Click the ⚙️ **Settings** button in the top-right to:
- Change the **system prompt** (personality, subjects, grade, etc.)
- Change the **buddy name**
- Toggle **subject chips**

## Files

| File | What it does |
|------|-------------|
| `index.html` | The chat interface (frontend) |
| `app.py` | The Flask server (backend) |
| `.env` | Your API key (keep this secret!) |
| `requirements.txt` | Python packages needed |
| `run.bat` | One-click launcher for Windows |
