# Chill Chacha 🫖

Chill Chacha is a character-first AI chat app that gives calm, grounded life advice in the voice of an Indian uncle.  
No drama. No hype. Just perspective.

---

## What is Chill Chacha

Chill Chacha is a conversational AI designed to feel like talking to a sensible Indian chacha in the evening over chai.

He:
- Normalizes problems
- Slows overthinking
- Gives practical, lived-experience advice
- Avoids therapy jargon and motivational nonsense

This is **not** a medical or clinical tool.

---

## Core Features

- 🧠 Character-driven AI (Indian uncle persona)
- 💬 Text chat mode
- 🎙 Voice chat mode (speech-to-text + text-to-speech)
- 🎨 Clean, warm, modern UI
- ⚡ Fast frontend-first architecture

---
## Try Out
- https://chill-chacha-ai-main.vercel.app/

## Tech Stack

- **Frontend**: React + TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **AI Backend**: Google Gemini API
- **Voice**:
  - Speech-to-Text (browser / API based)
  - Text-to-Speech (browser / API based)

---

## Environment Variables

Create a `.env` file:

VITE_GEMINI_API_KEY=your_api_key_here

Never commit API keys.

---

## Running Locally

npm install npm run dev

---

## Character Rules (Important)

Chill Chacha must always:
- Stay in character
- Speak calmly
- Use simple English with light Indian phrasing
- Avoid emojis
- Avoid preaching
- Avoid diagnosis or clinical language

If conversation becomes extreme, respond with grounding and suggest real human support.

---

## Non-Goals

This app intentionally does NOT include:
- User accounts
- Mood tracking
- Journaling
- Gamification
- Notifications
- Analytics-heavy dashboards

---

## Philosophy

Most people don’t need motivation.  
They need perspective.

Chill Chacha exists to reduce mental noise, not add to it.

---

## Status

Early-stage prototype.  
Character and UX take priority over features.

---

## License

MIT

<a href="https://studio.firebase.google.com/import?url=https%3A%2F%2Fgithub.com%2Fs-hari-haran%2Ffb-test">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://cdn.firebasestudio.dev/btn/open_dark_32.svg">
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://cdn.firebasestudio.dev/btn/open_light_32.svg">
    <img
      height="32"
      alt="Open in Firebase Studio"
      src="https://cdn.firebasestudio.dev/btn/open_blue_32.svg">
  </picture>
</a>
