# Mario Bros–style Platformer in Python

A 2D arcade platformer inspired by the original *Mario Bros.*, written in Python with the [Pyxel](https://github.com/kitao/pyxel) retro game engine. Developed as a two-person university project.

<!-- Add a screenshot or GIF here, e.g. ![Gameplay](docs/gameplay.gif) -->

## Features

- Player movement with gravity, jumping and collision detection against floors and platforms
- Enemies (turtles, crabs and more) that move across the platforms
- A POW block, collectible coins, and a three-life system with game over
- Multiple levels: clearing one advances you to the next
- Object-oriented structure: one class per game entity (`classes/`), with all tuning values in `constants.py`

## How to Run

Requires Python 3.

```bash
pip install pyxel
python main.py
```

## Controls

| Key   | Action     |
|-------|------------|
| A / D | Move left / right |
| Space | Jump       |

## Project Structure

- `main.py`: entry point
- `board.py`: game loop, level setup, lives and spawning
- `classes/mario.py`: player
- `classes/NPCs/`: enemies and coins
- `classes/blocks/`: floors, pipes and the POW block
- `constants.py`: screen size, hitboxes, sprite coordinates and physics values
- `assets/sprites.pyxres`: sprite sheet (Pyxel resource file)

## Authors

Developed together with [@Saren75](https://github.com/Saren75).
