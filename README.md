# Chess Game

This is an online chess game built with Node.js, Socket.io, Express, and Chess.js. It allows two players to play chess in real-time with drag-and-drop functionality for the chess pieces. The game state is synchronized across all clients, ensuring that each player sees the same game board.

## Features

- **Real-Time Gameplay**: The game state is updated instantly for both players using Socket.io.
- **Drag-and-Drop Interface**: Players can move chess pieces by dragging them to the desired squares.
- **Board Flipping**: The board automatically flips for black pieces so that each player has a clear view of the game.
- **Player Roles**: The first player to join is assigned to play as white, while the second player plays as black.

## Technologies Used

- **Node.js**: Backend server to handle game logic and communication between clients.
- **Socket.io**: Real-time communication for game state synchronization between players.
- **Express**: Web framework to serve the frontend and handle HTTP requests.
- **Chess.js**: Chess game logic to manage moves, validations, and board state.
- **Tailwind CSS**: Styling for the chessboard layout and pieces.
- **EJS**: Templating engine to render the HTML dynamically.

## Installation

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

### Steps to Run Locally

 Clone this repository:

   ```bash
   git clone https://github.com/kush511/cheap_chess.git
   cd cheap_chess
   ```
Install the required dependencies:
npm install

Run the application:
npm start

Open your browser and navigate to http://localhost:3000 to start playing the game.


How to Play
When two players join the game, the first player will automatically be assigned to play as white, and the second player will play as black.

Players can move pieces by dragging them to valid squares on the board.

The board will automatically update for both players, ensuring real-time gameplay.

The game will end when a checkmate or stalemate condition is reached.
