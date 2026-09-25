# RAG Company Knowledge Agent

A knowledge assistant that answers questions from a controlled company knowledge base using Retrieval-Augmented Generation.

## Features
- LLM-powered question answering or analysis
- Context-aware processing
- Streamlit interface
- Environment-based API configuration
- Clear project structure for extension

## Workflow
User Input -> Context / Schema -> LLM -> Validation or Retrieval -> Result

## Project Structure
```text
rag-company-knowledge-agent/
├── app.py
├── requirements.txt
└── .env.example
```

## Quick Start
```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
pip install -r requirements.txt
```

Configure the required variables in `.env` using `.env.example`, then run:

```bash
streamlit run app.py
```

## Portfolio Focus
**RAG • AI Assistants • Knowledge Bases • LLM Applications • Python**

> Never commit API keys, passwords, or private user/company data.