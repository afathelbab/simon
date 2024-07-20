
# Simon Game

This project is a web-based implementation of the classic Simon game. The player has to remember and reproduce a sequence of colors that the game presents. Each round, the sequence gets longer, and the game ends when the player makes a mistake.

## Features

- A sequence of colors that the player must remember and reproduce.
- Each round adds a new color to the sequence.
- The game displays the current level and provides feedback on mistakes.
- The game uses animations and sounds to enhance the user experience.

## Table of Contents

- [Getting Started](#getting-started)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Functionality](#functionality)
- [Credits](#credits)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You need a web browser to run this project. No additional software or libraries are required.

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/simon-game.git
   ```
2. Navigate to the project directory:
   ```sh
   cd simon-game
   ```
3. Open `index.html` in your web browser to start the game.

## Usage

1. **Start the Game**: Press any key to start the game.
2. **Play the Game**: Follow the sequence of colors that the game presents. Click on the colored buttons to reproduce the sequence.
3. **Game Over**: If you make a mistake, the game will display "Game Over" and you can restart by pressing any key.

## File Structure

```
/project-root
├── /sounds
│   ├── blue.mp3
│   ├── green.mp3
│   ├── red.mp3
│   └── yellow.mp3
├── styles.css
├── game.js
├── index.html
└── README.md
```

## Functionality

### HTML

- **index.html**: The main HTML file that includes the structure of the page and links to the CSS and JavaScript files.

### CSS

- **styles.css**: Contains styles for the page layout, fonts, colors, and other visual aspects.

### JavaScript

- **game.js**: Manages the game logic, including generating the color sequence, handling user input, and providing feedback.

### Key Functions in `game.js`

- **`nextSequence()`**: Generates the next color in the sequence and updates the game state.
- **`checkAnswer(currentLevel)`**: Checks the user's input against the game sequence.
- **`animatePress(currentColor)`**: Animates the button press.
- **`playSound(name)`**: Plays the corresponding sound for the given color.
- **`startOver()`**: Resets the game state to start a new game.

## Credits

Developed by: Ahmed Fathelbab. Feel free to use and modify the code as needed. Contributions are welcome!
