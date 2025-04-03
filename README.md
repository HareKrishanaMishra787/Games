Python Turtle Games Collection
This repository contains three classic arcade-style games built using Python's Turtle graphics library:
<br>
🐍 Snake Game <br>
![snake game](https://github.com/user-attachments/assets/54fda2f9-4f30-4b14-b5f8-76b665737c18)

A classic Snake game where you control a snake that grows longer as it eats food. The game keeps track of your score and high score.
Features:

Snake movement controlled by arrow keys
Score tracking and persistent high score saved to file
Collision detection with walls and snake's own body
Growing snake mechanics when food is eaten

🏓 Pong Game <br>

![Screenshot (548)](https://github.com/user-attachments/assets/bb38f175-0b8c-4456-be82-40615917a92d)

A recreation of the classic Pong arcade game for two players.
Features:

Two-player controls (Right paddle: Up/Down arrows, Left paddle: W/S keys)
Score tracking for both players
Ball physics with increasing speed as the game progresses
Collision detection with paddles and walls

🐢 Turtle Crossing Game <br>
![turtle game](https://github.com/user-attachments/assets/e10e56f8-4523-4b8d-83ff-28b34a40e903)

A Frogger-style game where you control a turtle trying to cross a busy road.
Features:

Turtle controlled by the Up arrow key
Randomly generated cars with different colors
Increasing difficulty levels (cars move faster) as you progress
Game over when turtle collides with a car

How to Run the Games

Make sure you have Python installed on your system
Clone this repository
Navigate to the project directory
Run any of the games using Python:

bashCopypython main.py  # Run the Snake game
# or
python F:\...\main.py  # Run the Pong or Turtle Crossing game
Project Structure

Snake Game:

main.py - Main game loop and setup
snake.py - Snake class implementation
food.py - Food class implementation
scoreboard.py - Score tracking and display
data.txt - Stores the high score


Pong Game:

main.py - Main game loop and setup
padle.py - Paddle class implementation
ball.py - Ball class with movement and collision physics
score.py - Score tracking and display


Turtle Crossing Game:

main.py - Main game loop and setup
player.py - Player (turtle) class implementation
car_manager.py - Car generation and movement
scoreboard.py - Level tracking and display



Dependencies
The games use Python's built-in libraries:

turtle - For graphics and game objects
time - For game timing
random - For randomization of food/car placement

Screenshots
The repository includes screenshots of all three games in action.
Learning Objectives
These games demonstrate:

Object-oriented programming in Python
Game development fundamentals
Event handling and user input
Collision detection
File I/O for score persistence

License
Feel free to use, modify, and distribute this code for educational purposes.RetryClaude does not have the ability to run the code it generates yet.Claude can make mistakes. Please double-check responses. 3.7 Sonnet
