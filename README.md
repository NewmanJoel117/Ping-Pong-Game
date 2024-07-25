# Pong Game

Welcome to my Pong game project! This classic arcade game is built using Python and the Turtle graphics library.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Classes](#classes)
  - [Paddle](#paddle)
  - [Ball](#ball)
  - [Scoreboard](#scoreboard)
- [How to Play](#how-to-play)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is a simple implementation of the classic Pong game. The game is built using Python's Turtle graphics library. It includes two paddles, a ball, and a scoreboard. The players can control the paddles using the keyboard, and the objective is to prevent the ball from going past the paddle.

## Features

- Two-player gameplay
- Real-time ball movement
- Collision detection
- Score tracking

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-github-username/pong-game.git
   ```
2. Navigate to the project directory:
   ```bash
   cd pong-game
   ```
3. Ensure you have Python installed. This project requires Python 3.x.

## Usage

To start the game, run the following command in your terminal:
```bash
python pong_game.py
```

## Classes

### Paddle

The `Paddle` class represents the paddles used by the players to hit the ball.

- **Methods**:
  - `__init__(self, position)`: Initializes the paddle at the given position.
  - `go_up(self)`: Moves the paddle up.
  - `go_down(self)`: Moves the paddle down.

### Ball

The `Ball` class represents the ball used in the game.

- **Methods**:
  - `__init__(self)`: Initializes the ball.
  - `move(self)`: Moves the ball in the current direction.
  - `bounce_y(self)`: Reverses the ball's y-direction.
  - `bounce_x(self)`: Reverses the ball's x-direction and increases speed.
  - `reset_position(self)`: Resets the ball to the center and resets speed.

### Scoreboard

The `Scoreboard` class tracks and displays the scores of both players.

- **Methods**:
  - `__init__(self)`: Initializes the scoreboard.
  - `update_scoreboard(self)`: Updates the score display.
  - `l_point(self)`: Increments the left player's score.
  - `r_point(self)`: Increments the right player's score.

## How to Play

- Player 1 controls the left paddle using the 'W' (up) and 'S' (down) keys.
- Player 2 controls the right paddle using the 'Up' and 'Down' arrow keys.
- The goal is to hit the ball with your paddle and prevent it from going past you. Each time a player misses the ball, the other player scores a point.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

Developed by myself 'Onyedika Joel Chukwuka'. If you have any questions or feedback, feel free to reach out to me.

Enjoy the game!
