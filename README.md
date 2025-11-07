# Snake-Game🐍 Realistic Snake Game (HTML)

A modern, dark-themed implementation of the classic Snake arcade game, built using only client-side web technologies.

🕹️ How to Play

This game runs entirely in your web browser and requires no installation or external server.

    Save the Code: Copy all the code provided into a single file named snake.html.

    Open in Browser: Double-click the snake.html file to launch the game in Chrome, Firefox, or any modern web browser.

    Controls: Use the Arrow Keys (↑, ↓, ←, →) to change the snake's direction.

✨ Features

    Dark Theme: Visually appealing dark background with high-contrast elements.

    Canvas Implementation: Uses the HTML <canvas> element for fluid, real-time rendering of the game state.

    Collision Detection: Checks for two conditions to end the game:

        Hitting the walls of the game board.

        The snake's head hitting its own body (self-collision).

    Real-time Scoring: Tracks the score and displays a Game Over screen with the final score.

⚙️ Technical Details

Component	Purpose	Details
HTML (snake.html)	Structure	Defines the <canvas> element, score display, and the Game Over screen.
CSS (<style>)	Styling/Theme	Embedded within the HTML, responsible for the dark background (#1a1a1a) and game element colors.
JavaScript (<script>)	Logic	Manages the game loop, snake movement, food placement logic, and input handling (key events).
Grid Size	Configuration	Set to a 20×20 grid with a TILE_SIZE of 20 pixels.
