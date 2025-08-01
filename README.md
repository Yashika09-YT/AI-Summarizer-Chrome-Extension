# 🧠 AI Summarizer Chrome Extension

Summarize the web in seconds — your choice of ✍️ Brief, 📚 Detailed, or 🔘 Bullet Point formats.  
Built with ⚛️ React.js, 🌐 Node.js, 🛢️ MongoDB, and powered by **Gemini AI**.


---

## 🚀 Features

- 🔍 **One-Click Summarization** – Summarize any webpage instantly.
- 🧠 **Gemini AI Integration** – Uses Google’s Gemini LLM for accurate summaries.
- ✨ **Three Summary Modes**:
  - ✍️ **Brief** – 2-3 line overview
  - 📚 **Detailed** – Paragraph-level explanation
  - 🔘 **Bullet Points** – Clean TL;DR-style points
- ⚛️ **Modern UI** – Built with React.js for a responsive and smooth experience.
- 🔐 **Backend API** – Node.js + MongoDB for session handling and secure key usage.
- 🧩 **Chrome Extension Ready** – Easily loadable via Chrome’s Dev Tools.

---

## 🛠️ Tech Stack

| Frontend | Backend | AI/ML | Database |
|----------|---------|-------|----------|
| React.js, Tailwind | Node.js, Express | Gemini API (Google AI) | MongoDB |

---

> Click, Summarize, Done.

---

## 🧪 How It Works

1. User selects a summary mode from the popup.
2. Extension grabs content from the active tab using `chrome.tabs`.
3. Sends it to Gemini via your backend API.
4. Renders the response in the extension popup.

---

