# Flappy Golf

A golf-themed twist on the classic Flappy Bird game! Navigate your golf ball through obstacles made of golf clubs and achieve the highest score possible.

## Game Overview

In **Flappy Golf**, you control a golf ball that must fly through gaps between golf club obstacles. The game features simple one-button controls and increasingly challenging gameplay.

## Features

- **Golf-themed graphics**: Golf ball with dimple patterns and detailed golf club obstacles
- **Smooth physics**: Realistic gravity and jump mechanics
- **Score tracking**: Keep track of your current score and best score (saved in browser)
- **Responsive design**: Works on desktop and mobile devices
- **Beautiful UI**: Gradient backgrounds with animated clouds

## How to Play

1. **Start the game**: Click the "Start Game" button
2. **Control the ball**:
   - Click anywhere on the canvas, OR
   - Press the SPACEBAR
3. **Objective**: Navigate through the gaps between golf clubs without hitting them
4. **Scoring**: Each set of clubs you pass through adds 1 point to your score
5. **Game Over**: The game ends if you hit a club or touch the top/bottom of the screen

## Tech Stack

- **HTML5**: Game structure and canvas element
- **CSS3**: Styling and responsive design
- **JavaScript (Vanilla)**: Game logic, physics, and rendering
- **Canvas API**: 2D graphics rendering

## Project Structure

```
Rookie/
├── index.html          # Main HTML file with game canvas
├── css/
│   └── style.css      # Styling and layout
├── js/
│   └── game.js        # Game logic, physics, and rendering
└── README.md          # This file
```

## Running the Game

### Option 1: Open Locally
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start playing!

### Option 2: Serve with a Local Server
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## Game Mechanics

### Physics
- **Gravity**: 0.5 pixels per frame
- **Jump Velocity**: -8 pixels per frame
- **Club Speed**: 2 pixels per frame
- **Club Gap**: 160 pixels
- **Ball Radius**: 12 pixels

### Difficulty
- Clubs spawn every 120 frames (approximately 2 seconds)
- Gap positions are randomized for each club
- Constant horizontal speed creates increasing challenge as more clubs appear

## Browser Compatibility

This game works in all modern browsers that support:
- HTML5 Canvas
- ES6 JavaScript
- LocalStorage API

Tested on:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Future Enhancements

Potential features to add:
- Sound effects (club hits, scoring)
- Background music
- Different difficulty levels
- Power-ups (slow-mo, invincibility)
- Animated golf ball spin based on velocity
- Mobile touch controls optimization
- Leaderboard system
- Different golf-themed obstacles

## Credits

Created as a fun golf-themed variation of the classic Flappy Bird game.

## License

Feel free to use and modify this code for your own projects!
