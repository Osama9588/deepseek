DeepSeek + Groq Streamlit Chatbot

A lightweight Streamlit chat app that runs DeepSeek models served by Groq via LangChain.
It supports streaming responses, model switching, and sane error handling for common LangChain/Pydantic issues.

✨ Features

🗨️ Chat UI built with Streamlit

⚡ Fast inference via Groq (DeepSeek family and others)

🔁 Streaming responses (token-by-token)

🔐 .env-based secrets loading (no keys in code)

🧰 Robust imports with Pydantic forward-ref fix (BaseCache) for mixed LangChain versions

🧪 Developer diagnostics (shows current Python interpreter in the sidebar)

📦 Tech Stack

Python 3.10+ (recommended)

Streamlit

LangChain + langchain-core

langchain-groq (Groq LangChain integration)

groq (Groq Python SDK)

python-dotenv (optional but recommended)
