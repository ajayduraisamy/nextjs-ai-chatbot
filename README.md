✨ A clear project intro (what this repo is and why it’s useful)

🛠️ Features section (what’s included in the template)

⚡ Installation steps (how to run it locally)

🚀 Deployment steps (Vercel one-click + manual option)

📊 Tech stack badges (Next.js, Tailwind, shadcn, AI SDK, etc.)

🎥 Optional demo GIF or screenshot (app preview)

🤝 Contributing guidelines (if open-source)

# 🤖 Next.js AI Chatbot Template

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js" />
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/AI%20SDK-FF6F00?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel" />
</p>

<p align="center">⚡ Build your own AI-powered chatbot with <b>Next.js App Router</b>, <b>AI SDK</b>, and <b>shadcn/ui</b>.</p>

---

## 🚀 Features

- ⚡ **Next.js 14 (App Router)** – advanced routing, React Server Components, and server actions
- 🧠 **AI SDK** – unified API to connect with OpenAI, Anthropic, Cohere, xAI, and more
- 🎨 **shadcn/ui + TailwindCSS** – beautiful, accessible UI components
- 💾 **Data persistence** – Neon Postgres (chat history) + Vercel Blob (file storage)
- 🔐 **Authentication** – simple and secure with Auth.js
- ☁️ **Deploy-ready** – optimized for Vercel

---

## 📦 Getting Started

### 1️⃣ Clone the repo

```bash
git clone https://github.com/ajayduraisamy/nextjs-ai-chatbot.git
cd nextjs-ai-chatbot


2️⃣ Install dependencies
pnpm install

3️⃣ Set up environment variables

Copy .env.example → .env.local and fill in your API keys.
⚠️ Never commit .env.local (it contains secrets).

4️⃣ Run locally
pnpm dev


App runs on http://localhost:3000 🎉


🚀 Deploy to Vercel

One-click deploy:


Or manually:

npm i -g vercel
vercel

🛠️ Tech Stack

Frontend: Next.js 14, React, TailwindCSS, shadcn/ui

Backend: Next.js Server Actions, AI SDK

AI Providers: OpenAI, Anthropic, Cohere, xAI (default)

Database: Neon Postgres

Storage: Vercel Blob

Auth: Auth.js

📊 Example Dataset (Optional if relevant to AI tasks)

If you’re training or fine-tuning, ensure datasets are stored in /data and not pushed with secrets.

🤝 Contributing

Contributions are welcome!

Fork the repo

Create your feature branch (git checkout -b feature/my-feature)

Commit changes (git commit -m "Added new feature")

Push branch (git push origin feature/my-feature)

Open a PR 🚀

📜 License

This project is open-source under the MIT License.

<p align="center"> <img src="https://komarev.com/ghpvc/?username=ajayduraisamy&label=Repo+Views&color=blueviolet&style=flat-square" alt="views"/> </p>
```
