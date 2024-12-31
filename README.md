#Interactive Data Insights: Conversational CSV Analysis with Gemini AI

CSV AI Assistant is an interactive tool designed to help users explore and analyze CSV files using natural language questions. Powered by Google Gemini AI, this project simplifies data analysis by enabling conversational interactions and quick insights.

Features:
Load CSV Files: Upload and view sample rows from your CSV files effortlessly.
Ask Questions: Interact with your data through natural language questions.
AI-Powered Responses: Receive accurate answers and insights using Google Gemini AI.

Configuration:
To use this tool, configure the Gemini API by replacing the placeholder with your API key in the script:
genai.configure(api_key="")  # PASTE YOUR GEMINI API KEY  
model = genai.GenerativeModel("gemini-1.5-flash")  

Usage:
Run the notebook.
Enter the path to your CSV file when prompted.
Ask questions about the CSV data in natural language.
Type exit to quit the application.
Example Questions
"What is the total number of rows in the dataset?"
"What are the column names?"
"Show me the first 5 rows."
Acknowledgements
Powered by Google Gemini AI.
Built with Python and Jupyter Notebook.











