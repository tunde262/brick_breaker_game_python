# Brick Breaker Game

A simple Brick Breaker game implemented using **Python** and **Pygame**. The game includes a paddle, a bouncing ball, and destructible bricks. Players can control the paddle to keep the ball in play and break all the bricks to win. 

The program also includes optional web hosting support using **asyncio** & **pygbag**.

![thumbnail](https://github.com/tunde262/brick_breaker_game_python/blob/main/assets/thumbnail.png?raw=true)

## Features
- **Dynamic Gameplay:** Paddle and ball mechanics for an engaging experience.
- **Multiple Brick Layers:** Bricks have varying strength levels based on their row.
- **Victory & Game Over Conditions:** Win by destroying all bricks or lose if the ball falls below the paddle.
- **Optional Web Hosting** on the web using asyncio compatibility with the Pygbag library..

---

## Requirements

- Python 3.8+, recommended for the following reasons:
  1. **Enhanced `asyncio` Support**: The project uses `asyncio.run()` for the optional web-hosting feature, which simplifies asynchronous execution.
  2. **Compatibility with Pygbag**: Pygbag, used for web hosting, requires Python 3.8+.
- Pygame (install via `pip install pygame`)
- (Optional) Pygbag for web hosting

## Installation

1. **Clone the Repository**:
   
   ```bash
   git clone https://github.com/tunde262/brick_breaker_game_python.git
   cd brick_breaker_game_python
   ```
   
3. **Install Dependencies**: Ensure you have Python 3.8+ installed. Then, install the required libraries:
   
   ```bash
   pip install pygame
   ```

4. **Run the Game**:
   
   ```bash
   python main.py
   ```

---

## Web Hosting (Optional)

This project supports optional web hosting using `asyncio` and the **Pygbag** library.

1. **Install the Pygbag library**:
   ```bash
   pip install pygbag
   ```
   
2. **Compile and host the game**:
   ```bash
   pygbag main.py
   ```

3. Follow the output instructions to serve the game in a browser.

## How to Play

- Use the arrow keys to move the paddle.
- Prevent the ball from falling below the paddle.
- Destroy all the bricks to win.
- The screen updates in real time, maintaining a 60 FPS frame rate for smooth play.

## Game Controls

- `Click anywhere` : Start the game
- `→` - Move Right
- `←` - Move Left

---

## Future Enhancements
- Add power-ups (e.g., wider paddle, faster ball).
- Implement scoring and a high-score tracker.
- Introduce sound effects and background music.
- Mobile-friendly version with touch controls.
- Add on-screen instructions.

---

### Author
*Tunde Adepitan*  
GitHub: [tunde262](https://github.com/tunde262)  
Feel free to connect and give me feedback!
