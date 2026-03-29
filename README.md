# Snake-Game
It is basically a game developed by me in python as part of my college project. It uses import functions like random,turtle and time. The game is simply a snake which can be controlled by WASD keys which should eat food to increase its length. Each food gives +10 health. The snake would die if its head hits its tail or it goes out of boundary.
# FEATURES 
Smooth snake movement controlled by WASD keys Food appears at random positions Score increases as the snake eats food Snake grows after each food item Game Over on collision with borders or with itself Clean and beginner-friendly code

# MODULES USED MODULE PURPOSE TURTLE 
For graphics, snake movement, drawing, and screen handling RANDOM To generate random food positions TIME To manage game speed and delays

# CONTROLS 
W Move Up 
A Move Left
S Move Down 
D Move Right

# GAME ELEMENTS 
Snake Head : Moves continuously in the direction set by the player Food : Appears randomly, eaten by snake to gain score Scoreboard : Displays current score and high score(+10 for each food) Border : Collision ends the game

# GAME LOGIC 
The snake moves in steps using turtle.forward() A list stores body segments, and each segment follows the previous one Random coordinates generate food positions Collision checks include Hitting the wall Hitting its own tail

# IMPLEMENTATION DETAILS 
The core functionality is structured around the turtle module:

**Game Screen**: Set up using turtle.Screen()**.Game Loop**: An infinite while True: loop that updates the screen and checks game logic. Snake Segments & Food: Created using turtle.Turtle() objects. **Key Bindings:** Handled by screen.onkey() to map arrow keys to snake direction functions. Movement: Achieved by continuously moving the snake's head and having the body segments follow the head's position.

# GAMEPLAY

The game starts with a small snake.
Use the arrow keys to direct the snake towards the red food dot.
Each time the snake eats the food, it grows longer, and your score increases.
The game ends if the snake runs into the border or collides with its own body.
Press 'R' or close and reopen the window to restart the game.

# CONCLUSION 
This Snake Game is a great beginner project to understand Python graphics, loops, and game logic.
