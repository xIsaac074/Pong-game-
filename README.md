# 🎮 Pong Game

A classic Pong game implementation using HTML5, CSS3, and JavaScript. Play against a computer AI opponent in this timeless arcade game.

## Features

✨ **Game Features:**
- ⌨️ Dual control system (Mouse & Keyboard)
- 🤖 Intelligent computer AI opponent
- 🎯 Collision detection (paddles & walls)
- 📊 Real-time scoreboard
- 🏆 Win condition (first to 11 points)
- 🎨 Modern UI with animations
- 📱 Responsive design
- ⚡ Smooth ball physics

## How to Play

1. Open `index.html` in your web browser
2. Control the left paddle (green) with either:
   - **Mouse**: Move your mouse up and down
   - **Keyboard**: Press Arrow Up/Down keys
3. The computer controls the right paddle (red)
4. First player to score 11 points wins!
5. Use the "Reset Game" button to start a new game

## Controls

| Control | Action |
|---------|--------|
| Mouse Movement | Move paddle up/down |
| Arrow Up | Move paddle up |
| Arrow Down | Move paddle down |
| Reset Button | Start new game |

## Game Rules

- Ball bounces off the top and bottom walls
- Ball bounces off paddles with angle variation based on collision point
- Ball speed increases slightly with each paddle hit
- Score increases when opponent misses the ball
- Game ends when a player reaches 11 points

## Technical Details

### Files
- `index.html` - Complete game implementation (HTML, CSS, JavaScript)

### Key Components
- **Canvas API** - For rendering game graphics
- **RequestAnimationFrame** - For smooth 60 FPS gameplay
- **Event Listeners** - For mouse and keyboard input
- **Collision Detection** - Rectangular and circular collision algorithms
- **AI Algorithm** - Predictive AI that adjusts difficulty based on ball speed

### Game Objects
- **Player Paddle** - Left side, controlled by user
- **Computer Paddle** - Right side, controlled by AI
- **Ball** - Center court, bounces around
- **Score** - Tracked for both players

## Browser Compatibility

Works on all modern browsers that support:
- HTML5 Canvas
- JavaScript ES6
- CSS3 Flexbox

## Installation

1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. Start playing!

## Customization

You can easily modify the game by changing these constants in the JavaScript:

```javascript
const PADDLE_HEIGHT = 80;      // Change paddle size
const BALL_RADIUS = 8;         // Change ball size
const WIN_SCORE = 11;          // Change winning score
computer.speed = 5;            // Change AI difficulty
