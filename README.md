# Classic-Snake-Game

### Project Summary: Snake Game

This project is a classic Snake Game built using Python's `turtle` module. The game is played on a graphical window where the player controls a snake to eat food, grow longer, and avoid collisions with walls and itself. The game consists of four main components: the main game loop (`main.py`), the snake logic (`snake.py`), the food logic (`food.py`), and the scoreboard (`scoreboard.py`).

#### main.py
- **Purpose**: Initializes the game, handles game logic, and user input.
- **Key Functions**:
  - Sets up the game screen with a black background and a title "My Snake Game".
  - Creates instances of `Snake`, `Food`, and `Scoreboard`.
  - Listens for user inputs to control the snake's direction.
  - Contains the game loop which:
    - Updates the screen and moves the snake.
    - Detects collisions with food, walls, and the snake's own tail.
    - Ends the game when the snake collides with a wall or its tail.

#### snake.py
- **Purpose**: Defines the behavior and properties of the snake.
- **Key Functions**:
  - Initializes the snake with three segments.
  - Moves the snake forward and handles the addition of new segments when the snake eats food.
  - Changes the direction of the snake based on user input while ensuring it cannot move in the opposite direction directly.

#### food.py
- **Purpose**: Manages the food object that the snake eats to grow.
- **Key Functions**:
  - Initializes the food object with a small blue circle shape.
  - Randomly places the food at a new location on the screen when it is eaten by the snake.

#### scoreboard.py
- **Purpose**: Keeps track of and displays the player's score.
- **Key Functions**:
  - Initializes the scoreboard at the top of the screen and displays the score.
  - Updates the score when the snake eats food.
  - Displays "GAME OVER" message when the game ends.

### How to Run the Game
1. Ensure Python and the `turtle` module are installed on your system.
2. Run the `main.py` file.
3. Use the arrow keys to control the snake:
   - Up arrow: Move up
   - Down arrow: Move down
   - Left arrow: Move left
   - Right arrow: Move right
4. Try to eat the food to grow the snake and increase your score.
5. Avoid collisions with the walls and the snake's own tail to keep the game going.

### Key Features
- **User Input**: Control the snake using keyboard arrow keys.
- **Dynamic Food Placement**: Food appears at random locations each time it is eaten.
- **Score Tracking**: The score increases as the snake eats more food, and the current score is always displayed.
- **Game Over Detection**: The game ends when the snake collides with the wall or its own tail, with a "GAME OVER" message displayed.

This project demonstrates basic game development concepts using Python and can be further extended with additional features such as different levels, obstacles, or improved graphics.
