This is a console-based implementation of the classic Pac-Man game in C. It's a simplified version, focusing on basic gameplay mechanics such as movement, score tracking, and collision detection.
The game contains certain elements as mentioned below:
Pacman or Cursor: The Cursor is the main element that is not static in the whole game
Walls: Walls are the same as real walls we can’t move surpassing them.
Food or Points: These are the elements that need to be collected and added to the main score.
Demons: These are the entities that need to be avoided in the game.
Functions which are used in the game are:
move(): It enables pacman to move in the game. Movement can be up, down, left and right.
draw(): Prints the game board on the console.
initialize(): It defines the board at the start of the game. Puts the walls around boundaries and inside the board, places demons at random places and places eatables at the rest of the places.
when you eat food number of Demon increased
