# CI2024_lab3
## N-Puzzle

- A* search algorithm:
    - Misplaced tiles heuristic: `heuristic_simple`
    - Manhattan distance heuristic: `enhanced_manhattan_heristic` ( https://algorithmsinsight.wordpress.com/graph-theory-2/a-star-in-general/implementing-a-star-to-solve-n-puzzle/)
        - Linear conflicts: it is a pair of tiles that are in the same row or column and their goal positions are in the same row or column, but they are in the wrong order. For each linear conflict it adds two moves to the Manhattan distance.

- Results:
    - 3x3 puzzle:
        - quality: 19
        - cost: 493
        - time: 0.028s
    - 4x4 puzzle:
        - quality: 43
        - cost: 398_203
        - time: 61.871s


