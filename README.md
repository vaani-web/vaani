 🗣️ Vaani — Free Multilingual Translator

> **वाणी** (*vāṇī*) — Sanskrit for *voice*, *speech*, *expression*

A free, offline-capable Progressive Web App (PWA) for translating across Indian and global languages — right from your browser, no install required.

🌐 **Live App:** [vaani-web.github.io/vaani](https://vaani-web.github.io/vaani)

---

## ✨ Features

- 🌏 **Multilingual Translation** — Supports major Indian languages including Telugu, Hindi, Tamil, Kannada, Malayalam, Bengali, and more
- 📴 **Offline-First** — Powered by a Service Worker; works without an internet connection after first load
- 📱 **Installable PWA** — Add to your home screen on Android or iOS for a native app-like experience
- ⚡ **No Sign-Up Required** — Open and translate instantly, completely free
- 🔒 **Privacy-Friendly** — No tracking, no accounts, no data collection
- 🖥️ **Responsive Design** — Works seamlessly on mobile, tablet, and desktop

---

## 🚀 Getting Started

### Use the App
Simply visit **[vaani-web.github.io/vaani](https://vaani-web.github.io/vaani)** in any modern browser.

### Install as a PWA
1. Open the app in Chrome or Safari
2. Tap the **"Add to Home Screen"** prompt (Android) or use the Share → Add to Home Screen option (iOS)
3. Vaani will appear as an app icon on your device

### Run Locally
```bash
git clone https://github.com/vaani-web/vaani.git
cd vaani
# Serve with any static server, e.g.:
npx serve .
# or
python3 -m http.server 8080
```
Then open `http://localhost:8080` in your browser.

---

## 🏗️ Project Structure

```
vaani/
├── index.html       # Main application — UI and translation logic
├── manifest.json    # PWA manifest (name, icons, theme, display mode)
└── sw.js            # Service Worker for offline caching
```

Vaani is intentionally **lightweight** — no frameworks, no build tools, no dependencies. Pure HTML, CSS, and JavaScript.

---

## 🌍 Supported Languages

| Language   | Script      |
|------------|-------------|
| Telugu     | తెలుగు      |
| Hindi      | हिन्दी       |
| Tamil      | தமிழ்       |
| Kannada    | ಕನ್ನಡ       |
| Malayalam  | മലയാളം      |
| Bengali    | বাংলা       |
| English    | Latin       |

> More languages coming in **Vaani v2**.

---

## 🛣️ Roadmap — Vaani v2

- [ ] **Tenglish Detection** — Automatic detection and handling of Telugu-English code-mixed input
- [ ] **Offline Keyboard Translator** — Type and translate without internet in 6 Indian languages
- [ ] **Expanded Language Support** — Odia, Punjabi, Gujarati, Marathi, Urdu
- [ ] **Voice Input / Text-to-Speech** — Speak your text, hear the translation
- [ ] **Android App** — Native APK with keyboard integration
- [ ] **Copy & Share** — One-tap copy or share of translated text

---

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

1. Fork this repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit: `git commit -m "Add: your feature description"`
4. Push to your fork: `git push origin feature/your-feature-name`
5. Open a Pull Request

### Ideas for Contributions
- Add support for new Indian languages
- Improve mobile UI/UX
- Add language auto-detection
- Write tests for translation accuracy
- Improve Service Worker caching strategies

---

## 🐛 Reporting Issues

Found a bug or have a feature request? Please [open an issue](https://github.com/vaani-web/vaani/issues) with:
- A clear description of the problem
- Steps to reproduce (if applicable)
- Your browser and OS

---

## 📄 License

This project is open source. See the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- Inspired by the rich linguistic diversity of India
- Built for communities that speak multiple languages every day
- *वाणी* — because every voice deserves to be understood

---

<p align="center">
  Made with ❤️ for India's multilingual communities
  <br/>
  <a href="https://vaani-web.github.io/vaani">🌐 Try Vaani</a> · 
  <a href="https://github.com/vaani-web/vaani/issues">🐛 Report a Bug</a> · 
  <a href="https://github.com/vaani-web/vaani/issues">💡 Request a Feature</a>
</p>
