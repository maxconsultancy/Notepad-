Here's a complete GitHub README for your Notepad web app:

```markdown
# 📝 Notepad

A full-featured, browser-based rich text notepad built with vanilla HTML, CSS, and JavaScript. No dependencies, no frameworks — just open and write.

**[Live Demo](https://your-username.github.io/notepad)**

![Notepad Screenshot](screenshot.png)

---

## ✨ Features

- **Rich Text Editing** — Bold, italic, underline, strikethrough, headings (H1/H2/H3), lists, blockquotes, alignment, font size, and text color
- **Multiple Notes** — Create, manage, and switch between unlimited notes
- **Auto-Save** — Notes are automatically saved to `localStorage` every 3 seconds
- **Find & Replace** — Full search with match navigation, replace one or all
- **Import & Export** — Export notes as `.txt` or `.html`; import `.txt`, `.html`, or `.md` files
- **Keyboard Shortcuts** — Fast access to common actions
- **Persistent Storage** — All notes survive page refresh via `localStorage`
- **Zero Dependencies** — Pure HTML/CSS/JS, no build step required

---

## 🚀 Getting Started

### Option 1 — Open Directly
Download `index.html` and open it in any modern browser. That's it.

### Option 2 — Clone the Repo
```bash
git clone https://github.com/your-username/notepad.git
cd notepad
open index.html   # macOS
start index.html  # Windows
xdg-open index.html  # Linux
```

### Option 3 — GitHub Pages
Visit the live hosted version at:
```
https://your-username.github.io/notepad
```

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl + S` | Save note |
| `Ctrl + N` | New note |
| `Ctrl + F` | Open Find & Replace |
| `Ctrl + B` | Bold |
| `Ctrl + I` | Italic |
| `Ctrl + U` | Underline |
| `Ctrl + Z` | Undo |
| `Ctrl + Y` | Redo |
| `Escape` | Close Find bar |

---

## 🛠️ Toolbar Reference

| Control | Description |
|---|---|
| B / I / U / ~~S~~ | Bold, Italic, Underline, Strikethrough |
| H1 / H2 / H3 | Heading levels |
| List icons | Bulleted and numbered lists |
| Quote icon | Blockquote |
| Align icons | Left, center, right alignment |
| Size dropdown | Font size (8px – 26px) |
| Color picker | Custom text color |
| Link icon | Insert hyperlink |
| `</>` icon | Inline code block |
| `—` | Horizontal divider |
| Undo / Redo | History navigation |

---

## 📁 Project Structure

```
notepad/
└── index.html      # Entire app in a single file
```

---

## 💾 Data Storage

All notes are stored in the browser's `localStorage` under the key `notepad_notes`. Notes persist across sessions on the same device and browser. No data is ever sent to a server.

> **Note:** Clearing browser data or switching browsers will erase saved notes. Use **Export** regularly to back up important notes.

---

## 📤 Export & Import

**Export:**
- **TXT** — Plain text version of the note
- **HTML** — Full HTML file preserving all formatting

**Import:**
- Supports `.txt`, `.html`, and `.md` files
- Imported files are added as new notes

---

## 🌐 Deploying to GitHub Pages

1. Fork or clone this repo
2. Push to your GitHub account
3. Go to **Settings → Pages**
4. Set source to `main` branch, `/ (root)` folder
5. Your app will be live at `https://your-username.github.io/notepad`

---

## 🧱 Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Storage | Browser `localStorage` |
| Fonts | Google Fonts (Playfair Display, JetBrains Mono) |
| Hosting | GitHub Pages |

---

## 🔮 Roadmap

- [ ] Markdown preview mode
- [ ] Note tagging and categories
- [ ] Dark / light theme toggle
- [ ] Note pinning
- [ ] Print support
- [ ] Cloud sync (optional backend)
- [ ] PWA support (offline-first)

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add my feature"`
4. Push to the branch: `git push origin feature/my-feature`
5. Open a Pull Request

Please keep the zero-dependency philosophy in mind when contributing.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- [Google Fonts](https://fonts.google.com/) for Playfair Display & JetBrains Mono
- [GitHub Pages](https://pages.github.com/) for free static hosting
- The browser's built-in `contentEditable` and `execCommand` APIs

---

*Built with ♥ using nothing but a text editor.*
```

---

