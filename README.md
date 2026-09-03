# 🎀 Happy Birthday, Dyana

A single-file interactive birthday web page — no frameworks, no build step, no dependencies. It has a candle-blowing cake, an interactive dress-up game, an openable letter envelope, and a presentation ticket.

## ✨ Features

- 🕯️ **Interactive cake** — click "Blow the candle" to snuff the flame and trigger fireworks + confetti.
- 👑 **Dress-up game** — tap an item (crown, sash, cake, balloons) and it flies onto the character automatically with a bouncy animation, or drag it into place by hand. Works with touch, mouse, and keyboard.
- 💌 **Letter envelope** — click to open it and reveal a personal message inside.
- 🎫 **Presentation ticket** — a button linking out to an external presentation (Canva or any URL).
- 🎆 **Rich animation & effects** — confetti, canvas-based particle fireworks, scroll-reveal for sections, and glow/sparkle touches throughout.
- ♿ **Accessible** — respects `prefers-reduced-motion`, every interactive element is keyboard-operable (Enter / Space), and has proper `aria-label`s.
- 📱 **Fully responsive** — looks and works great on mobile, tablet, and desktop.

## 🚀 Usage

1. Download `dyana-birthday-v3.html` (rename it however you like).
2. Open it directly in any browser — no server or install needed.

### Deploying with GitHub Pages

```bash
git clone <your-repo-url>
cd <your-repo-name>
# Open the file directly, or enable GitHub Pages from the repo settings
```

After enabling **GitHub Pages** under `Settings → Pages` (branch `main`, folder `/root`), the page will be live at your GitHub Pages URL.

## 🛠️ Customization

All the key settings live near the top of the `<style>` block in the HTML file:

| What | Where |
|---|---|
| Core colors | CSS variables under `:root` (`--raspberry`, `--lavender`, `--gold`, etc.) |
| Letter text | Inside `<div class="env-letter">` |
| Presentation link | Inside `<a class="ticket-btn" href="...">` |
| Post-blow wish messages | The `wishes` array in the JavaScript |
| Dress-up game items & positions | The `.drop-slot` and `.item-chip` elements |

## 📦 Tech Stack

- HTML + CSS + vanilla JavaScript only — one file, zero dependencies, zero build step.
- Google Fonts: `Baloo Bhaijaan 2` and `Almarai`.
- Confetti/fireworks particles are hand-drawn on `<canvas>`, no external library.

## 📄 License

Free to use and modify for personal projects — make it a gift for someone you love 💕

---

Made with love 💕
