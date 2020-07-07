# Minesweeper-
Project made for a work in university

Description:
Minesweeper is a popular single player computer game. It was invented by Phil Spencer
in 1989 and aims to reveal a minefield without any being detonated. This game has
rewritten for the most diverse platforms, the most popular version being the one that came
natively in editions prior to Windows 10.

GAME RULES:
The playing area consists of a rectangular square field. Each square can be revealed by clicking on
him, and if the clicked square contains a mine, then the game is over. If, on the other hand, the square does not contain a
mine, one of two things can happen:
• A number appears, indicating the number of adjacent squares that contain mines;
• No number appears, indicating that there is no mine adjacent to the chosen square;
The game is won when all the squares that have no mines are revealed.

GAME PROGRAMMING REQUIREMENTS:
Before the game starts:
1º The number of lines, columns and the number of mines in the game (constant) must be defined in the code. The logic
should work even with changing values for a new run
It must be ensured that the map has at least two pumps and a number of rows and columns
larger than one, so the smallest map possible will have two rows, two columns and 2 bombs.

2º The bombs must be placed at random positions on the map. Tip: use the rand () function to choose
a random row and column on the map and remember to prevent a bomb from being placed in a
position that there is already another pump.

3º Whenever you place a bomb, use a repetition loop to add the number of bombs in one
adjacent positions, this will ensure that the map indicates the number of nearby mines correctly.

Now we can start the game:
4º Before each move, the map must be displayed, only with all the positions already revealed by the player.

5º The game must ensure that the player chooses a valid coordinate. It is recommended that these coordinates are
displayed along with the map.

6º The game must end when a mine is selected or when all free positions on the map are
revealed.

7º The game must indicate whether the player won or lost and the number of valid plays made by him.



