# 🤖 ChatBot-Telegram-AI

An interactive Telegram bot built with **aiogram** and **OpenAI models** that handles real‑time user queries and supports dynamic, multi‑step conversations.

## ✨ Features
- **Function Calling**: Dynamically call backend functions based on user queries and conversation context.
- **Prompt Chaining**: Use context‑aware prompt engineering to generate coherent multi‑step responses.
- **Conversational State Management**: Preserve dialogue history to improve relevance and continuity across turns.
- **Real‑Time Interaction**: Fast, event-driven handling of incoming Telegram messages.

## ⚙️ Tech Stack
- **aiogram** — Asynchronous Telegram Bot API framework
- **OpenAI models** — Natural language understanding & generation
- **Python** — Core language for orchestration and business logic

## 🚀 Getting Started

Create and activate a virtual environment:

bash
Copier le code
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copier le code
pip install -r requirements.txt
🔑 Setup
Bot Token: Create a Telegram bot via @BotFather and get your API token.

OpenAI API Key: Sign up at OpenAI and get an API key.

Environment Variables: Create a .env file in the project root:

ini
Copier le code
TELEGRAM_TOKEN=your_telegram_token
OPENAI_API_KEY=your_openai_api_key
▶️ Running the Bot
bash
Copier le code
python bot.py
Once running, start a chat with your bot on Telegram
