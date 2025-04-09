# 🤖 Telegram AI Chatbot Automation using n8n + Hugging Face

This project is a working automation flow built using **n8n**, **Telegram**, and **Hugging Face**, where users can send a message to a Telegram bot, and receive an AI-generated reply from a language model.

---

## 🔧 What It Does

- Accepts incoming Telegram messages
- Forwards the text to a Hugging Face-hosted LLM (like Mistral or LLaMA-based models)
- Sends the model’s response back to the user in Telegram
- Fully automated using a no-code n8n workflow

---

## 🛠️ Tech Stack

- **n8n** – open-source automation platform
- **Telegram Bot API** – for user interaction
- **Hugging Face Inference API** – to access open LLMs
- **ngrok** – for local webhook exposure (during dev)

---

## ⚙️ How to Use

1. Clone or download this repo
2. Import the workflow into n8n
3. Replace the Telegram Bot token and Hugging Face API key with your own
4. Use ngrok or deploy on a public n8n instance
5. Start chatting with your bot!

---

## 📂 Files

- `telegram-ai-chatbot-workflow.json` – The exported n8n workflow
- `README.md` – This documentation

---

## ⚠️ Notes

- This demo uses the **free tier of Hugging Face**, so some models may respond slowly or return blank due to cold starts or limitations.
- You can easily swap in a different model endpoint to improve response quality.

---

## 📷 Preview

<img width="1074" alt="Screenshot 2025-04-09 at 3 48 53 PM" src="https://github.com/user-attachments/assets/6dc53346-33be-4dfc-a7c1-d52ef9559507" />

---

## 💡 Credits

Built by [Shibil](https://github.com/shibil-ai) using automation tools and LLM APIs.

---

## 📬 Let’s Talk

Feel free to fork this project, test it out, and connect if you’d like to collaborate on automation or AI tools!
