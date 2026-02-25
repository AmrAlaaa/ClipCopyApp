<div align="center">

# 📋 ClipCopy App

**A lightweight, local-first clipboard manager for commands and text snippets.**  
No install. No server. No internet. Just open and use.

<br/>

![HTML](https://img.shields.io/badge/HTML-Single%20File-5b8fff?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-Vanilla-a78bfa?style=flat-square&logo=css3&logoColor=white)
![JS](https://img.shields.io/badge/JavaScript-Vanilla-f0db4f?style=flat-square&logo=javascript&logoColor=black)
![Storage](https://img.shields.io/badge/Storage-localStorage-34d399?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-gray?style=flat-square)

</div>

---

## ✨ Overview

ClipCopy App is a personal text and command vault that lives entirely in your browser. Save the commands, snippets, API keys, templates, or any text you reach for repeatedly — then copy them to your clipboard in a single click.

It was built to be **fast, frictionless, and offline-first**. No account. No sync. No distractions.

---

## 🖼️ Preview

> *Dark-mode interface with soft blue/violet accent gradients, monospace command previews, and instant clipboard feedback.*

---

## 🚀 Getting Started

No installation or setup required.

1. **Download** `clipcopy-app.html`
2. **Open** it in any modern browser (Chrome, Firefox, Edge, Safari)
3. **Start saving** your snippets

That's it. The file runs entirely on the client side.

---

## 🧩 Features

| Feature | Description |
|---|---|
| **Save entries** | Add a label (optional) and your text or command |
| **One-click copy** | Click any entry card to instantly copy to clipboard |
| **Visual feedback** | Green glow + toast notification confirms the copy |
| **Edit entries** | Update the title or content of any saved entry |
| **Delete entries** | Remove entries with a single click |
| **Drag & drop reorder** | Reorganise entries in any order you like |
| **Search / filter** | Filter your list in real time as you type |
| **Persistent storage** | Data survives browser closes and system restarts |
| **Keyboard shortcuts** | Full keyboard-driven workflow (see below) |
| **No label required** | Entries without a title display cleanly with no placeholder |
| **Offline** | Zero network requests — works with no internet connection |

---

## ⌨️ Keyboard Shortcuts

| Action | Shortcut |
|---|---|
| Save new entry | `Ctrl` + `Enter` (or `⌘ Enter` on Mac) |
| Save from text field | `Shift` + `Enter` |
| Copy entry to clipboard | `Click` anywhere on the card |
| Open shortcuts panel | `?` |
| Close modal / dialog | `Esc` |
| Reorder entries | Drag the `⠿` grip handle |
| Edit an entry | Hover → click the `✎` icon |
| Delete an entry | Hover → click the `🗑` icon |

---

## 💾 Data Persistence

All data is stored in your browser's **`localStorage`**. This means:

- ✅ Data persists after closing the browser
- ✅ Data persists after restarting your computer
- ✅ No account or login needed
- ✅ No data ever leaves your device
- ⚠️ Data is tied to the specific browser and profile you use
- ⚠️ Clearing browser site data will erase entries

---

## 🗂️ Use Cases

- Terminal commands you use often but never remember
- API endpoint URLs or cURL snippets
- Boilerplate code blocks
- Frequently used email responses or phrases
- SSH aliases, connection strings, credentials (local only)
- Git commands and config snippets
- Anything you'd otherwise keep in a sticky note

---

## 🔧 Technical Details

| Property | Value |
|---|---|
| **Type** | Single-file HTML application |
| **Dependencies** | None (zero external JS libraries) |
| **Fonts** | Google Fonts — `Syne` + `DM Mono` (loaded on first open if online) |
| **Storage** | Browser `localStorage` |
| **Network** | Not required after initial font load |
| **Browser support** | All modern browsers (Chrome, Firefox, Edge, Safari) |
| **File size** | ~20 KB |

---

## 📁 Repository Structure

```
clipcopy-app/
├── clipcopy-app.html   # The entire application — open this in your browser
└── README.md           # You're reading it
```

---

## 🛠️ Customisation

Since it's a single HTML file, everything is editable:

- **Accent colours** — change `--accent` and `--accent2` CSS variables at the top
- **Font sizes** — all sizes are in `px` and easy to locate
- **Default entries** — pre-populate the `entries` array in the `load()` function
- **Storage key** — change `STORAGE_KEY` if you want isolated instances per use case

---

## 📄 License

MIT — free to use, modify, and distribute.

---

<div align="center">

crafted with care by **Amr Alaa**

</div>
