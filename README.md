# Ball Pit (Pygame)

This project is a simple physics-based simulation / mini game built with Python and Pygame.  
Balls of random sizes fall from the top of the screen and collide with each other and the screen boundaries.

After a certain number of balls have spawned, a special cube drops into the scene.  
All objects can be grabbed and thrown using the mouse.

---

## Features

- Gravity and bounce physics  
- Ball–ball and ball–cube collisions  
- Random sizes and spawn delays  
- Rotating sprites when images are available  
- Mouse drag, hold, and throw interaction  
- Press `R` to reset the simulation  

---

## Project Structure

- `game.py` — Main game file  
- `assets/` — Ball and cube images (`.png`)  

`cube.png` is used only for the cube.  
All other `.png` files are used randomly for balls.

### Requirements
- Python 3.8 or higher  
- Pygame  

### Install Pygame
```bash
pip install pygame

## How to Run

run game.py

### Extras

Press R to reset the ball pit

You can hold and drag the objects with LMB

