# 🎨 Text Studio

> A powerful online Text Studio — 30+ tools for editing, transforming, cleaning, and repeating text. Instantly, in your browser.

<p align="center">
  <a href="https://amiralikop90.github.io/Text-Studio/">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-Online-success?style=for-the-badge" alt="Live Demo">
  </a>
  <img src="https://img.shields.io/badge/HTML5-Single_File-orange?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/JavaScript-Vanilla-yellow?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="MIT License">
  <img src="https://img.shields.io/badge/Zero-Dependencies-brightgreen?style=for-the-badge" alt="Zero Dependencies">
</p>

---

## 📖 About

**Text Studio** is a sleek, single-file web tool that gives you **30+ useful text utilities** in one place. From simple editing to letter transformation, cleanup, and repetition — everything you need to work with text, right in your browser.

Whether you're a writer cleaning up drafts, a developer transforming data, or just someone who needs to repeat a line 100 times, this tool gets it done in one click.

---

## ✨ Features

### 📝 Editor Tab
- 📄 **Large editor** with monospace font
- 💾 **Auto-save** in localStorage (500ms debounce)
- ↩️ **Undo/Redo** — 50-step history
- 🎨 **Change font** — mono, sans, serif
- 🔍 **Zoom in/out** font size
- ↔️ **Toggle direction** (LTR/RTL)

### 🔤 Transform Tab (10 tools)
- 🔠 **UPPERCASE** — all caps
- 🔡 **lowercase** — all small
- ✨ **Title Case** — Capitalize Each Word
- 📝 **Sentence case** — Capitalize first letter
- 🔄 **tOGGLE cASE** — invert case
- 🔃 **Reverse Text** — mirror the text
- ↕️ **Reverse Lines** — flip line order
- 🔀 **Shuffle Lines** — random line order
- ⬆️ **Sort A-Z** — alphabetical
- ⬇️ **Sort Z-A** — reverse alphabetical

### 🧹 Cleanup Tab (10 tools)
- ✂️ **Remove extra spaces** — multiple → single
- 🚫 **Remove empty lines**
- 🔢 **Remove numbers**
- 🔤 **Remove letters**
- 🎯 **Remove symbols**
- 📏 **Trim lines** — remove leading/trailing spaces
- ⬅️ **Remove duplicate lines**
- 🧹 **Remove all spaces**
- 🚫 **Remove punctuation**
- 😀 **Remove emojis**

### 🔁 Repeat Tab
- 🔁 **Text Repeater** — repeat text 1 to 1000 times
- ➖ **Separator** — newline, space, comma, comma+space, none, custom
- 🔢 **Numbering** — none, `1.`, `(1)`, `1-`
- 🔄 **Swap** — replace editor with result
- 📋 **Copy Result** — copy the repeated text
- 📊 **Live preview** — output character count

### 📊 Live Stats
- 📏 Character count
- 📝 Word count
- 📄 Line count
- 📖 Reading time (200 WPM)

### ⌨️ Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `Ctrl+Z` | Undo |
| `Ctrl+Y` | Redo |
| `Ctrl+S` | Save |
| `Ctrl+K` | Copy |
| `Ctrl+D` | Download |

### 🌐 Internationalization
- 🇮🇷 Persian (فارسی) — RTL
- 🇬🇧 English — LTR
- 🇨🇳 Chinese (中文) — LTR

### 🌙 Themes
- ☁️ **Cloud White** — soft, light, airy
- 🖤 **Matte Black** — deep, flat, no glare

### ⚡ Performance
- 🚀 **Zero backend** — everything runs in your browser
- 💾 **No tracking** — your data never leaves your device
- 📱 **Fully responsive** — mobile, tablet, desktop
- ♿ **Accessible** — ARIA labels, semantic HTML
- 🔍 **SEO-optimized** — meta tags, Open Graph, Twitter Cards, JSON-LD
- 📄 **Footer with license link** — [psoa.ir/licens.html](https://psoa.ir/licens.html)

---

## 🚀 Live Demo

👉 **[https://amiralikop90.github.io/Text-Studio/](https://amiralikop90.github.io/Text-Studio/)**

---

## 🛠️ How to Use

1. Open the live demo
2. Type or paste your text in the editor
3. Switch between tabs: **Editor**, **Transform**, **Cleanup**, **Repeat**
4. Click any tool button to apply it to your text
5. Use **📋 Copy**, **💾 Download**, **🗑️ Clear**, or **↺ Reset** at the bottom

### Example: Repeating Text
1. Go to the **🔁 Repeat** tab
2. Set the count (e.g., `10`)
3. Choose a separator (e.g., newline)
4. Optionally enable numbering
5. Click **Apply Repeat**

---

## 🎯 Use Cases

| Use Case | Description |
|----------|-------------|
| **Writers** | Clean up drafts, remove extra spaces |
| **Developers** | Transform data, sort lines, remove duplicates |
| **Students** | Count words, check reading time |
| **Marketers** | Repeat text for creative content |
| **Designers** | Prepare placeholder text |
| **Everyone** | Quick text fixes on the go |

---

## 📦 Deploy on GitHub Pages

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Under **Source**, select `Deploy from a branch`
4. Choose **Branch:** `main` and **Folder:** `/ (root)`
5. Click **Save** — your site will be live at:
https://amiralikop90.github.io/Text-Studio/

text

---

## 🌍 Supported Languages

| Language | Code | Direction |
|----------|------|-----------|
| 🇮🇷 Persian | `fa` | RTL |
| 🇬🇧 English | `en` | LTR |
| 🇨🇳 Chinese | `zh` | LTR |

Language can be switched from the top bar — your choice is remembered across visits via `localStorage`.

---

## 🎨 Themes

- ☁️ **Cloud White** — soft, light, airy (default)
- 🖤 **Matte Black** — deep, flat, no glare

Toggle from the top-left button. Your preference is saved automatically.

---

## 📁 Project Structure
.
├── index.html # Entire app: HTML + CSS + JS in one file
├── robots.txt # Search engine crawler rules
├── sitemap.xml # URL list for search engines
├── LICENSE # MIT License
└── README.md # This file

text

> The entire application lives inside a **single `index.html`** — no build tools, no bundlers, no `node_modules`.

---

## 🧰 Tech Stack

- **HTML5** — semantic, accessible markup
- **CSS3** — custom properties for theming
- **JavaScript (Vanilla)** — no frameworks, no libraries
- **localStorage** — for auto-save and preferences
- **GitHub Pages** — free static hosting

---

## 🔍 SEO Features

This project ships with production-grade SEO out of the box:

- ✅ Optimized `<title>` and `<meta description>`
- ✅ `hreflang` tags for multilingual content
- ✅ Open Graph (Facebook, LinkedIn, Telegram)
- ✅ Twitter Card (`summary_large_image`)
- ✅ JSON-LD structured data (`WebApplication` schema)
- ✅ Canonical URL
- ✅ `robots.txt` and `sitemap.xml`
- ✅ Google Search Console verified
- ✅ Semantic headings
- ✅ ARIA labels for accessibility

---

## 💾 Data Storage

All data is stored locally in your browser:

- **Editor content** — key: `text_studio_content`
- **Theme** — key: `text_studio_theme`
- **Language** — key: `text_studio_lang`

No data is ever sent to any server.

---

## 🤝 Contributing

Contributions are welcome! If you have ideas for new tools, additional languages, or UI improvements:

1. Fork the repository
2. Create your branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

---

## 🔮 Planned Features (Phase 2)

- 🔍 **Find & Replace** — search and replace with regex
- 📊 **Full Analysis** — letter frequency, word frequency, longest/shortest word
- 🔐 **Encode/Decode** — Base64, URL, HTML, ROT13, SHA-256
- 🎨 **Format** — number lines, prefix/suffix, wrap text, indent
- ✨ **Special** — Lorem Ipsum generator, emoji picker, UUID insert
- 📱 **PWA support** — install as a mobile app
- 🌐 **More languages** — Arabic, Russian, Spanish, German, French
- 📥 **File upload** — drag & drop .txt files
- 🎨 **More themes** — additional color schemes

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

See the [LICENSE](LICENSE) file for details.

For more information, visit the license page:
👉 **[https://psoa.ir/licens.html](https://psoa.ir/licens.html)**

---

## 👤 Author

**Amirali Kamani**

- 🌐 Website: [psoa.ir](https://psoa.ir)
- 💻 GitHub: [@Amiralikop90](https://github.com/Amiralikop90)
- 📜 License page: [psoa.ir/licens.html](https://psoa.ir/licens.html)

---

<p align="center">
  Made with ❤️ — because working with text should be one click away.
</p>
