# CI2024_lab1

To tackle the set covering problem, each set was given a score based on how many nodes it contained, with nodes weighted according to their importance. The rarer (less frequent) a node was, the more important it was considered. Finally, these scores were empirically transformed into probabilities using the softmax function; the higher the score, the greater the probability of selecting the set.

To initialize the starting solution, a draw without replacement of the sets to be considered was performed until a valid solution was obtained. The iterative method used both the previously defined probability-based selection and random selection (hill climb). Simulated annealing was implemented.
