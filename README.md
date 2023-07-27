# PingPong Game

PingPong Game is a simple and engaging game created using HTML, CSS, and JavaScript DOM. Challenge yourself to play against the computer and score as many points as you can!

## Table of Contents

- [Getting Started](#getting-started)
  - [Installation](#installation)
- [How to Play](#how-to-play)
- [Game Rules](#game-rules)
- [Score and Maximum Score](#score-and-maximum-score)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/MayankSethi27/PingPong.git
   cd "ping pong"
   ```

2. Open `index.html` in your web browser.

3. Start playing the game and enjoy!

## How to Play

1. To control the paddle, use the mouse or keyboard (W and S keys).
2. The left paddle is controlled by you, and the right paddle is controlled by the computer.
3. The game starts with the ball moving towards the right side (computer's side). Your goal is to prevent the ball from hitting the right wall.
4. When the ball hits the right wall, the computer gains a point. When the ball hits the left wall (your side), you gain a point.
5. The game continues until one player reaches the winning score.

## Game Rules

- The ball bounces off the top and bottom walls, as well as the paddles.
- The computer-controlled paddle will try to track the ball and hit it back.
- The game will pause and display the winner once either player reaches the winning score (e.g., 10 points).

## Score and Maximum Score

- The current score is displayed during the game. It increments whenever a player successfully hits the ball back.
- The maximum score achieved in a single game is stored in local storage for reference across sessions.
- If this is your first time playing the game, you will be alerted to start the game.
- Otherwise, you will see the name of the player who achieved the highest score and their corresponding score.

## Contributing

Contributions are welcome! If you find any bugs or want to improve the game, feel free to open an issue or submit a pull request.

---

Thank you for playing the PingPong Game! Challenge yourself to beat the computer's paddle and achieve the highest score. Have fun and enjoy the game! If you have any questions or feedback, please don't hesitate to contact us. Happy gaming!
