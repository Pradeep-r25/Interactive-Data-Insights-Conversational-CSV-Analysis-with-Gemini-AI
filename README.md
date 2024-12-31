# Interactive-Data-Insights-Conversational-CSV-Analysis-with-Gemini-AI
Interactive tool for exploring and analyzing CSV data through natural language questions. Powered by Google Gemini AI, this project enables users to load CSV files, view sample data, and ask conversational questions to gain insights effortlessly.

CSV AI Assistant is an interactive tool that allows users to explore and analyze CSV files using natural language questions. Powered by Google Gemini AI, this project makes it simple to derive insights from your data.

Features
Load CSV Files: Easily upload and view sample rows from your CSV files.
Ask Questions: Interact with your data by asking natural language questions.
AI-Powered Responses: Get accurate answers and insights using Google Gemini AI.
Configuration
To use this tool, configure the Gemini API in the script by replacing the placeholder with your API key:

python
Copy code
genai.configure(api_key="")  # PASTE YOUR GEMINI API KEY
model = genai.GenerativeModel("gemini-1.5-flash")
Usage
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
