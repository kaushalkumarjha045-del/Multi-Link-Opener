# ⚡ LinkBlast — Multi URL Opener

> Open all your URLs in one click with automatic invalid link highlighting.

![HTML](https://img.shields.io/badge/HTML-5-orange?style=flat-square&logo=html5)
![CSS](https://img.shields.io/badge/CSS-3-blue?style=flat-square&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=flat-square&logo=javascript)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 🔗 Live Demo
👉 [Click here to try it](https://YOUR-USERNAME.github.io/Multi-Link-Opener/)

> ⚠️ Replace `YOUR-USERNAME` with your actual GitHub username after deploying.

---

## 📸 Preview

![LinkBlast Preview](https://via.placeholder.com/900x500/0a0a0f/00f5a0?text=LinkBlast+%E2%80%94+Multi+URL+Opener)

---

## ✨ Features

| Feature | Description |
|---|---|
| ⚡ One-Click Open | Open hundreds of URLs instantly in separate tabs |
| 🔴 Auto-Highlight Invalid URLs | Invalid links highlighted in amber automatically |
| ✕ Not-Found Detection | Blocked or failed URLs flagged in red |
| 🔍 Validate Only Mode | Check URLs without opening any tabs |
| 🗑 Remove Duplicates | Auto-removes repeated URLs |
| ⚙ Auto HTTPS | Adds `https://` to bare domains automatically |
| ⏱ Configurable Delay | Set delay (ms) between tab opens to avoid blocking |
| 📊 Live Stats Dashboard | Shows total / opened / invalid / failed counts |
| 🚫 Pop-up Blocker Warning | Detects and warns if browser blocks tabs |
| 🎨 Dark Mode UI | Sleek dark theme with animated results |

---

## 🚀 How to Use

1. **Paste your URLs** — one URL per line in the text area
2. **Choose options** — auto https, remove duplicates, validate only, delay
3. **Click "⚡ Open All Links"** — all valid URLs open in new tabs
4. **See results** — invalid URLs highlighted in amber, failed ones in red

### Example Input
```
https://google.com
https://github.com
not-a-valid-url
example.com
https://youtube.com
```

### Example Output
- ✅ `https://google.com` → Opened
- ✅ `https://github.com` → Opened
- ⚠️ `not-a-valid-url` → Invalid URL (highlighted in amber)
- ✅ `https://example.com` → Opened (https added automatically)
- ✅ `https://youtube.com` → Opened

---

## 🛠 Tech Stack

- **HTML5** — Structure
- **CSS3** — Styling with animations & dark theme
- **Vanilla JavaScript** — Logic, URL validation, tab management
- **Google Fonts** — Syne + Space Mono typography
- **Zero dependencies** — No frameworks, no libraries, no installs

---

## 📁 Project Structure

```
Multi-Link-Opener/
│
├── index.html       # Main application file
└── README.md        # Project documentation
```

---

## ⚙️ Setup & Deployment

### Run Locally
1. Download or clone this repository
2. Open `index.html` in any modern browser
3. No server or internet connection required

### Deploy on GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings** → **Pages**
3. Set source to **main branch** → **/ (root)**
4. Your site will be live at `https://YOUR-USERNAME.github.io/Multi-Link-Opener/`

---

## ⚠️ Pop-up Blocker Note

Most browsers block multiple pop-ups by default. To allow all tabs to open:

- **Chrome:** Click the pop-up blocked icon in the address bar → Allow
- **Firefox:** Click "Options" in the notification bar → Allow pop-ups
- **Edge:** Click the pop-up blocked icon → Allow for this site
- **Safari:** Preferences → Websites → Pop-up Windows → Allow

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

---

## 🙌 Contributing

Pull requests are welcome! If you find a bug or want to suggest a feature, feel free to open an issue.

---

<p align="center">Made with ❤️ — LinkBlast</p>
