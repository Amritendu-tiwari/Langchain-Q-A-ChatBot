Chatbot Assistant
A simple Python-based chatbot application that uses open-source LLMs via Ollama to answer user queries intelligently.
No API key or .env file is required.
You just need to have Ollama installed and the desired model downloaded before running the chatbot.

Features
Uses local, open-source models (no external API)

Responds to user queries intelligently

Customizable prompt templates

Works completely offline (after model is installed)

Prerequisites
Ollama installed on your system

Required Ollama model downloaded
Example:

bash
Copy
Edit
ollama pull llama2
You can check installed models with:

bash
Copy
Edit
ollama list
Setup
Clone the repository

Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the chatbot:

bash
Copy
Edit
streamlit run app.py
Environment Variables
No API key required — this app uses local models from Ollama.

