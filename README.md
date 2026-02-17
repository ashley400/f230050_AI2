# AI Search Algorithms Visualizer

A GUI‑based project that demonstrates how different Artificial Intelligence search strategies work in path finding / graph traversal problems.
The program allows you to select an algorithm, choose a start & goal node, and visually observe how the algorithm explores the graph.

---

## Algorithms Implemented

* Breadth First Search (BFS)
* Depth First Search (DFS)
* Uniform Cost Search (UCS)
* Greedy Best‑First Search
* A* Search

---

## Features

* Interactive GUI visualization
* Step‑by‑step node exploration
* Comparison of algorithms performance
* Best case & worst case demonstrations
* Path cost display (for weighted algorithms)

---

## Project Structure

```
project/
│── main.py                # Program entry point
│── gui.py                 # GUI handling
│── graph.py               # Graph generation / representation
│── algorithms/
│     ├── bfs.py
│     ├── dfs.py
│     ├── ucs.py
│     ├── greedy.py
│     └── astar.py
│── assets/                # icons / images (optional)
│── README.md
```

---

## Requirements

Install Python 3.9 or above.

### Required Libraries

Install dependencies using pip:

```
pip install matplotlib
pip install networkx
pip install numpy
pip install tkinter
```

> Note: tkinter comes preinstalled with most Python distributions. If missing, install it using your system package manager.

---

## How to Run the Project

1. Download or clone the repository

```
git clone https://github.com/your-username/ai-search-visualizer.git
cd ai-search-visualizer
```

2. Install dependencies

```
pip install -r requirements.txt
```

(or install manually from the list above)

3. Run the program

```
python main.py
```

The GUI window will open where you can:

* Select an algorithm
* Select start node
* Select goal node
* Click RUN to visualize the search

---

## How It Works

1. User selects a search algorithm
2. Graph is generated
3. Algorithm expands nodes step‑by‑step
4. Explored nodes are colored differently from frontier nodes
5. Final path is highlighted when goal is reached

---

## Test Case Demonstration

### Best Case

Target node found immediately with minimal expansions

(Add Screenshot Here)

### Worst Case

Target found after exploring most of the graph

(Add Screenshot Here)

---

## Learning Purpose

This project helps understand:

* Difference between uninformed & informed search
* Effect of heuristics
* Optimal vs non‑optimal algorithms
* Time & space complexity behavior

