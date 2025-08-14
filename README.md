# 🚀 DeepSeek + Groq Streamlit Chatbot 🤖  

*Your AI-powered chat assistant running DeepSeek models on Groq’s lightning-fast hardware!*  

## 🎯 What is this?  
This is a **Streamlit-based chatbot** powered by **Groq** and **LangChain**, designed to give you blazing-fast AI responses using DeepSeek and other Groq-supported models.  
It’s lightweight, easy to set up, and built to handle common LangChain/Pydantic compatibility issues so you can focus on chatting, not debugging.  

## 🛠️ Features  
✅ **Fast Inference** – Thanks to Groq’s hardware acceleration.  
✅ **DeepSeek Model Support** – Like `deepseek-r1-distill-llama-70b` and more.  
✅ **Streaming Responses** – See tokens appear in real time.  
✅ **Version Compatibility Fixes** – Handles `BaseCache`/Pydantic forward-ref issues.  
✅ **Environment Diagnostics** – Shows which Python interpreter is running in the sidebar.  

## 🚀 Getting Started  
1. **Clone this repo:**  
   ```bash
   git clone https://github.com/Osama9588/deepseek.git
   cd deepseek
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the chatbot:  
   ```bash
   create .env file and add your api key
   GROQ_API_KEY="your_api_key_here'
   ```
4. Run the chatbot:  
   ```bash
   streamlit run app.py
   ```
