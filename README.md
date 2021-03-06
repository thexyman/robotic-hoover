# robotic-hoover
A simple game to clean a room full of dirt with a handy robotic hoover!

## Functionality 
* The game takes commands from input.txt and feeds it to script.js where the data is parsed to create a 2D game board (x and y coordinates where x = no. of columns and y = no. of rows). In input.txt:
   * The first line provides the room dimensions
   * The second line the starting position of the Hoover on the 2D game board
   * The preceeding lines up until the final line provide the dirt positions 
   * The final line provides the driving instructions (as cardinal directions where e.g. N and E mean "go north" and "go east" respectively) in caps.
* The purpose of the game is to:
   * add dirt to the 2D grid
   * then direct the hoover to clean up the dirt  
* The game has been designed according to OOP principles that uses class structure to organise the code 

## How to run program
- Clone this repository and cd robotic-hoover/src 
- run `node script.js`
- The results of the game will be printed to the terminal in the following format:\
`1 3`\
`1`
- Where the first line is the final position of the hoover
- The second line is the number of dirt patches cleaned
- The data in input.txt can be changed but please ensure it follows the format described above

### Reference:
- https://gist.github.com/DavidJSimpsonEsq/71dcf396a2303ad5edd08690289d016d
