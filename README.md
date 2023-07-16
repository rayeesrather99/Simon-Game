# Simon-Game
This is a simple implementation of the Simon game using HTML, CSS, and JavaScript. Simon is a memory game where players have to remember and repeat a sequence of colors.

# Game-Mechanics
The game starts when the user presses any key on the keyboard.
A random color is generated and added to the gamePattern array.
The corresponding button for the generated color flashes briefly and plays a sound.
The player then clicks on the buttons to repeat the sequence.
If the player clicks the correct sequence, the game progresses to the next level.
If the player clicks the wrong sequence, the game ends, and the player can restart by pressing any key.
The game keeps track of the current level.

# Variables
buttonColours: An array of colors available in the game (red, blue, green, yellow).
gamePattern: An array that stores the randomly generated sequence of colors.
userClickedPattern: An array that stores the sequence of colors clicked by the player.
started: A boolean variable to check if the game has started.
level: A variable to keep track of the current level.

# Creator
https://www.rayees.co
