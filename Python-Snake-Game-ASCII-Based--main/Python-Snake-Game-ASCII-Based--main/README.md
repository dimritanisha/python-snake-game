Python Snake Game (ASCII-Based)

A simplified version of the classic Snake game implemented in Python. This game uses an ASCII-based interface, making it lightweight and suitable for playing in a terminal or Google Colab.

Features:
    Interactive Gameplay: Control the snake using W, A, S, D keys.
    Dynamic Food Generation: Food appears at random positions on the grid.
    Grid-Based Movement: The snake moves and grows as it eats food.
    Game Over Scenarios: The game ends when the snake hits the grid boundary.

How to Play:
    Launch the Python script in a terminal or Google Colab.

Control the snake using the following keys:
    W: Move Up
    A: Move Left
    S: Move Down
    D: Move Right

The goal is to eat as much food as possible by moving the snake to the food's position.
The snake grows as it eats food. Avoid hitting the grid boundaries, or the game will end.

Game Rules:
    The snake starts at the top-left corner of the grid.
    Eating food causes the snake to grow and increases your score.
    The game ends if:
    The snake moves outside the grid boundaries.
    (Optional for further development) The snake collides with itself.

Requirements:  Python 3.x
No additional libraries are required, making it easy to run on any system.

How to Run:
    Copy the game code into a Python file or a Jupyter/Colab notebook.
    Run the script in your terminal or execute the cell in Colab.
    Follow the on-screen instructions to play.

Demo:
Below is an example of what the game might look like during play:


..........
O.........
.O........
..O....F..
..........


Customization
    Grid Size: Modify grid_size to change the game board dimensions.
    Food Behavior: Add new rules for food spawning or bonus points.
    Collision Rules: Implement self-collision detection for added difficulty.
    Future Enhancements
    Add score tracking and display.
Introduce different levels of difficulty with speed adjustments.
Implement a graphical interface using pygame.
