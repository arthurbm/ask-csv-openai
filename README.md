# Langchain Chat-CSV with OpenAI (Tutorial)
This is a Python application that enables you to load a CSV file and ask questions about its contents using natural language. The application leverages Language Models (LLMs) to generate responses based on the CSV data. The LLM will only provide answers related to the information present in the CSV.

# Installation
1. Clone the repository
2. Install the dependencies
```
pip install langchain openai tabulate python-dotenv streamlit
```

# Usage
1. Create a .env file in the root directory of the project
2. Add your OpenAI API key to the .env file
```
OPENAI_API_KEY=YOUR_API_KEY
```
3. Run the application
```
streamlit run app.py
```
4. Upload a CSV file
5. Ask questions about the CSV data

# References
This code is based on this [repository](https://github.com/alejandro-ao/langchain-ask-csv)

