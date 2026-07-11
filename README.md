# 🧠 Fundamentals of Artificial Intelligence

[![Python](https://img.shields.io/badge/Python-3.x-yellow.svg)](https://www.python.org/)
[![Topic](https://img.shields.io/badge/Domain-Graph_Theory_&_Search-blue.svg)](https://en.wikipedia.org/wiki/Breadth-first_search)

This repository contains educational implementations of essential Artificial Intelligence algorithms, focused primarily on search strategies, graph traversal methods, and foundational problem-solving heuristics.

---

## 🔍 Implemented Algorithms

### 1. Breadth-First Search (BFS)
* **File:** [`bfs.py`](bfs.py)
* **Description:** A classic uninformed search strategy used to traverse or explore tree/graph data structures level-by-level. Starting from a root node, BFS expands all neighboring nodes at the current depth level before moving to the next depth layer.
* **Complexity:** Time Complexity $\mathcal{O}(V + E)$, Space Complexity $\mathcal{O}(V)$ (where $V$ is vertices and $E$ is edges).
* **Usage:** Used for finding the shortest path on unweighted graphs and checking connectivity components.

#### logic Flow
```mermaid
graph TD
    A[A] --> B[B]
    A --> C[C]
    B --> D[D]
    B --> E[E]
    C --> F[F]
    C --> G[G]

    style A fill:#4F46E5,stroke:#fff,stroke-width:2px,color:#fff
    style B fill:#06B6D4,stroke:#fff,stroke-width:2px,color:#fff
    style C fill:#06B6D4,stroke:#fff,stroke-width:2px,color:#fff
    style D fill:#10B981,stroke:#fff,stroke-width:1px,color:#fff
    style E fill:#10B981,stroke:#fff,stroke-width:1px,color:#fff
    style F fill:#10B981,stroke:#fff,stroke-width:1px,color:#fff
    style G fill:#10B981,stroke:#fff,stroke-width:1px,color:#fff
```
The traversal order of the above graph using BFS starting at **A** is:
$$\text{A} \rightarrow \text{B} \rightarrow \text{C} \rightarrow \text{D} \rightarrow \text{E} \rightarrow \text{F} \rightarrow \text{G}$$

---

## 🚀 How to Run

### Setup
Ensure you have Python installed on your computer.

### BFS Execution
Run the following script to see the graph traversal:
```bash
python bfs.py
```

### Test Script
To execute the quick diagnostics file:
```bash
python test.py
```
