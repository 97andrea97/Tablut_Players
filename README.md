# Tablut_Players
The state is represented by a 9x9 matrix. Each cell contains a number which is the encoding of a specific combination of tile_type & checker_type.
Tablut is an asymmetric game, the black and white checkers have different aims and different possible actions.
The functions "action_.." define the possible moves of the correspondent checkers. 
The functions "heuristic_.." define the state evaluation on which the minmax algorithm works. 
The function "result" computes the new state predicting the application of an action.
We define some hyperparameters: the points attributed to some situations like "king in danger","kill an enemy checker" etc.
By tuning the hyperparameters the player strategy can be influenced (more difensive, more aggressive, more tricky etc).
