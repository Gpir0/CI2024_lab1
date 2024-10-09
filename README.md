# CI2024_lab1

To tackle the set covering problem, each set was given a score based on how many elememts it contained, with elements weighted according to their importance. The rarer (less frequent) an element was, the more important it was considered. Finally, these scores were empirically transformed into probabilities using the softmax function; the higher the score, the greater the probability of selecting the set.

To initialize the starting sets, a draw without replacement of sets was performed until a valid solution was obtained. The iterative method used both the previously defined probability-based selection and random selection (hill climbing). Simulated annealing was implemented.


The code was based on the basic code written in class. I exchanged ideas with classmate Vida Gallo (github.com/VidaGallo).
