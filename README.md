# Conways Game of Life

Conway's Game of Life is a cellular automaton devised by the British mathematician John Horton Conway in 1970. It is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input. The game is played on a grid of cells, where each cell can be either alive or dead.

### Rules:
The universe of the Game of Life is an infinite, two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, live or dead (or populated and unpopulated, respectively). Every cell interacts with its eight neighbors, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:

1- Underpopulation: Any live cell with fewer than two live neighbors dies.

2- Survival: Any live cell with two or three live neighbors survives to the next generation.

3- Overpopulation: Any live cell with more than three live neighbors dies.

4- Reproduction: Any dead cell with exactly three live neighbors becomes a live cell.

These rules create fascinating patterns and behaviors, making the Game of Life a classic example of emergent complexity.

### Usage:

Conway's Game of Life has various applications and uses:

1- Simulation: It's often used as a simulation tool in biology, ecology, and other fields to model population dynamics and spatial interactions.

2- Algorithmic Exploration: The Game of Life provides an interesting platform for exploring and developing algorithms, especially for tasks like pattern recognition and optimization.

3 - Visualizations: Many artists and designers use the Game of Life to create visually stunning patterns and animations.

4- Educational Tool: It serves as an educational tool for teaching concepts like cellular automata, emergent behavior, and algorithmic thinking.

### Examples:

Here are a few examples of patterns that can emerge in Conway's Game of Life:

1- Still Life: Patterns that remain unchanged throughout generations.

![image](https://github.com/mahyar-e/Conways-Game-of-Life/assets/78594407/804aea99-d772-41fc-8fe4-a41fe3cd4dc4)


2- Oscillators: Patterns that oscillate between two or more states.

![oscillator](https://github.com/mahyar-e/Conways-Game-of-Life/assets/78594407/722ef161-0c40-41cf-88a9-0af51c9b978f)


3- Spaceships: Patterns that move across the grid in a consistent direction.

![mwss](https://github.com/mahyar-e/Conways-Game-of-Life/assets/78594407/9d5ef2eb-2d3a-4475-bc10-f584d8b7fdb4)

4- Glider Gun: A pattern that continuously produces gliders, which are spaceships moving diagonally. (You can find the codes in the jupyter notebook.)

![gosper_glider_gun](https://github.com/mahyar-e/Conways-Game-of-Life/assets/78594407/c1ac92ac-33aa-41b4-815a-29d179e65837)


### Getting started:
In order to begin the simulation you need to have these libraries installed:

```NumPy```, ```Matplotlib``` and ```PIL```

You can easily install the libraries via the following command:

```pip install [name of the library]```

You can also manipulate the rules of the game to see what will happen if you chanhe the rules of the game. A few examples are included in the file, like game of life considering the second neighbor, dead cells have a chance to come to life and etc.

Feel free to share your opinions regarding this project.
