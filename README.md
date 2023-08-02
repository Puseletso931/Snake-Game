#Snake-Game

The game consists of snakes, apples, and zombies, each with specific rules:

Snakes:

Move in one of the four cardinal directions at one square per timestep.
Die if they collide with the grid's sides, a non-empty, or non-apple square.
Colliding with another snake's body results in the latter getting a kill.
Head-on collisions between two snakes result in both snakes being killed.
Dead snakes are respawned at a random location after missing one timestep.
Crashed snakes are removed from the board for the round.
Zombies:

Move at half the speed of normal snakes, one square every two timesteps.
Move toward the head of the nearest snake, avoiding the apple.
Colliding with a zombie results in the snake's death.
There are six zombies on the board.
Apples:

Appear at a random location at the beginning of the game and respawn after being eaten.
Eating an apple causes a snake to grow by having its tail remain in its current position.
If multiple snakes eat the same apple simultaneously, both snakes are killed, and the apple respawns at a new location.
The apple respawns if it hasn't been eaten within a certain number of moves.
Players must control their snakes to eat apples and avoid zombies while competing with other snakes to survive and grow. The game continues until all but one snake is eliminated.
