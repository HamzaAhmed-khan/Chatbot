# 🤖 Chatbot

A simple **AI-powered chatbot** that allows users to interact with an AI model through a conversational interface. The project demonstrates the basic implementation of user input, AI response generation, and continuous chat interaction.

## 🚀 Features

* 💬 Interactive conversation with AI
* 🤖 AI-generated responses
* ⌨️ Takes real-time user input
* 🔄 Continuous conversation loop
* 🔐 API key support using environment variables or secure secrets

## 🛠️ Technologies Used

* **Python**
* **Google Gemini API**
* **Google GenAI SDK**


## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/chatbot.git
cd chatbot
```

### 2. Install Dependencies

```bash
pip install -U google-genai
```

Or, if a `requirements.txt` file is available:

```bash
pip install -r requirements.txt
```

### 3. Add Your API Key

Store your Gemini API key securely as an environment variable or secret.

Example:

```python
import os
from google import genai

api_key = os.getenv("GEMINI_API_KEY")

client = genai.Client(api_key=api_key)
```

**Never upload your API key directly to GitHub.**

## ▶️ Usage

Run the chatbot:

```bash
python chatbot.py
```

Enter your message when prompted:

```text
You: Hello
Bot: Hello! How can I help you?

You: What is artificial intelligence?
Bot: Artificial intelligence is...

You: bye
Bot: Goodbye!
```

The chatbot continues running until the user enters an exit command such as:

```text
bye
quit
```

## 🧠 How It Works

The chatbot follows a simple process:

```text
User Input
    ↓
Chatbot
    ↓
AI Model
    ↓
Generate Response
    ↓
Display Response
    ↓
Continue Conversation
```

1. The user enters a message.
2. The chatbot sends the message to the AI model.
3. The AI model processes the request.
4. A response is generated.
5. The response is displayed to the user.
6. The chatbot continues until an exit command is entered.

## 🔒 Security

* Keep your API key private.
* Do not hardcode API keys in source code.
* Add `.env` files to `.gitignore` if they contain secrets.
* Never commit sensitive credentials to GitHub.

## 🎯 Learning Objectives

This project helps demonstrate:

* Python programming
* API integration
* Generative AI
* User input handling
* Chat loops
* Prompt-based interaction
* Basic chatbot development

## 🔮 Future Improvements

Possible improvements include:

* Add conversation memory
* Create a web-based chat interface
* Add voice input and output
* Add multiple AI models
* Add streaming responses
* Store conversation history
* Deploy the chatbot as a web application

## 👨‍💻 Author

**Hamza Ahmed Khan**

BSCS Student | AI & Generative AI Learner

## 📄 License

This project is created for learning and educational purposes.
