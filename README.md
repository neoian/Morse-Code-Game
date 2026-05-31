# 📡 Morse Code Trainer

A simple, single-file web app for learning Morse code — no frameworks, no dependencies, just plain HTML/CSS/JS.

**[▶ Live Demo](https://neoian.github.io/Morse-Code-Game/)**

---

## Features

- **Reference Table** — All A–Z letters and 0–9 digits with their Morse codes. Click any card to hear the sound.
- **Converter** — Instantly convert text ↔ Morse code with dot/dash visual display and audio playback.
- **Practice Mode** — Three quiz modes:
  - 글자 → 모스 : Type the Morse code for a given letter
  - 모스 → 글자 : Identify the letter from a Morse pattern
  - 듣고 맞추기 : Listen to the beep and type the letter
- **Audio** — Real Morse beeps using the Web Audio API (600 Hz sine wave)
- Score tracking with accuracy percentage

## Usage

No installation needed. Just open `index.html` in any modern browser, or visit the live demo link above.

```
git clone https://github.com/neoian/Morse-Code-Game.git
cd Morse-Code-Game
open index.html
```

## Morse Code Reference

| Symbol | Code | Symbol | Code |
|--------|------|--------|------|
| A | `.-` | N | `-.` |
| B | `-...` | O | `---` |
| C | `-.-.` | S | `...` |
| E | `.` | T | `-` |
| ... | | 0 | `-----` |

## Contributing

Pull requests are welcome! Feel free to open an issue for bug reports or feature suggestions.

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

[MIT](LICENSE) © neoian
