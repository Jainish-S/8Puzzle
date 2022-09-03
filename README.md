# 8Puzzle

Classic 8 Puzzle problem solved using blind search algo dfs &amp; bfs with visualization.

- Used graphviz library to make the tree.

### Example

```python

start_state = [
    [1, 8, 2], 
    [0, 4, 3], 
    [7, 6, 5]
]

end_state = [
    [1, 8, 2],
    [7, 4, 3],
    [6, 0, 5]
]

```

## Search Space

![BFS](./BFS.gv.svg)

# TODO
- Add heuristic search algorithm like A<sup>*</sup>
