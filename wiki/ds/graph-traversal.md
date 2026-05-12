# Graph Traversal

**Subject:** DS  
**Prerequisites:** [Linear Structures](linear-structures.md)  
**Exam Importance:** High  
**Last updated:** 2026-05-12  
**Sources:** [DS1 and Supporting Images](../sources/source-ds1-and-supporting-images.md), [Previous Year Question Papers](../sources/source-previous-year-question-papers.md)

## Breadth-First Search

Breadth-first search visits a start vertex, then all of its unvisited neighbors, then vertices at the next distance level. It uses a queue.

Basic BFS pattern:

```text
mark source visited
enqueue source
while queue is not empty:
    v = dequeue
    visit v
    for each unvisited neighbor u of v:
        mark u visited
        enqueue u
```

For an adjacency-list graph, BFS runs in `O(V + E)` time and uses `O(V)` extra space for the queue and visited set.

## Disconnected Graphs

If the graph is disconnected and the task asks for a full traversal, restart BFS from another unvisited vertex after the current queue becomes empty.

DS1 includes an example whose visible output is:

```text
0, 2, 3, 1, 4, 5
```

The source explanation says BFS starts from `0`, finishes that component, then starts another BFS from `4` and visits `5`.

## Ordering Caveat

BFS order can differ when a node's neighbors can be processed in different orders. Exam diagrams usually imply a fixed left-to-right, numeric, or listed adjacency order.

> **[EXAM_TIP]** BFS uses a queue; DFS uses a stack or recursion. This distinction is frequently tested directly.

## See Also

- [Linear Structures](linear-structures.md)
- [Trees and Search Trees](trees-and-search-trees.md)
- [DS1 Solved Questions and Complexity Sheets](../problems/ds1-solved-questions.md)
