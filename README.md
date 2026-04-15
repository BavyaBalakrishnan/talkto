# 🎭 TalkTo — Chat with Any Fictional Character

A beautiful web app that lets you have real-time AI-powered conversations with your favorite fictional characters — from Sherlock Holmes to Goku, The Joker to SpongeBob, or literally anyone you can imagine.

![Gemini AI](https://img.shields.io/badge/Powered%20by-Gemini%20AI-orange?logo=google&logoColor=white)
![Vanilla JS](https://img.shields.io/badge/Vanilla-JavaScript-yellow?logo=javascript&logoColor=white)
![Single File](https://img.shields.io/badge/Single-HTML%20File-blue)

---

## ✨ Features

- **20+ Built-in Characters** — From books, movies, cartoons, and anime
- **Chat with Anyone** — Type any character name and start a conversation instantly
- **Stays in Character** — Short, natural, personality-accurate replies — like actually texting them
- **Category Filters** — Browse by 📚 Books, 🎬 Movies, 🎨 Cartoons, or ⚡ Anime
- **Conversation History** — All chats saved locally and resumable anytime
- **Suggestion Chips** — Character-specific conversation starters to break the ice
- **Typing Indicator** — Animated dots while the character is "thinking"
- **Dark Theme UI** — Gorgeous dark interface with purple accents and smooth animations
- **Fully Responsive** — Works on desktop and mobile
- **Zero Dependencies** — Pure vanilla JS in a single HTML file

---

## 🎭 Built-in Characters

| 📚 Books | 🎬 Movies | 🎨 Cartoons | ⚡ Anime |
|---|---|---|---|
| Sherlock Holmes 🔍 | Darth Vader 🖤 | SpongeBob 🧽 | Goku 🔥 |
| Gandalf 🧙 | Jack Sparrow 🏴‍☠️ | Bugs Bunny 🐰 | Naruto 🍥 |
| Elizabeth Bennet 👗 | The Joker 🃏 | Scooby-Doo 🐕 | Light Yagami 📓 |
| Harry Potter ⚡ | Tony Stark 🦾 | Homer Simpson 🍩 | |
| Atticus Finch ⚖️ | Forrest Gump 🏃 | | |
| Jay Gatsby 🥂 | Hannibal Lecter 🎭 | | |
| Gollum 💍 | | | |

> 💡 **Can't find your character?** Just type any name in the search bar — Hermione, Walter White, Elsa, Pikachu — and TalkTo will create a custom chat for them!

---

## 🚀 Getting Started

### Option 1 — Just Open It
1. Clone or download this repository
   ```bash
   git clone https://github.com/BavyaBalakrishnan/talkto.git
   ```
2. Open `index.html` in your browser
3. Pick a character and start chatting!

### Option 2 — Live Demo
> Coming soon — deploy to GitHub Pages, Vercel, or Netlify

---

## 🎯 How to Use

1. **Browse or Search** — Pick a character from the grid or type any name in the search bar
2. **Start Chatting** — Use the suggestion chips or type your own message
3. **Keep Talking** — The AI remembers context from the conversation
4. **View History** — Click 📜 History to revisit past conversations
5. **New Chat** — Click "+ New Chat" to start fresh with a different character

---

## 📸 Screenshots

### Landing Page
> Browse 20+ characters across Books, Movies, Cartoons & Anime with category filters and search

### Chat View
> Real-time conversation with typing indicators, message bubbles, and suggestion chips

### History Panel
> Slide-out panel to revisit and manage past conversations

---

## 🏗️ Project Structure

```
talkto/
├── index.html          # Entire app — HTML + CSS + JS in one file
├── README.md           # You're here
└── demo/
    └── DEMO_CONTENT.md # Social media templates & demo content
```

---

## 🛠️ Tech Stack

- **Google Gemini AI** (`gemini-3.1-flash-lite-preview`) — Powers all character responses
- **Vanilla JavaScript** — No frameworks, no build step, no dependencies
- **CSS3** — Custom dark theme with glassmorphism, animations & transitions
- **LocalStorage** — Conversation history persisted across sessions
- **Google Fonts** — Playfair Display, Inter & JetBrains Mono

---

## ⚙️ How It Works

1. **Character Selection** — User picks a built-in character or types a custom name
2. **Prompt Engineering** — Each message is wrapped in a carefully crafted prompt that instructs Gemini to stay in character with short, natural, texting-style replies
3. **Conversation Context** — The last 10 messages are included in each API call for continuity
4. **Response Rendering** — AI responses are formatted with markdown-style bold/italic support
5. **Auto-Save** — Every exchange is saved to LocalStorage and accessible via the History panel

---

## 🔑 API Setup

The app uses Google's Gemini API. To use your own key:

1. Get a free API key from [Google AI Studio](https://aistudio.google.com/apikey)
2. Open `index.html` and replace the `API_KEY` value at the top of the `<script>` section:
   ```javascript
   const API_KEY = 'your-api-key-here';
   ```

---

## 📝 License

MIT License — feel free to use, modify, and distribute.

---

## 🤝 Contributing

Pull requests are welcome! Ideas for improvement:
- Add more built-in characters
- Add character avatar images
- Add voice input/output
- Add theme customization
- Deploy as a PWA

---

Built with ❤️ and Gemini AI
