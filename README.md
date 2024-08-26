
## Chess-like Turn-Based Strategy Game


## Introduction
This project is a turn-based, chess-like strategy game where two players control teams of characters on a 5x5 grid. Each player commands three types of characters: Pawn, Hero1, and Hero2, each with unique movement rules. The game is implemented with a server-client architecture, using WebSockets for real-time communication and a web-based interface built with React.Made by Amit Pal, 21BCE10567

## Features
- **Turn-based Gameplay:** Players take turns to move their characters.
- **Three Character Types:** Each character type has unique movement and attack patterns.
- **WebSocket Integration:** Real-time communication between the server and the client.

## Project Structure
/Amit_Pal_21BCE10567
├── /client
│   ├── index.html
│   ├── styles.css
│   └── chess.js
├── /server
│   └── server.js
├── package.json
└── package-lock.json



## Technology used 

### Front-End 
ReactJS 

### Back-End
NodeJs


## Client Directory
- > `index.html` : Contains the HTML layout for the game board.
- > `styles.css`: Provides the styling for the game board and pieces.
- > `chess.js`: Implements the game logic and handles user interactions.

## Server Directory
- > `server.js`: Sets up an Express server and WebSocket communication for real-time game updates.

## Installation
### Install Server Dependencies 
> `npm install`

### Start the Server and this will too view the game

>`npm start`

## How to Play

Click on a piece to select it.

Click on a highlighted square to move the piece.

The turn indicator will update to show whose turn it is.

The game will notify you when a player wins.



## Dependencies

Express: Web server framework.

ws: WebSocket library for real-time communication.

## License
This project is licensed under the Apache License. See the LICENSE file for details.

## Acknowledgments
Thanks to HitWicket for the opportunity to showcase my skills and to present my intrest in the company.
Thanks to the open-source community for providing the tools and libraries used in this project.
