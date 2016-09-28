# Tetris Game
This is a multi-threaded Tetris game in Java that uses Swing to create the Graphical User Interface.  I developed it for my final project in my Java Programming course at the University of Chicago in the Masters Program in Computer Science. This was my first major project in the program.

## About
- Uses the model-view-controller (MVC) pattern to divide the three parts of the application.
- Utilizes a base code game engine originally used to power the game Asteroids, including a Movable interface, controller, game frame and panel etc.
- Applies concepts such as object-oriented design, polymorphism, inheritance and encapsulation.

## How To Play 
It functions like a typical Tetris game, in that a piece (tetromino) gradually falls down from the top of the screen (one at a time) and the player controls the position in which it falls. Your goal is to fill up complete lines in the board's grid. You score points each time you fill up 1 line, at which time the line will clear from the grid. There is a bonus "bomb" piece that clears the board.

## Pieces/Tetrominoes
- Square Piece
- J-Shaped Piece
- Long Piece
- L-Shaped Piece
- Plus-Sign-Shaped Piece
- S-Shaped Piece
- T-Shaped Piece
- Z-Shaped Piece
- Bomb Piece (only comes up every so often: clears the board and has a bomb sound effect)

## Keyboard Controls
- S = Start
- P = Pause
- M = Toggle Sound (Mute)
- Space Bar = Rotates current piece
- Arrow Keys (Left, Right, Down) = Moves current piece left, right or more quickly down the screen

## Scoring
- Complete 1 Line: 1200 points
- Bomb Piece: 1000 points
Note: The High Score gets saved within 1 run of the program, with multiple re-plays using the same window. If you quit out and re-run the application, the high score does not get saved. As your score increases, the pieces will move down incrementally faster to make the game more difficult.

## Setup
1. Import the code into an IDE (I used IntelliJ).
2. Open the controller and run Game.java.
3. Follow instructions on the screen that comes up.
