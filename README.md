# search_algorithm_optimization
# Breadth First Search (BFS) and Depth First Search (DFS)

## Description

This project demonstrates the implementation of:

1. Breadth First Search (BFS)
2. Depth First Search (DFS)

using Python programming.

The program searches for a path from an initial node to a goal node in a graph and prints the search path.

---

# Graph Used

```text
        A
      /   \
     B     C
    / \   / \
   D   E F   G
        |
        H
```

---

# Files Included

- search_algorithms.py

---

# Breadth First Search (BFS)

## Features

- Uses Queue (FIFO)
- Explores nodes level by level
- Finds shortest path in an unweighted graph

---

# Depth First Search (DFS)

## Features

- Uses Stack (LIFO)
- Explores nodes deeply before backtracking
- May not always find the shortest path

---

# Sample Output

```text
================================
BREADTH FIRST SEARCH (BFS)
================================
Initial Node : A
Goal Node    : H
Search Path  : A -> B -> E -> H

================================
DEPTH FIRST SEARCH (DFS)
================================
Initial Node : A
Goal Node    : H
Search Path  : A -> B -> E -> H
```

---

# How to Run

## Step 1

Open terminal or Jupyter Notebook.

## Step 2

Run the program:

```bash
python3 search_algorithms.py
```

---

# Author

Your Name
