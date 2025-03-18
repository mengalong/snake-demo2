# Snake Game

## Overview
This is a simple Snake game implemented using HTML, CSS, and JavaScript. The player controls a snake that moves around the screen, eating food to grow longer. The game ends if the snake hits the walls or itself.

## Game Features
- Classic Snake gameplay
- Score tracking
- Speed increases as the snake grows
- Mobile support with touch controls
- Pause/Resume functionality

## Implementation Details

### Game Logic
The game follows these main steps:

1. **Initialization**: Sets up the game board, creates the initial snake, and places food at a random position.
2. **Game Loop**: Continuously updates the game state and redraws the canvas.
3. **Movement**: The snake moves in the current direction, and the player can change direction using arrow keys.
4. **Collision Detection**: Checks for collisions with walls, the snake's body, and food.
5. **Growth**: When the snake eats food, it grows longer and the score increases.

### Key Components

#### HTML Structure
- `index.html`: The main HTML file containing the game canvas and UI elements.

#### CSS Styling
- `style.css`: Handles the styling of the game, including the canvas, buttons, and layout.

#### JavaScript Logic
- `script.js`: Contains all the game logic, including:
  - Canvas setup and drawing functions
  - Snake movement and control
  - Food generation
  - Collision detection
  - Game state management
  - Touch controls for mobile devices

### Technical Concepts Used
- **Canvas API**: Used for drawing the game elements
- **SetInterval**: For the game loop implementation
- **Event Listeners**: For keyboard and touch controls
- **Array Manipulation**: For managing the snake's body segments

## How to Play
1. Click the "Start Game" button to begin
2. Use the arrow keys to control the snake's direction
3. Eat the red food to grow and increase your score
4. Avoid hitting the walls or the snake's own body
5. The game speeds up as your score increases

## Mobile Controls
On mobile devices, swipe in the direction you want the snake to move.

## Future Improvements
- Add difficulty levels
- Implement high score storage
- Add different types of food with special effects
- Create obstacles or maze-like levels

---

Enjoy the game! Feel free to modify and expand upon this implementation.