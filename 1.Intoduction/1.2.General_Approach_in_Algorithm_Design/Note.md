In a broad sense, many algorithms approach problems in the same way. Thus, it is often convenient to classify them based on the approach they employ. One reason to classify algorithms in this way is that often we can gain some insight about an algorithm if we understand its general approach. This section presents some common approaches.

Randomized algorithms.
    Randomized algorithms rely on the statisical properties of random numbers. One example of a randomized algorighm is quicksort.

Divide-and-conquer algorithms.
    Divide-and-conquer algorithms revolve around three steps: divide, conquer, and combine. In the divide step, we divide the data into smaller, more manageable pieces. In the conquer step, we process each division by performing some operation on it. In the combine step, we recombine the processed divisions. One example of a divide-and-conquer algorithm is merge sort.

Dynamic-programming solution.
    Dynamic-programming solutions are similar to divide-and-conquer methods in that both solve problems by breaking larger problems into subproblems whose results are later recombined. However, the approaches differ in how subproblems are related. In divide-and-conquer algorithms, each subproblem is independent of the others. Therefore, we solve each subproblem using recursion and combine its result with the results of other subproblems. In dynamic-programming solutions, subproblems are not independent of one another. In other words, subproblems may share subproblems. In problems like this, a dynamic-programming solution will do more work than necessary, as shared subproblems are solvedf more than once. Although it is an important technique used by many algorithms, none of the algorithms in this book use dynamic programming.

Greedy algorithms.
    Greedy algorithms make decisions that look best at the moment. In other words, they make decisions that are locally optimal in the hope that they will lead to globally optimal solutions. One example of greedy algorithm is Huffman coding, which is an algorithm for data compression.

Approximation algorithms.
    Approximation algorithms are algorithms that do not compute optimal solutions; instead, they compute solutions that are "good enough." Often we use approximation algorithms to solve problems that are computationally expensive but are too significant to give up on altogether. The traveling-salesman problem is one example of a problem usually solved using an approximation algorithm. A heuristic is a less than optimal strategy that we are willing to accept when an optimal strategy is not feasible.
