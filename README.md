# Stone Paper Scissors

[![Play it](https://img.shields.io/badge/play%20it-samarthjaiswal.github.io%2FStone--Paper--Scissors-081b31?style=flat-square)](https://samarthjaiswal.github.io/Stone-Paper-Scissors/)

A small browser game of Rock, Paper, Scissors against the computer, written in plain HTML, CSS and
JavaScript with no dependencies or build step.

**[Play it →](https://samarthjaiswal.github.io/Stone-Paper-Scissors/)**

![The game after a round: the three choices, a score of 1 to 1, and the message "You lost. scissors beats your paper"](og.png)

## Features

- Pick rock, paper or scissors by clicking (or tabbing to and pressing Enter/Space on) an image.
- The computer picks a random move; the result message turns green for a win, red for a loss
  and stays dark blue for a draw.
- Running score for you and the computer, plus a **Reset score** button.
- Keyboard-accessible buttons with labels, a screen-reader-announced result message, and a
  layout that shrinks to fit phone screens.

## How to run

Open `index.html` in a browser, or serve the folder locally:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

It is also live on GitHub Pages, served straight from the `main` branch.

## Project structure

```
Stone-Paper-Scissors/
├── index.html                          # markup: three choice buttons, score board, message, reset
├── style.css                           # layout and colours, mobile breakpoint at 600px
├── app.js                              # random computer move, win/draw logic, scoring, reset
└── rock.png, paper.png, scissors.png   # choice images
```

## Tech stack

HTML5, CSS3, vanilla JavaScript (ES6).
