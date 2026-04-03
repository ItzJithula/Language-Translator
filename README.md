# 🌐 Modern Language Translator
 
A sleek, single-file language translator web app with a glassmorphism UI, dark/light theme toggle, text-to-speech, and clipboard copy — powered by the MyMemory Translation API.
 
> Built by **Jithula Bhasitha** for [Bit X Tools](https://bit-x-tools.vercel.app)
 
---
 
## ✨ Features
 
- 🌍 **90+ Languages** — Translate between a wide range of world languages
- 🔄 **Swap Languages** — Instantly swap source and target languages with one click
- 🌙 / ☀️ **Dark & Light Theme** — Toggle with a beautiful animated switch; preference saved in `localStorage`
- 🔊 **Text-to-Speech** — Listen to both input and translated text in the correct language
- 📋 **Clipboard Copy** — Copy either text box to clipboard with one click
- ⚡ **Single File** — Entire app lives in one `index.html` — no build tools, no dependencies to install
- 📱 **Fully Responsive** — Works great on desktop, tablet, and mobile
 
---
 
## 🚀 Getting Started
 
### Option 1 — Just open it
 
Download `index.html` and open it in any modern browser. That's it.
 
### Option 2 — Clone the repo
 
```bash
git clone https://github.com/your-username/language-translator.git
cd language-translator
```
 
Then open `index.html` in your browser — no server required.
 
---
 
## 🛠️ Built With
 
| Technology | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 | Glassmorphism UI, animations, responsive layout |
| Vanilla JavaScript | App logic, API calls, theme management |
| [MyMemory API](https://mymemory.translated.net/) | Free translation engine |
| [Font Awesome 5](https://fontawesome.com/) | Icons |
| [Google Fonts — Poppins](https://fonts.google.com/specimen/Poppins) | Typography |
 
---
 
## 📁 Project Structure
 
Since the entire app is bundled into one file, the internal structure is:
 
```
index.html
├── <head>
│   ├── Font Awesome CDN
│   └── Google Fonts CDN
├── <style>
│   ├── CSS variables (dark/light themes)
│   ├── Glassmorphism component styles
│   └── Responsive breakpoints
├── <body>
│   ├── Top bar (back button + title)
│   ├── Theme toggle button (🌙 / ☀️)
│   ├── Translator card
│   │   ├── Input & output textareas
│   │   ├── Language selectors (90+ options)
│   │   └── Copy & speak icons
│   └── Footer
└── <script>
    ├── Countries data object
    ├── Dropdown population
    ├── Language swap logic
    ├── MyMemory API fetch + error handling
    ├── Theme toggle + localStorage persistence
    └── Copy & text-to-speech handlers
```
 
---
 
## 🌐 API Reference
 
This project uses the free [MyMemory Translation API](https://mymemory.translated.net/doc/spec.php).
 
```
GET https://api.mymemory.translated.net/get?q={text}&langpair={from}|{to}
```
 
No API key is required for basic usage. The free tier allows up to **5,000 characters per day** per IP.
 
---
 
## 🎨 UI Preview
 
| Dark Mode | Light Mode |
|---|---|
| Deep navy glassmorphism | Clean frosted white |
| Purple gradient accents | Purple gradient accents |
| 🌙 Moon toggle | ☀️ Sun toggle |
 
---
 
## 🐛 Known Limitations
 
- Translation quality depends on the MyMemory API — results may vary for rare language pairs
- Text-to-speech availability depends on the user's browser and OS voice support
- The free API tier has a daily character limit per IP address
 
---
 
## 🤝 Contributing
 
Contributions, issues, and feature requests are welcome!
 
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
 
---
 
## 📄 License
 
This project is open source and available under the [MIT License](LICENSE).
 
---
 
## 👨‍💻 Author
 
**Jithula Bhasitha**
- Website: [Bit X Tools](https://bit-x-tools.vercel.app)
- GitHub: [@your-username](https://github.com/your-username)
 
---
 
<p align="center">Made with ❤️ by Jithula Bhasitha for Bit X Tools</p>
