🚀 AI Python Code Reviewer

This project provides an AI-based Python code review tool built with Streamlit and the GoogleAI API. The app allows users to input their Python code and analyzes it to identify bugs, logical errors, or areas for improvement. It then provides a fixed version of the code along with an explanation of the changes made.

 📌Requirements

- Python 
- Streamlit
- Google Generative AI API Key
- python-dotenv

💡 Installation

📌Clone the repository:
  ```bash
   git clone https://github.com/rubinapokhrel061/ai-python-code-reviewer.git

📌 Navigate to the project directory:
```bash
   cd ai-python-code-reviewer

📌 Install dependencies:
```bash
   pip install -r requirements.txt

📌Set up your .env file:
Create a .env file in the project's root directory and add your Google Gemini API key:
GENAI_API_KEY=your_actual_api_key_here

📌 Usage

Run the app:
```bash
  streamlit run app.py

Input your Python code:
Open the app in your browser.  A text area will be displayed where you can enter the Python code you want to be reviewed.
Generate the review:

Click the "Generate" button. The app will analyze your code and provide:

Bug Report: A description of any issues or bugs found.
Fixed Code: A corrected version of your code.
Explanation: An explanation of the changes made.


