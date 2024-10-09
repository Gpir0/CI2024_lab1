# CI2024_lab1

To tackle the set covering problem, each set was given a score based on how many elememts it contained, with elements weighted according to their importance. The rarer (less frequent) an element was, the more important it was considered. Finally, these scores were empirically transformed into probabilities using the softmax function; the higher the score, the greater the probability of selecting the set.

To initialize the starting sets, a draw without replacement of sets was performed until a valid solution was obtained. The iterative method used both the previously defined probability-based selection and random selection (hill climbing). Simulated annealing was implemented.


I searched (using Copilot) which function is used in literature to transform scores into probabilities. The code was based on the basic code written in class. I exchanged ideas with classmate Vida Gallo (github.com/VidaGallo).




RESULTS (cost)

100  10  0.2   <br>
286.437    out_it=30   in_it=1000 

1000 100 0.2 <br>
10587.550     out_it=30   in_it=1000  

10000 100 0.2  <br>
117930.432     out_it=30   in_it=1000

100000 10000 0.1 <br>
1851363.949    out_it=30 in_it=1000

100000 10000 0.2 <br>
2034141.269    out_it=30 in_it=1000

100000 10000 0.3 <br>
2012269.240   out_it=30 in_it=1000
