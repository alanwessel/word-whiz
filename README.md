# word-whiz

# Word Whiz – Daily Word Puzzle

Word Whiz is a browser-based daily word puzzle game built with plain HTML, CSS, and JavaScript.  
The game presents a new puzzle each day, tracks player performance, and validates submitted words against an approved word list.

This repository powers the public game experience hosted via GitHub Pages and embedded on the Think Fast Games website.

---

## LICENSE

The Word Whiz game logic is MIT-licensed.
Puzzle content and branding © Think Fast Games
Contact: thinkfastgames.official@gmail.com

## 🎮 How It Works

- Daily puzzles are selected based on the current date
- Puzzle data and scheduling are loaded from CSV files
- Word validation is performed client-side using a curated JSON word list
- Game state (completion, timing, difficulty) is stored in `localStorage`
- No backend or server is required

---

## 🧱 Tech Stack

- HTML / CSS / Vanilla JavaScript
- CSV parsing via PapaParse
- Static hosting (GitHub Pages)

---

## 📁 Repository Structure

```text
/
├── index.html
├── data/
│   ├── word_whiz_puzzles_with_hints_v2.csv
│   ├── daily_puzzle_schedule.csv
│   └── ApprovedWords4.json
├── README.md
└── LICENSE
