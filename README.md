# 🍎 Royal macOS Terminal Setup

A fully customized macOS terminal startup experience featuring:

- Centered Apple ASCII logo
- Dynamic Figlet welcome banner
- Random quote on every new tab
- Cowsay-formatted quote
- Gradient coloring via lolcat
- ANSI-safe centering (no broken ASCII)
- Clean minimal zsh prompt

Built specifically for macOS (zsh).

---

# 📸 Preview

![Terminal Preview](./preview.png)


---

# ✨ Features

## 🎨 Visual Design
- Apple ASCII logo
- Rainbow gradient output
- Fully centered content
- Dynamic width detection
- Resize-safe layout

## 💬 Smart Greeting System
- Large figlet banner
- Random short quote (`fortune -s`)
- Cowsay formatting
- Clean minimal prompt styling

## ⚙️ Technical Highlights
- Uses `tput cols` to detect terminal width
- Strips ANSI escape codes before measuring length
- Calculates dynamic horizontal padding
- Applies color AFTER centering
- No hardcoded spacing

---

# 🛠 Requirements

## 1️⃣ Install Homebrew (if not installed)

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
