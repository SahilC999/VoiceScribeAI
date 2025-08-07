# 🎙️ VoiceScribeAI

**VoiceScribeAI** is an AI-powered web application for voice transcription, text translation, summarization, and transliteration. Built with **Next.js**, **Google Genkit**, and **Firebase**, it provides an interactive platform to process audio and text using state-of-the-art AI models like **Gemini 2.0**.

---

## 🔧 Features

- 🎧 **Generate Transcripts** – Convert audio files into accurate, readable text.
- 🌍 **Translate Text** – Translate transcribed or input text into multiple languages.
- 🪶 **Summarize Content** – Get concise summaries of long transcripts or text blocks.
- 🈂️ **Transliterate Text** – Convert text between scripts like Latin ↔ Devanagari, etc.

---

## 🚀 Technologies Used

- **Next.js 14** – Full-stack React framework
- **Google Genkit** – AI orchestration framework
- **Google Gemini 2.0 Flash** – LLM used via Genkit
- **Firebase** – Hosting and project configuration
- **Tailwind CSS** – Utility-first UI styling

---

## 🛠️ Project Structure

summarization-app/
├── src/
│ ├── ai/ # AI flows for summarize, translate, etc.
│ ├── app/ # Next.js pages and layout
│ ├── components/ # Reusable UI components
├── public/ # Static assets
├── .env # Environment variables
└── genkit.config.ts # Genkit setup



---

## 📦 Getting Started

### 1. Clone the Repo

git clone https://github.com/SahilC999/VoiceScribeAI.git
cd VoiceScribeAI


2. Install Dependencies
npm install
# or
yarn install


3. Set Up Environment Variables
Create a .env file and add your Google AI keys or Firebase config as needed.

4. Run the Development Server
npm run dev
🧠 Example Use Case
Upload an audio file → Convert to text → Summarize or translate it → View output instantly in the browser.

📤 Deployment
VoiceScribeAI can be easily deployed on:

Firebase Hosting
Vercel
Netlify


🙌 Credits
Built using Genkit by Google.

Inspired by real-world transcription needs in healthcare, education, and journalism.
