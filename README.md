# 🚀 Sandesh's AI-Powered Portfolio

![Portfolio Banner](https://img.shields.io/badge/Portfolio-Live-brightgreen?style=for-the-badge&logo=vercel)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?style=for-the-badge&logo=vercel)
![Gemini](https://img.shields.io/badge/AI-Gemini%202.0-blue?style=for-the-badge&logo=google)

> A modern, responsive personal portfolio website with a built-in AI chatbot — deployed live on Vercel.

🔗 **Live Site:** (https://my-portfolio-nine-gamma-80.vercel.app/)

---

## ✨ Features

- 🎨 **Glassmorphism UI** — Dark theme with animated gradient orbs and smooth scroll
- 🤖 **AI Chatbot** — Powered by Google Gemini 2.0 Flash; answers recruiter questions about my skills, experience & availability
- 📸 **Dynamic Photo Upload** — Click-to-upload profile photo in the About section
- 🏢 **Certification Logos** — Real company logos for Oracle, IBM, TCS & Udemy
- 📱 **Fully Responsive** — Works seamlessly on mobile, tablet & desktop
- ⚡ **Serverless Backend** — Vercel serverless function keeps the API key secure
- 🎞️ **Scroll Animations** — Sections fade in gracefully as you scroll

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| AI Chatbot | Google Gemini 2.0 Flash API |
| Backend | Vercel Serverless Functions (Node.js) |
| Hosting | Vercel (Free tier) |
| Version Control | Git & GitHub |

---

## 📁 Project Structure

```
my-portfolio/
│
├── index.html          # Main portfolio page (UI + chatbot frontend)
│
├── api/
│   └── chat.js         # Serverless function — proxies requests to Gemini API
│
├── vercel.json         # Vercel routing & build configuration
│
└── README.md           # You're reading this!
```

---

## 🤖 How the AI Chatbot Works

```
Recruiter types a question
        ↓
  index.html sends POST to /api/chat
        ↓
  api/chat.js (Vercel serverless function)
        ↓
  Calls Gemini API using secret GEMINI_API_KEY
        ↓
  Returns response → displayed in chat window
```

The API key is stored as a **Vercel Environment Variable** — never exposed to the browser.

---

## 🚀 Getting Started (Run Locally)

### Prerequisites
- A Google Gemini API key (free) from [aistudio.google.com](https://aistudio.google.com)
- [Node.js](https://nodejs.org) installed
- [Vercel CLI](https://vercel.com/docs/cli) installed

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/your-username/my-portfolio.git
cd my-portfolio

# 2. Install Vercel CLI
npm install -g vercel

# 3. Create a .env file for local development
echo "GEMINI_API_KEY=your_api_key_here" > .env

# 4. Run locally with Vercel Dev
vercel dev
```

Open `http://localhost:3000` in your browser.

---

## ☁️ Deployment (Vercel)

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com) → **New Project** → Import your repo
3. Under **Environment Variables**, add:
   ```
   GEMINI_API_KEY = your_gemini_api_key
   ```
4. Click **Deploy** — your live URL is ready in ~60 seconds ✅

---

## 📬 Contact

| Platform | Link |
|---|---|
| 📧 Email | your@email.com |
| 💼 LinkedIn | [linkedin.com/in/your-profile](https://linkedin.com) |
| 🐙 GitHub | [github.com/your-username](https://github.com) |
| ⚡ LeetCode | [leetcode.com/your-username](https://leetcode.com) |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">
  Made with ❤️ by <strong>Sandesh</strong> · MCA Student | Software Developer | Educator
</p>
