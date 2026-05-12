# Linear Structures

**Subject:** DS  
**Prerequisites:** None  
**Exam Importance:** High  
**Last updated:** 2026-05-12  
**Sources:** [DS1 and Supporting Images](../sources/source-ds1-and-supporting-images.md), [Previous Year Question Papers](../sources/source-previous-year-question-papers.md)

## Core Idea

Linear structures arrange elements in sequence. Arrays provide direct indexing; linked lists provide pointer-based traversal; stacks and queues restrict access order.

## Stack

A stack follows LIFO: last in, first out.

- `push`: insert at top.
- `pop`: remove from top.
- `peek`: read top without removal.
- Underflow in an array stack commonly means `TOP = -1`.
- Recursion uses the call stack for activation records.

> **[EXAM_TIP]** In expression conversion and evaluation, stacks handle operators, operands, parentheses, and recursive calls.

## Queue and Circular Queue

A queue follows FIFO: first in, first out.

- `enqueue`: insert at rear.
- `dequeue`: remove from front.
- BFS uses a queue to visit vertices level by level.
- In an array circular queue with exactly one element, `FRONT = REAR`.

Circular queues reuse freed slots by advancing indices modulo the array size.

## Linked Lists

To test whether a linked list is empty:

```cpp
if (head == nullptr) {
    // empty list
}
```

To move to the last node:

```cpp
while (temp->next != NULL) {
    temp = temp->next;
}
```

To count nodes:

```cpp
int length = 0;
while (head) {
    length++;
    head = head->next;
}
```

> **[EXAM_TIP]** The loop for the last node checks `temp->next`, not `temp`, because it should stop with `temp` still pointing to the final node.

## Operation Costs

| Structure | Access | Search | Insert | Delete | Space |
| --- | ---: | ---: | ---: | ---: | ---: |
| Array | `O(1)` | `O(n)` | `O(n)` | `O(n)` | `O(n)` |
| Stack | `O(n)` arbitrary | `O(n)` | `O(1)` | `O(1)` | `O(n)` |
| Queue | `O(n)` arbitrary | `O(n)` | `O(1)` | `O(1)` | `O(n)` |
| Singly linked list | `O(n)` | `O(n)` | `O(1)` if position/node known | `O(1)` if predecessor known | `O(n)` |
| Doubly linked list | `O(n)` | `O(n)` | `O(1)` if position/node known | `O(1)` if node known | `O(n)` |

If a linked-list operation must first search by value or position, include the `O(n)` traversal cost.

## Expression Evaluation Example

Prefix expression:

```text
+ A * - B C D
```

Parse it as:

```text
(+ A (* (- B C) D))
```

For `A=5`, `B=4`, `C=2`, `D=3`:

```text
5 + ((4 - 2) * 3) = 11
```

## See Also

- [Graph Traversal](graph-traversal.md)
- [Sorting and Searching](sorting-and-searching.md)
- [DS1 Solved Questions and Complexity Sheets](../problems/ds1-solved-questions.md)
