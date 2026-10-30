# Memorama

A memory game written in Python with `turtle` and `freegames`.
Flip two tiles at a time and find all the matching pairs.

## Requirements

- Python 3
- [freegames](https://pypi.org/project/freegames/)

## How to run

```bash
pip install -r requirements.txt
python memory.py
```

## How to play

Click a tile to show its symbol, then click another tile. If the two match,
they stay revealed. The game ends when all pairs are found. The tap counter
at the top of the window shows how many clicks you used. Try to finish with
as few taps as possible.

## Changes made to the original game

The game started from the `memory` example included in `freegames`. We changed it to:

- Count and show the number of taps
- Use letters and symbols instead of numbers
- Track the pairs still missing and end the game when all of them are found
- Center each symbol on its tile

## Contributors

- *[Dilosch03](https://github.com/Dilosch03): end-of-game detection, centering the symbols
- [jcontreras13](https://github.com/jcontreras13): tap counter, letters and symbols instead of numbers