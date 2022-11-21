An HTML file containing Javascript script that animates Conway's Game Of Life as a grid of checkboxes.

# Conway's Game of Life

[Conway's Game of Life](https://en.wikipedia.org/wiki/Conway's_Game_of_Life) is a [cellular automaton](https://plato.stanford.edu/entries/cellular-automata/#:~:text=Cellular%20automata%20(henceforth%3A%20CA),a%20variety%20of%20scientific%20fields.) devised by the British mathematician John Horton Conway in 1970.\
The game universe is a two-dimensional grid of square cells, each of which is either dead or alive.\
With each new generation, cells interact with thier eight neighbours (horizontal, vertical, or diagonal) and:\
* Any live cell with fewer than two live neighbours dies.
* Any live cell with two or three live neighbours lives on to the next generation.
* Any live cell with more than three live neighbours dies.
* Any dead cell with exactly three live neighbours becomes a live cell.


# Get started 
Download or clone this repository and double-click ```game_of_life.html``` to run it with your default browser.\
Use the ```Next``` button to step through each generation, or the ```Auto``` button to watch it unfold. 

# Peek in
The code includes step-by-step comments to explain how things work.

# Play around
Manually change the configuration of checkboxes in your browser by clicking/unclicking.\
Play with ```const size = 20``` and ```const possibility = 0.2``` in the script to change random starting generation.

# Credits
This was coded as part of an exercise in Marijn Haverbeke's brilliant book [Eloquent Javascript](https://eloquentjavascript.net/)
