# tetris-game
This is a multi-threaded Tetris game in Java that uses Swing to create the Graphical User Interface. I developed it for my final project in my Java Programming course at the University of Chicago in the Masters Program in Computer Science. This was my first major project in the program.

It utilizes a game engine originally used to power the game Asteroids. It functions like a typical Tetris game, in that a piece (tetromino) will gradually fall down from the top of the screen one at a time, and the goal is to fill up a complete line in the board's grid. There are several different shaped pieces: a square piece, J-shaped piece, a long piece, an L-shaped piece, a plus-sign shaped piece, an S-shaped piece, a T-shaped piece, a Z-shaped piece, and a bomb piece. You score 1200 points each time you fill up a line, at which time the line will clear from the grid. The bomb piece only comes up every once in a while, and it will have a bomb sound effect when it hits and clear the board. This scores you 1000 points. If you fill the board to the top, the game ends. There is a square at the top right corner that tells you what the next piece will be. The high score gets saved within one instance of the game (replaying as many times as you wish within 1 run of the program). As your score increases, the pieces will move down incrementally faster to make the game more difficult.

Keyboard controls are as follows:
M = Toggle Sound (Mute)
S = Start
P = Pause
Space Bar = Rotate the current piece
Arrow Keys = Move the current piece left, right or down
