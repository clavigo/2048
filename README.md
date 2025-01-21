# 2048 Game
This project is an implementation of the popular 2048 game, developed using HTML, CSS, and JavaScript. The focus of the project is on manipulating the DOM to update the game board, display the score, and handle user interactions.

# Technologies Used:
1. **HTML**: Provides the basic structure for the page and game board.
2. **CSS** and **Sass**: Adds styling, including gradient colors, tile positioning, and animations.
3. **JavaScript**:
- Generates the game board and initial tiles.
- Handles DOM manipulation to reflect tile movement and merging.
- Implements the logic to detect game-over conditions.
4. **npm** – for dependency management and automating development processes.

# Features:
1. Gameplay:
- Players move tiles using arrow keys.
- Tiles with the same numbers merge upon collision, forming higher values.
- The game ends when no more moves are available.

2. Dynamic Updates:
- The 4x4 board is created as a table using HTML.
- All tile changes (generation, movement, merging) are handled via JavaScript, dynamically updating DOM elements.

3. Styling:
- CSS is used to create an appealing design for the tiles, with animations for movement and color changes based on tile values.

4. Game Mechanics:
- The game logic is implemented in pure JavaScript.
- Arrow key events are used for player control.
- New tiles are generated after each move.

# Code Style Tools:
- **ESLint** – for JavaScript code quality checks.
- **Stylelint** – for linting styles (CSS/Sass).
- **Prettier** – for automatic code formatting, ensuring consistent style.
- **Linthtml** – for checking HTML files for errors and compliance with standards.

# Demo link
[DEMO LINK](https://clavigo.github.io/2048/)

# How to run project locally
- **Clone** the repository
- **Install** all dependencies (npm install)
- **Start** the project (npm start)
