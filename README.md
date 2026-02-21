# 2048 Glassmorphism Edition

A premium take on the classic 2048 puzzle game, built with pure HTML, CSS, and JavaScript — no dependencies.

![2048](https://img.shields.io/badge/version-5.0-blueviolet) ![License](https://img.shields.io/badge/license-MIT-green)

## Features

- **Glassmorphism UI** — Frosted glass tiles, board, and controls with backdrop blur and soft glow effects
- **Animated Background** — Shifting gradient with floating blurred orbs for depth
- **Particle Effects** — Colorful particle bursts on every tile merge, scaling with tile value
- **Score Animations** — Floating "+points" text on merges and a bouncing score counter
- **Confetti Celebration** — Full-screen confetti shower when you reach 2048
- **Smooth Animations** — Spring-based tile appear/merge animations with satisfying bounce
- **Touch Support** — Swipe to play on mobile devices
- **Persistent Best Score** — High score saved in localStorage

## How to Play

1. Use **arrow keys** (or **swipe** on mobile) to slide all tiles
2. Tiles with the same number **merge** when they collide
3. Each merge adds to your score
4. Reach **2048** to win!

## Run Locally

```bash
# Clone the repo
git clone https://github.com/markwilkinsjr-cmyk/2048.git
cd 2048

# Serve with any static server
python3 -m http.server 8080
# Open http://localhost:8080
```

No build step, no dependencies — just one HTML file.

## Tech Stack

- HTML5 / CSS3 / Vanilla JavaScript
- CSS `backdrop-filter` for glassmorphism
- Canvas API for confetti
- Web Animations API for particles
- Google Fonts (Inter)

## License

MIT
