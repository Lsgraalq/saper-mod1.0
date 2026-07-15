# saper-mod — Minesweeper (PyQt5)

> **Created: May 2022** — learning project (desktop GUI game in Python).

A more complete version of my **Minesweeper** game built with **PyQt5** — an improved follow-up to the earlier `saper` project, with actual gameplay wired up. Built while following a PyQt course.

## Features

- Full **PyQt5** window: status bar with mine counter, a smiley status button (reset / win / lose faces), and a timer.
- Interactive **board** of custom `Cell` widgets using Qt signals (`clicked`, `flagged`, `expandable`, `game_over`, …):
  - left-click to reveal, right-click to flag
  - auto-expansion of empty cells
  - mines, adjacent-mine numbers, and end-of-game reveal
- Three difficulty **levels** (8×8 / 10 mines, 16×16 / 40, 24×24 / 99).
- Image assets for bombs, flags, clock, and status faces in `images/`.

## Running

```bash
pip install PyQt5
python saper.py
```

## Stack

- Python 3
- PyQt5

## License

See [LICENSE](LICENSE). The base project follows a PyQt course by Roman Yatsenko.
