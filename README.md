# 💬 WhatsApp Web Clone — Feature Concept UI

A frontend-only concept redesign of **WhatsApp Web**, built to propose and demonstrate two new features that the desktop version currently lacks.

### 🌐 [Live Demo → khwaaishpatwa2110.github.io/whatsapp-clone-frontend-only](https://khwaaishpatwa2110.github.io/whatsapp-clone-frontend-only/)

---

## 🎯 Purpose

The real WhatsApp Web has limitations that this project aims to address through a UI proof-of-concept. Two specific features were designed and implemented:

### ✨ Feature 1 — Custom Chat Wallpaper
Set a wallpaper of your choice for the chat background. The current desktop WhatsApp doesn't let users personalise their chat window background the way the mobile app does. This project adds that capability directly to the web interface.

### 📱 Feature 2 — Multi-Device Phone Linking
Link **multiple mobile phones** (up to 3) to a single PC. Currently, WhatsApp Web only supports one primary phone. This concept extends the Linked Devices section in Settings to allow users to connect additional phones — each with live device status shown (active, last seen, etc.).

---

## 🖥️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure and page layout |
| Tailwind CSS (CDN) | Styling and dark theme |
| Vanilla CSS | Custom scrollbar, background wallpaper, page switching |
| Pure CSS `:target` | Zero-JS page navigation between Chat and Settings |

> **No JavaScript. No frameworks. No backend.** This is a pure HTML + CSS single-file application.

---

## 📁 Project Structure

```
whatsapp-clone-frontend-only/
│
├── index.html       # Main app (single file — all HTML, CSS, and layout)
├── bg.jpeg          # Chat background wallpaper image
└── pfp.jpg          # Profile picture used in sidebar and settings
```

---

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/khwaaishpatwa2110/whatsapp-clone-frontend-only.git
   ```

2. Place your own `bg.jpeg` (wallpaper) and `pfp.jpg` (profile photo) in the same directory as `index.html`.

3. Open `index.html` in any modern browser — no server or build step required.

---

## 📸 Features at a Glance

- **Dark mode UI** matching WhatsApp's official colour palette (`#111b21`, `#202c33`, `#005c4b`)
- **Chat list sidebar** with active chat highlight and unread badge
- **Mock conversation** demonstrating the multi-device feature in context
- **Settings page** with a fully designed Linked Devices section showing three linked phones with status indicators
- **Custom wallpaper** rendered as the chat window background via CSS
- **CSS-only navigation** — the Settings page is toggled using the `:target` pseudo-class with zero JavaScript

---

## 📌 Note

This is a **frontend-only static UI prototype**. It contains no real messaging functionality, authentication, or backend logic. It was built as a feature concept demonstration.

---

## 👤 Author

**Khwaaish Patwa**  
[GitHub Profile](https://github.com/khwaaishpatwa2110)
