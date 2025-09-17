# LinkedIn Post Generator (FastAPI + Groq AI)

A web application built with **FastAPI** that generates authentic and engaging LinkedIn posts using the **Groq AI API**. Users can provide role, purpose, tone, highlights, and other optional inputs, and the app generates a professional LinkedIn post accordingly.

---

## Features

- Create LinkedIn posts with a professional, human, and conversational tone.
- Supports optional fields like key insights, gratitude, hashtags, resources, and more.
- Uses **Groq AI API** for AI-powered text generation.
- Web interface powered by **Jinja2 templates**.
- Handles CORS and static files for smooth frontend integration.

---

## Tech Stack

- **Backend:** FastAPI
- **Frontend Templates:** Jinja2
- **AI:** Groq Llama3-8b-8192 model
- **Middleware:** CORS
- **Other:** python-dotenv for environment variables, python-multipart for form handling, StaticFiles for frontend assets
