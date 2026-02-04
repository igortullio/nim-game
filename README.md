# Nim Game

A Python implementation of the classic Nim game, where the computer uses a mathematical strategy based on game theory to beat the player.

## About

The Nim game consists of **n** pieces on a board, where two players alternate turns removing between 1 and **m** pieces per round. Whoever takes the last pieces wins.

The computer follows the optimal strategy: always leaving a number of pieces that is a multiple of **(m+1)** for the opponent, guaranteeing victory whenever mathematically possible.

## Features

- Single match against the computer
- Championship mode (best of 3 rounds)
- Winning strategy based on game theory
- User input validation
- Automatic decision of who starts based on strategic advantage

## Getting Started

```bash
git clone https://github.com/igortullio/nim-game.git
cd nim-game
python3 jogo_nim.py
```

## Example

```
Welcome to the NIM game! Choose:

1 - to play a single match
2 - to play a championship

How many pieces? 3
Piece limit per turn? 1

Computer starts!
The computer took one piece.
Now there are 2 pieces on the board.
```

## Tech Stack

- Python 3