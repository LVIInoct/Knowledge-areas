# Knowledge-areas
A list of the areas I've studied and taken private notes on. Subjects not listed are ones I haven't covered yet.
Topics follow the IEEE Computer Society curriculum structure and personal studies. This note is unfinished, as I am still studying through new subjects to this day.
My current main focus is Algorithms.

# Algorithms
**Data Structures and Algorithms**
1. Abstract Data Type and dictionary operations (insert, delete, find)
2. Arrays - a. Numeric, non-numeric, character strings. b. Vector vs matrix
3. Structs/Tuples and Objects (OOP)
4. Linked lists - a. Single vs Double and Linear vs Circular
5. Stacks
6. Queues and deques - a. Heap-based priority queue
7. Hash tables/maps - a. Collision resolution and complexity (e.g. probing, chaining, rehash)
8. Graphs (e.g., [un]directed, [a]cyclic, [un]connected, and [un]weighted) - a. Adjacency list vs matrix
9. Trees - a. Binary and search trees. b. balanced (e.g. AVL, Red-Black, Heap)
10. Sets
11. Search algorithms - a. O(n) complexity (e.g., linear/sequential array/list search). b. O(log₂ n) complexity (e.g., binary search). c. O(log_b n) complexity (e.g., uninformed depth/breadth-first tree search)
12. Sorting algorithms (e.g., stable, unstable) - a. O(n²) complexity (e.g., insertion, selection). b. O(n log n) complexity (e.g., quicksort, merge, timsort, heapsort). c. Pseudo O(n) complexity (e.g., bucket, counting, radix)
13. Graph algorithms - a. Shortest path (e.g., Dijkstra's, Floyd's). b. Minimal spanning tree (e.g., Prim's, Kruskal's). c. Transitive closure (e.g., Warshall's). d. Topological sort
14. Matching - a. Longest common subsequence matching. b. Regular expression matching

**Algorithmic Strategies**
1. Paradigms - a. Brute-Force (e.g., linear search, selection sort, knapsack). b. Decrease-and-Conquer - i. By a Constant (e.g., insertion sort, topological sort). ii. By a Constant Factor (e.g., binary search). c. Divide-and-Conquer (e.g., binary search, quicksort, mergesort). d. Greedy (e.g., Dijkstra's, Kruskal's, Knapsack). e. Transform-and-Conquer - i. Problem reduction (e.g., least-common-multiple). ii. Dynamic programming (e.g., Floyd's). f. Space vs time tradeoffs (e.g., hashing)
2. Iteration vs recursion (e.g., factorial, tree search)

**Complexity**
1. Complexity Analysis Framework - a. Best, average, and worst-case performance of an algorithm. b. Empirical and relative (Order of Growth) measurements. c. Input size and primitive operations. d. Time and space efficiency
2. Asymptotic complexity analysis (average and worst-case bounds) - a. Big-O, Big-Omega, and Big-Theta formal notations. b. Foundational Complexity Classes and Representative Examples/Problems - i. O(1) Constant (e.g., array access). ii. O(log₂ n) Logarithmic (e.g., binary search). iii. O(n) Linear (e.g., linear search). iv. O(n log₂ n) Log Linear (e.g., mergesort). v. O(n²) Quadratic (e.g., selection sort). vi. O(nᶜ) Polynomial. vii. O(2ⁿ) Exponential (e.g., Knapsack, Satisfiability (SAT))
3. Tractability and intractability - a. P, NP, and NP-Complete Complexity Classes. b. NP-Complete Problems (e.g., SAT, Knapsack, TSP)
4. Little-o
5. Formal recursive analysis
6. Amortized analysis
7. Turing Machine-based models of complexity - a. Time complexity - i. P, NP, NP-C, and EXP classes. b. Space Complexity - i. NSpace and PSpace. ii. Savitch's theorem

**Computational Models and Formal Languages**
1. Formal automata - a. Finite State. b. Pushdown. c. Linear Bounded. d. Turing Machine
2. Formal languages, grammars and Chomsky Hierarchy - a. Regular (Type-3) - i. Regular Expressions. b. Context-Free (Type-2). c. Context-Sensitive (Type-1). d. Recursively Enumerable (Type-0)
3. Relations among formal automata, languages, and grammars
4. Decidability, (un)computability, and halting - a. Arithmetization and diagonalization
5. The Church-Turing thesis
6. Algorithmic correctness - a. Invariants (e.g., in iteration, recursion, tree search)
7. Deterministic and nondeterministic automata
8. Proofs of language limitations - a. Finite state automata (regular languages). b. Pushdown automata (context-free languages)
9. Reducibility and reductions
10. Equivalent models of algorithmic computation - a. Turing Machines and Variations (e.g., multi-tape, non-deterministic). b. Lambda Calculus


# Software Development Fundamentals
**Fundamental Programming Concepts and Practices**
1. Basic concepts such as variables, primitive data types, expressions, and their evaluation
2. Basic constructs such as assignment statements, conditional and iterative statements, basic I/O
3. Modularity: functions, methods and classes, parameter passing, scope, abstraction, encapsulation
4. Structured data types: arrays, lists, dictionaries, sets, tuples, and when to use them
5. Recursion
6. Dealing with runtime errors in programs (e.g., exception handling).
7. Basic concepts of programming errors, testing, and debugging
8. Documenting/commenting code at the program and module level.

**Fundamental Data Structures**
1. Standard abstract data types such as lists, stacks, queues, sets, and maps/dictionaries, including operations on them
2. Selecting and using appropriate data structures
3. Performance implications of choice of data structure(s)
4. Strings and string processing

**Algorithms**
1. Concept of algorithm and notion of algorithm efficiency
2. Some common algorithms (e.g., sorting, searching, tree traversal, graph traversal)
3. Impact of algorithms on time-space efficiency of programs

**Software Development Practices**
1. Basic testing, including test case design
2. Use of a general-purpose IDE, including its debugger
3. Programming style that improves readability
4. Specifying functionality of a module in a natural language
