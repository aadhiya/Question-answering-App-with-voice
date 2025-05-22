# 🤖 Gemini + Tavily QA Assistant with Voice

A Streamlit-powered AI assistant that:
- Takes user questions
- Searches the web with **Tavily API**
- Generates accurate answers using **Gemini Pro (Google Generative AI)**
- Reads answers aloud using **Coqui TTS**

---

## 🚀 Features

✅ Real-time question answering  
✅ Web search via Tavily  
✅ Gemini-generated answers  
✅ Voice playback using open-source TTS  
✅ Clean modular codebase for easy extension

---

## 📁 Project Structure

qa_voice_app/
├── app.py
├── .env
├── requirements.txt
└── modules/
├── llm.py
├── retriever.py
├── voice.py
└── prompts.py

---

## 🔧 Setup Instructions

### 1. Clone the repo and install requirements:
```bash
git clone https://github.com/yourusername/qa_voice_app.git
cd qa_voice_app
pip install -r requirements.txt

### 2. Add your API keys to .env
GOOGLE_API_KEY=your_google_api_key_here
TAVILY_API_KEY=your_tavily_api_key_here

### 3. Run the app:

streamlit run app.py
---
## 🔊 Voice

Uses Coqui TTS for generating realistic speech from AI-generated answers.
Model: tts_models/en/ljspeech/tacotron2-DDC
---

## 📦 Dependencies

    streamlit

    google-generativeai

    tavily-python

    langchain

    chromadb

    coqui-tts

    python-dotenv
