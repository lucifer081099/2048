# 2048
A pygame implementation of the popular single-player puzzle game, 2048, 
designed by [Saurabh Sinha](https://github.com/lucifer081099).

## Getting Started
1. Get Python 3.x and clone this repository
2. Get [pip](https://www.makeuseof.com/tag/install-pip-for-python/), then install pygame:\
    ```$ pip install pygame```

3. Run the game:\
    ```$ python main.py```
    
OR

1. Get Python 3.x 
2. Download the whole code and save it to some folder on your computer.
3. Open command prompt and run the command ```$ pip install pygame``` to install the Pygame module.
4. Go the directory where you have save the file.
5. Now run the command python main.py

    
## Moves
1. 2048 is played on a gray 4×4 grid (Default), with numbered tiles that slide when a player moves them using the **four arrow keys**.
2. If you want to change the configuration to YxY, then put the value of Y in grid_dimension file and save it.
3. Join the numbers and get to **2048** to win!

## Game Rules
1. Every turn, a new tile will randomly appear in an empty spot on the board with a value of either 2 or 4.
2. Tiles slide as far as possible in the chosen direction until they are stopped by either another tile or the edge of the grid. 
3. If two tiles of the same number collide while moving, they will merge into a tile with the total value of the two tiles that collided.
4. The resulting tile cannot merge with another tile again in the same move. 
5. If a move causes three consecutive tiles of the same value to slide together, only the two tiles farthest along the direction of motion will combine. 
6. If all four spaces in a row or column are filled with tiles of the same value, a move parallel to that row/column will combine the first two and last two.
7. Score will be calculated when two same number tiles collide with each other, for example if current score is 20 and two 4 number tiles collide with each other, then the score will become 20+4+4=28.
