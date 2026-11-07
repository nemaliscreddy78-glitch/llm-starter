# LLM Starter Project

## About This Project
This project is a beginner-friendly introduction to building applications using Large Language Models (LLMs) with Python and the Google Gemini API.

## Requirements
- Python 3.10 or above
- Visual Studio Code
- Google Gemini API Key
- Internet connection

## Project Setup

### 1. Create Virtual Environment

```bash
python -m venv .venv
```

### 2. Activate Virtual Environment

**Windows:**

```bash
.venv\Scripts\activate
```

### 3. Install Required Libraries

```bash
pip install google-genai python-dotenv
```

### 4. Configure API Key

Create a `.env` file in the project folder.

Add your Gemini API key:

```env
GEMINI_API_KEY=your_api_key_here
```

Replace `your_api_key_here` with your actual API key.

## Project Structure

```text
llm-starter/
│
├── .venv/
├── .env
├── README.md
└── main.py
```

## Important Notes

- Never share your API key.
- Never upload your `.env` file to GitHub.
- Use the Gemini API free tier within its usage limits.
- Keep your virtual environment activated while working.

## Technologies Used

- Python
- Google Gemini API
- VS Code
- Python Virtual Environment
- dotenv

## Author

Beginner LLM Project
