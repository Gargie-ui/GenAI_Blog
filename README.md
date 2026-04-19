# 🤖 AI Blog Generator

A Generative AI web app that creates full, well-structured blog posts from a topic or prompt — powered by the Hugging Face Inference API and built with Flask.

## Demo

**[Try it live](https://gigishot-genai-blog.hf.space/)**

---

## Features

- **Instant Blog Generation** — Enter a topic and get a full blog post in seconds
- **Hugging Face LLM Integration** — Connects to powerful hosted language models via the Inference API
- **Clean Web Interface** — Simple, intuitive Flask-powered UI
- **Secure API Key Handling** — Environment variables via python-dotenv

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Backend | Flask |
| Language | Python |
| AI Model | Hugging Face Inference API |
| LLM Client | huggingface_hub InferenceClient |
| Config | python-dotenv |

---

## How It Works

1. User enters a blog topic or prompt in the web interface
2. Flask sends the prompt to the Hugging Face Inference API via `InferenceClient`
3. A hosted LLM generates a full, structured blog post
4. Output is displayed instantly in the browser

---
