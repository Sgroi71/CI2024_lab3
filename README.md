# CI2024_lab2

- Greedy algorithm:
    - The greedy algorithm is a simple algorithm that builds up a solution piece by piece, always choosing the next piece that offers the most immediate benefit. This algorithm is not always the best solution, but it is a good heuristic. In this case, the greedy algorithm at each step chooses the nearest city that has not been visited yet. 
- Simulated Annealing:
    - Starts with the solution found in the greedy algorithm and then tries to improve it by making small changes. The algorithm accepts worse solutions with a certain propability, which allows it to escape local optima. The probability of accepting a worse solution decreases as the algorithm progresses.
    - Inversion mutation:
    The inversion mutation is a mutation operator that selects two random positions in the solution and inverts the order of the cities between them. This operator is used in the simulated annealing algorithm to make small changes to the solution minimazing changes in edges.
- Evolutionary algorithm:
    - It starts with a population made by scramble mutation of the greedy solution. 
    - It is used hypermodern GA flow: with a certain probability select the genetic operator (mutation or crossover) and then apply it to the population.
    - parents selection: the parents are selected by tournament selection, which selects a random subset of the population and then selects the best solution in the subset.
    - Inversion mutation:
    - Inver Over Crossover:
        - One genes (gene1) is selected randomly from the first parent
        - an edge containing the gene1 is selected from the second parent      
        - combine the child preserving the the edges of the first and the edge selected from the second parent
    - steady state: the new population is created by replacing the worst solutions in the population with the new solutions. 
