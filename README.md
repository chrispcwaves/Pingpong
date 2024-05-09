 Pong Game 

 Overview:

This project is a simple implementation of the classic Pong game using Python's Turtle graphics library. It includes functionality for player-controlled paddles, a bouncing ball, scoring, and basic game physics.

Files:

- `main.py`: Contains the main game logic and setup.
- `paddle.py`: Defines the Paddle class for player control.
- `ball.py`: Defines the Ball class for ball movement and collision detection.
- `scoreboard.py`: Defines the Scoreboard class for tracking player scores.

 How to Play:

1. Run the `main.py` file.
2. Use the following controls:
   - Right Paddle (Player 1):
     - Move Up: Up Arrow Key
     - Move Down: Down Arrow Key
   - Left Paddle (Player 2):
     - Move Up: 'W' Key
     - Move Down: 'S' Key
3. Bounce the ball past the opponent's paddle to score points.
4. The game continues until one player reaches the winning score.

Features:

- **Player Paddles:** Control two paddles to hit the ball.
- **Bouncing Ball:** The ball bounces off walls and paddles.
- **Scoring:** Keep track of points with the Scoreboard.
- **Simple Graphics:** Uses basic shapes and colors for game elements.

Customization:

- Adjust the game window size by modifying the `width` and `height` parameters in `screen.setup()` in `main.py`.
- Customize the speed of the ball by changing the `move_speed` attribute in `ball.py`.
- Modify the winning score limit and other game settings in `main.py`.

