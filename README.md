# Krishna.AI 🕉️

> Bhagavad Gita AI chatbot powered by a **fine-tuned GPT-4o-mini** model, delivering thoughtful, verse-grounded spiritual guidance.

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Features

- Chat interface trained on Bhagavad Gita teachings
- Fine-tuned GPT-4o-mini model (`ft:gpt-4o-mini-2024-07-18:personal::B204xqSk`)
- Responses grounded in relevant verses with detailed explanations
- Lightweight vanilla HTML/CSS/JS frontend — no build step

## 🚀 Getting Started

1. Clone the repo
   ```bash
   git clone https://github.com/RohanKatara/Krishna.AI.git
   cd Krishna.AI
   ```
2. Open `chat.html` and replace `YOUR_OPENAI_API_KEY` with your OpenAI API key.
   > ⚠️ For production, proxy the API call through a backend — never ship keys in the browser.
3. Serve the folder (e.g. `npx serve .`) and open `index.html`.

## 📁 Structure

```
Krishna.AI/
├── index.html      # Landing page
├── chat.html       # Chat interface
├── styles.css      # Shared styles
├── About us.md     # Project info
└── assets/         # Images & fonts
```

## 🙏 Credits

Built with a fine-tuned OpenAI model and inspiration from the Bhagavad Gita.
