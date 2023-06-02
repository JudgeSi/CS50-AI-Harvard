### Knowledge

knowledge is a concept of machine interpretable facts that a program can use to make decisions about problem.

### MinMax & knowledge

MinMax is the basic concept of an adverserial problem or game, where both players want to win. The concept of winning and loosing is encoded into a scoring problem, where the outcome of the game is associated with a numerical value. The numerical value can than be used to encode the ideas of winning and loosing, by having one player try to achive a minimal value and the other player trying to achieve a maximum value.

For the game of tic tac toe this means that all possible game board states need to be evaluated and given a value of 1 (winning max player) 0 draw or -1 (loosing min player). For tic tac to it might still be possible to calculate all possibilites, but for more complex games it is not relastic in terms of computational resources to evalute all possible states. Therefore the most important way to evaluate the effectiveness of an algortihm is to 'guess' the value of an non complete (or non
terminal) board state. If the algorithm is good at assigning a good probability of winning to an incomplete board state, it is only natural that he is more effective, since the algorithm would need to do less computing, comared to a complete algorithm that needs to evaluate all possible states of a board. 
