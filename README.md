# A-Knights-Travails

- We all know of knights in a chess board. We also know of the 
unique movement of the knight (an “L-shape” to be brief). 

- We aim to show the shortest possible path that a knight can take to 
take down a target chess piece, in a N x N chessboard. 

- We also give the player the choice to block certain squares with a 
friendly-pawn, that the knight may choose another path.

Searching Algorithm used : **BFS**

### Approach 
- The initial approach to this problem would be the finding the 
shortest path in an unweighted graph. 

- We take each square in a chess board as a graph node, and the board 
itself to be the graph. 

- We aim to use a special form of Breadth First Search (BFS), as we are 
using an unweighted graph here, and search all the possible paths that 
the knight can take. Then the algorithm chooses the shortest path. 

- If the player chooses to block the path of the knight with a friendly 
piece, the knight then removes the particular node from the graph and 
resumes BFS.

For more information, go [here](https://github.com/Mufaddal24/A-Knight-s-Travails/blob/main/A%20study%20of%20Knight's%20Travails%20-%20DSA%20Project.pdf).


