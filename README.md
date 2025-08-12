# Chatbot Assistant

A simple Python-based chatbot application that uses the OpenAI API to answer user queries intelligently.  
It requires an .env file to store the OpenAI API key.  
Setup involves installing dependencies, configuring the .env file, and running the chatbot.

## Features
- Responds to user queries intelligently
- Customizable prompt templates
- Environment variable configuration

## Setup
1. Clone the repository
2. Install dependencies:  
   
bash
   pip install -r requirements.txt

3. Create .env file:  
   
OPENAI_API_KEY=your_api_key_here

4. Run the chatbot:  
   
bash
   streamlit run app.py


## Environment Variables
- **OPENAI_API_KEY**: Your OpenAI API key (required)
