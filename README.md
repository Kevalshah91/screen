# 🖥️ AI Screen Share Assistant

A real-time AI assistant that analyzes your screen and responds to voice queries using Google's Gemini API. It captures live screen content and audio from the browser, processes it in a Python backend, and delivers smart replies — both as text and audio — from the Gemini 2.0 Flash model.

---

## 🚀 Features

- 📺 **Live Screen Capture** — Sends continuous snapshots to the AI model.
- 🎤 **Voice Input** — Records mic input and sends it via WebSocket in PCM format.
- 🧠 **Gemini-Powered** — Uses Google's `gemini-2.0-flash-exp` for real-time intelligent feedback.
- 🔊 **Audio Responses** — Plays Gemini's spoken responses using Web Audio API.
- 🌐 **WebSocket Server** — Enables full-duplex communication for low-latency AI interaction.

---

## 🧱 Tech Stack

| Component   | Technology                            |
|-------------|----------------------------------------|
| Frontend    | HTML, JavaScript, Canvas API, Web Audio API |
| Backend     | Python, `websockets`, `google-generativeai` |
| AI Model    | Gemini 2.0 Flash via Generative AI SDK |

---

## 🧪 Usage

1. Allow screen sharing and microphone access when prompted.
2. Click the mic button (🎙️) to start talking.
3. Gemini will analyze both audio and screen image, and respond.
4. Responses show up in the chat log, with audio playback enabled.



