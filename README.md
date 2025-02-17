# AI Python Code Reviewer

This project provides an AI-based Python code review tool. It analyzes Python code to identify bugs, logical errors, and areas for improvement, then provides a fixed version with an explanation of the changes.  This version uses Streamlit for the user interface and the Google Gemini API for code analysis.

## Requirements

- Python (Specify a minimum version, e.g., Python 3.8+)
- Streamlit
- Google Generative AI API Key
- python-dotenv

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/rubinapokhrel061/ai-python-code-reviewer.git

Navigate to the project directory:

Bash

cd ai-python-code-reviewer

Install dependencies:

Bash

pip install -r requirements.txt

Set up your .env file:

Create a .env file in the project's root directory and add your Google Gemini API key:

GENAI_API_KEY=your_actual_api_key_here

Markdown

# AI Python Code Reviewer

This project provides an AI-based Python code review tool. It analyzes Python code to identify bugs, logical errors, and areas for improvement, then provides a fixed version with an explanation of the changes.  This version uses Streamlit for the user interface and the Google Gemini API for code analysis.

## Requirements

- Python (Specify a minimum version, e.g., Python 3.8+)
- Streamlit
- Google Generative AI API Key
- python-dotenv

## Installation

1. **Clone the repository:**

   ```bash
   git clone [https://github.com/rubinapokhrel061/ai-python-code-reviewer.git](https://github.com/rubinapokhrel061/ai-python-code-reviewer.git)

## Navigate to the project directory:

Bash
cd ai-python-code-reviewer

## Install dependencies:

Bash
pip install -r requirements.txt

## Set up your .env file:

Create a .env file in the project's root directory and add your Google Gemini API key:

GENAI_API_KEY=your_actual_api_key_here
Important:  Do not commit your .env file to version control.  It should be listed in your .gitignore file.

## Usage
Run the app:

Bash

streamlit run app.py
Input your Python code:

Open the app in your browser.  A text area will be displayed where you can enter the Python code you want to be reviewed.

Generate the review:

Click the "Generate" button. The app will analyze your code and provide:

Bug Report: A description of any issues or bugs found.
Fixed Code: A corrected version of your code.
Explanation: An explanation of the changes made.
