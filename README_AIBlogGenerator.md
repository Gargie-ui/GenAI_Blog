# 🤖 AI Blog Generator

A Generative AI web app that creates full, well-structured blog posts from a topic or prompt — powered by the Hugging Face Inference API and built with Flask.

---

## 🚀 Features

- 📝 **Instant Blog Generation** — Enter a topic and get a full blog post in seconds
- 🤗 **Hugging Face LLM Integration** — Connects to powerful hosted language models via the Inference API
- 🌐 **Clean Web Interface** — Simple, intuitive Flask-powered UI
- 🔐 **Secure API Key Handling** — Environment variables via python-dotenv

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

## 📁 Project Structure

```
GenAI_Blog/
│
├── templates/
│   └── index.html        # Web UI
├── .env                  # API key (not committed)
├── app.py                # Flask app
└── requirements.txt
```

---

## ⚙️ Setup & Run

```bash
# 1. Clone the repo
git clone https://github.com/Gargie-ui/GenAI_Blog
cd GenAI_Blog

# 2. Install dependencies
pip install -r requirements.txt

# 3. Add your Hugging Face API key
echo "HF_API_KEY=your_api_key_here" > .env

# 4. Run the app
python app.py
```

Then open `http://localhost:5000` in your browser.

> 🔑 Get your free Hugging Face API key at [huggingface.co/settings/tokens](https://huggingface.co/settings/tokens)

---

## 📦 Requirements

```
flask
python-dotenv
huggingface_hub
```

---

## 💡 How It Works

1. User enters a blog topic or prompt in the web interface
2. Flask sends the prompt to the Hugging Face Inference API via `InferenceClient`
3. A hosted LLM generates a full, structured blog post
4. Output is displayed instantly in the browser

---

## 🔐 Environment Variables

Create a `.env` file in the root directory:

```
HF_API_KEY=your_huggingface_api_key
```

> ⚠️ Never commit your `.env` file — add it to `.gitignore`

---

## 👩‍💻 Author

**Gargi Channe**
- 🔗 [LinkedIn](https://www.linkedin.com/in/gargi-channe)
- 🐙 [GitHub](https://github.com/Gargie-ui)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
