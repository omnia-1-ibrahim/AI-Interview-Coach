# 🎯 AI Interview Coach

An end-to-end AI-powered mock interview system for ML & Data Science roles.

## Features
- 1000+ real interview questions (ML, Deep Learning, Data Science)
- Real-time AI evaluation powered by Groq LLaMA 3.1
- RAG-based question retrieval with random diversity
- Streaming feedback with scoring
- Automated report generation

## Tech Stack
- **Backend**: FastAPI, Python
- **LLM**: Groq (LLaMA 3.1 8B)
- **RAG**: FAISS + Sentence Transformers
- **Frontend**: Streamlit
- **Automation**: n8n webhooks

## Setup
1. Clone the repo
2. Add `GROQ_API_KEY` to environment variables
3. Run backend: `uvicorn backend.main:app`
4. Run frontend: `streamlit run frontend/streamlit_app.py`
