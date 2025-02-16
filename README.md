# AI Python Code Reviewer

This project provides an AI-based Python code review tool built with Streamlit and the Google Gemini API. The app allows users to input their Python code and analyzes it to identify bugs, logical errors, or areas for improvement. It then provides a fixed version of the code along with an explanation of the changes made.

## Requirements

To run the app, ensure you have the following:

- **Python **
- **Streamlit**
- **Google Generative AI API Key**
- **Python-dotenv**

## Installation

To set up the project on your local machine:

1. **Clone the repository**:

   Clone the repository from GitHub to your local machine:

   ```bash
   git clone https://github.com/rubinapokhrel061/ai-python-code-reviewer.git
Navigate into the project directory:

2.Change your working directory to the newly cloned project folder:

cd ai-code-reviewer
Install the required dependencies:

Install all required Python dependencies using pip
pip install -r requirements.txt

Set up your .env file with your Google Gemini API Key:

Create a .env file in the root directory of your project and add the following, replacing your_api_key_here with your actual API key from Google Gemini:

GENAI_API_KEY=your_api_key_here

Usage
To use the app, follow these steps:

Run the app with Streamlit:

Launch the app by running the following command in your terminal:

streamlit run app.py
Input your Python code:

Once the app is running, open it in your browser. You'll see a text area where you can input the Python code you want to be reviewed.

Click "Generate":

After entering your Python code, click the "Generate" button to analyze the code. The app will provide:

Bug Report: A detailed description of any issues or bugs found in your code.
Fixed Code: A corrected version of the code with improvements and fixes.
Explanation: An explanation of the changes made and why they are necessary.
