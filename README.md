# AIML Experiment 02 - A* and Memory-Bounded A* Search

## Aim

To implement informed search algorithms:
- A* Search
- Memory-Bounded A* Search (IDA*)

## Description

This experiment demonstrates informed search techniques using the 8-Puzzle problem.

The Manhattan Distance heuristic is used to estimate the cost from the current state to the goal state.

## Algorithms Used

### 1. A* Search

A* selects the state with the lowest:

f(n) = g(n) + h(n)

Where:
- `g(n)` = cost from the initial state to the current state
- `h(n)` = heuristic estimated cost to the goal
- `f(n)` = total estimated cost

### 2. Memory-Bounded A* Search (IDA*)

IDA* combines the memory efficiency of Depth-First Search with the heuristic guidance of A*.

It uses a threshold based on the heuristic value and searches within that threshold.

## Heuristic

Manhattan Distance is calculated as:

`|x1 - x2| + |y1 - y2|`

It estimates how far each puzzle tile is from its goal position.

## Technologies Used

- Python 3
- Priority Queue
- Manhattan Distance Heuristic
- A* Search
- IDA* Search

## How to Run

1. Install Python 3.
2. Open the terminal in this project folder.
3. Run:

```bash
python a_star.py
