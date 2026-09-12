# 🔥 FLAMES Calculator

A simple browser-based **FLAMES relationship calculator** from **SkyDevLab**.

## 💕 What is FLAMES?

FLAMES is a fun name-matching game that produces one of six playful relationship results:

- **F — Friends 🤝**
- **L — Love ❤️**
- **A — Affection 😊**
- **M — Marriage 💍**
- **E — Enemies 😡**
- **S — Siblings 👫**

> **Note:** This is an entertainment calculator, not a real compatibility or relationship test.

## ⚙️ How It Works

1. Enter two names.
2. The calculator compares the characters in both names.
3. Matching characters are removed from both names.
4. The number of remaining characters is calculated.
5. That count is used to eliminate letters from `FLAMES` until one letter remains.
6. The remaining letter is mapped to the final result.

The core JavaScript uses the standard elimination sequence:

`F → L → A → M → E → S`

## ✨ Features

- Simple and lightweight interface
- Instant browser-based calculation
- No backend or database required
- Handles different name combinations dynamically
- Friendly emoji-based results
- Built with plain HTML, CSS, and JavaScript

## 🛠️ Technologies

- HTML5
- CSS3
- JavaScript

## 🚀 Run Locally

```bash
git clone https://github.com/SkyDevLab/Gravity_Flames.git
cd Gravity_Flames
```

Open the project's HTML file in a modern web browser.

## 🔐 Gravity Safe Code Paste

Also check out **Gravity Safe Code Paste**, a privacy-first developer utility for sanitizing code, SQL, and configuration before sharing it with colleagues, AI assistants, or public forums.

### What it does

- Detects common sensitive information such as passwords, API keys, tokens, connection strings, URLs, and local file paths.
- Supports Java, C#, Python, Config, Other/Mixed Code, and SQL workflows.
- Provides an optional **Change identifiers** mode for replacing project-specific identifiers consistently.
- Shows a replacement mapping so developers can review what changed.
- Runs sanitization locally in the browser for the current MVP.
- Includes a responsive desktop and mobile interface.

### Live Demo

https://skyrunner-dev-ops.github.io/GravitySafeCodePaste/

### Source Code

https://github.com/SkyDevLab/GravitySafeCodePaste

> **Security note:** Gravity Safe Code Paste uses heuristic detection and is not a guarantee that all sensitive information will be found. Always review sanitized output before sharing.

---

Made with ❤️ by **SkyDevLab**