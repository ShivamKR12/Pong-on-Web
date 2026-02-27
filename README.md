# Pong

A simple cross-platform Pong game built with pygame-ce.

The game runs on desktop, mobile (Android), and the web (via pygbag).

## Features

- Classic Pong gameplay
- Keyboard controls on desktop
- Touch controls on mobile
- Simple AI opponent
- Sound effects
- Score tracking
- Countdown after each point

## Controls

Desktop:
- Up Arrow: Move paddle up
- Down Arrow: Move paddle down
- Close window to quit

Mobile:
- Drag your finger vertically to move the paddle

## Requirements

- Python 3.10+
- pygame-ce

Install dependency:

```bash
pip install pygame-ce
````

## Running Locally

Run the game with:

```bash
python main.py
```

## Web Build (pygbag)

To build for web:

```bash
pip install pygbag
pygbag main.py
```

The generated web files will appear in the `build` directory.

## Project Structure

```
main.py
assets/
  Ball.png
  Paddle.png
  pong.ogg
  score.ogg
.github/workflows/
web/
build/
```
