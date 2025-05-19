# 🤖 AI Chatbot Version 1.00

A friendly AI Chatbot built with **React + Vite** that answers questions, tells jokes, or shares daily tips — powered by [OpenRouter](https://openrouter.ai).

<a href='https://postimg.cc/7byV9291' target='_blank'><img src='https://i.postimg.cc/J7s213BF/Immagine-2025-04-11-165325.jpg' border='0' alt='Immagine-2025-04-11-165325'/>Chatbot Screenshot</a>

---

## 🚀 Features

- ⚡️ Fast and modern setup with [Vite](https://vitejs.dev/)
- 🧠 Chat with AI (using `mistralai/mistral-7b-instruct`)
- 💬 Smart conversation history
- 🎨 Clean and responsive UI
- 🔐 API key stored safely via `.env`

---

## 📦 Tech Stack

- **React** – Frontend library
- **Vite** – Build tool
- **Axios** – For HTTP requests
- **OpenRouter API** – For AI responses

---

## 🛠️ Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/Domenico85/Ai-Chatbot
cd ai-chatbot
```

### 2. Install dependencies

```bash
npm install
```

### 3. Add your API key (I used openrouter.ai)

```bash
Create a .env file in the root:

VITE_OPENROUTER_API_KEY=sk-your-openrouter-api-key

    🔐 You can get a free key from openrouter.ai.
```

### 4. Run the app

```bash

npm run dev

Visit http://localhost:5173 in your browser.
📁 Project Structure

ai-chatbot/
├── public/
├── src/
│   ├── components/
│   │   └── Chatbot.jsx
│   ├── App.jsx
│   ├── main.jsx
├── .env
├── package.json
└── vite.config.js

```

### 🌟 Future Ideas

    🎲 "Tell me a joke" / "Give me a tip" buttons

    💾 Save chat history to localStorage or backend

    🎨 Add light/dark theme toggle

    🌐 Multilingual support

### 📄 License

### MIT

🙌 Acknowledgements

    OpenRouter

    Mistral AI

    Vite

### Made with ❤️ by DomDev
