🧠 LangChain Q&A Chatbot with OpenAI
An interactive Q&A chatbot built with LangChain, Streamlit, and OpenAI's GPT models.
You can ask questions and get AI-generated answers instantly!

✨ Features
Chat Interface – Simple text input to ask your questions.

Customizable Settings – Choose your model, temperature, and max tokens.

Environment-based API Key – Keep your OpenAI API key safe in a .env file.

Streamlit UI – Clean, responsive design.

🛠 Tech Stack
Python 3.9+

LangChain

OpenAI API

Streamlit

python-dotenv

📦 Setup Instructions
1️⃣ Prerequisites
Python 3.9 or above

An OpenAI API Key → Get one here: OpenAI API Keys

Git

2️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/langchain-chatbot.git
cd langchain-chatbot
3️⃣ Create and Activate Virtual Environment
bash
Copy
Edit
python -m venv venv
venv\Scripts\activate    # On Windows
# OR
source venv/bin/activate # On Mac/Linux
4️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
5️⃣ Setup .env File
Create a .env file in the root directory and add your OpenAI API key:

ini
Copy
Edit
OPENAI_API_KEY=your_openai_api_key_here
⚠️ Never commit your .env file or API keys to GitHub.

6️⃣ Run the App
bash
Copy
Edit
streamlit run app.py