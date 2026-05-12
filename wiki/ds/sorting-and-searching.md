# Sorting and Searching

**Subject:** DS  
**Prerequisites:** [Linear Structures](linear-structures.md)  
**Exam Importance:** High  
**Last updated:** 2026-05-12  
**Sources:** [DS1 and Supporting Images](../sources/source-ds1-and-supporting-images.md), [Previous Year Question Papers](../sources/source-previous-year-question-papers.md)

## Core Idea

Searching locates a target item; sorting rearranges records into an ordered sequence. Most exam questions ask for algorithm choice, best/average/worst-case complexity, or the state after one step of an algorithm.

## Searching

| Algorithm | Requirement | Best | Average | Worst | Extra space |
| --- | --- | ---: | ---: | ---: | ---: |
| Linear search | None | `O(1)` | `O(n)` | `O(n)` | `O(1)` |
| Binary search | Sorted random-access sequence | `O(1)` | `O(log n)` | `O(log n)` | `O(1)` iterative |

> **[EXAM_TIP]** Binary search is not just "faster search"; it requires sorted data and efficient access to the middle element.

## Sorting Complexity

| Algorithm | Best | Average | Worst | Extra space | Notes |
| --- | ---: | ---: | ---: | ---: | --- |
| Bubble sort | `O(n)` | `O(n^2)` | `O(n^2)` | `O(1)` | Best case assumes an early-exit flag. |
| Selection sort | `O(n^2)` | `O(n^2)` | `O(n^2)` | `O(1)` | Repeatedly selects the minimum. |
| Insertion sort | `O(n)` | `O(n^2)` | `O(n^2)` | `O(1)` | Worst-case comparisons: `n(n - 1) / 2`. |
| Merge sort | `O(n log n)` | `O(n log n)` | `O(n log n)` | `O(n)` | Divide, sort halves, then merge. |
| Quick sort | `O(n log n)` | `O(n log n)` | `O(n^2)` | `O(log n)` average stack | Worst case occurs with highly unbalanced partitions. |
| Heap sort | `O(n log n)` | `O(n log n)` | `O(n log n)` | `O(1)` | Good when worst-case bound matters. |
| Tree sort | `O(n log n)` | `O(n log n)` | `O(n^2)` | `O(n)` | Worst case occurs when the BST becomes skewed. |
| Shell sort | `O(n log n)` typical | Gap-dependent | Gap-dependent | `O(1)` | Bounds depend on the gap sequence. |
| Counting sort | `O(n + k)` | `O(n + k)` | `O(n + k)` | `O(k)` | `k` is the key range. |
| Bucket sort | `O(n + k)` | `O(n + k)` | `O(n^2)` | `O(n + k)` | Assumes near-uniform distribution for linear average time. |
| Radix sort | `O(nk)` | `O(nk)` | `O(nk)` | `O(n + k)` | `k` is digit count or radix-related pass count. |
| Tim sort | `O(n)` | `O(n log n)` | `O(n log n)` | `O(n)` | Practical hybrid used in Python and Java object sorting. |

## Merging Sorted Lists

To merge two sorted lists of sizes `m` and `n`, repeatedly compare the smallest remaining elements and append the smaller one.

- Worst-case comparisons: `m + n - 1`.
- Best-case comparisons: `min(m, n)`.
- Time complexity: `O(m + n)`.
- Extra node allocation can be avoided for linked lists by relinking existing nodes.

## Exam Traps

> **[EXAM_TIP]** Keep best, average, and worst cases separate. The most repeated DS traps are optimized bubble sort best case `O(n)`, quicksort worst case `O(n^2)`, and heapsort worst case `O(n log n)`.

> **[CONNECTION]** External sorting and index scans in [DBMS Indexing and Buffering](../dbms/indexing-and-buffering.md) reuse the same merge and search ideas, but account for disk block transfers.

## See Also

- [Trees and Search Trees](trees-and-search-trees.md)
- [Hashing](hashing.md)
- [DS1 Solved Questions and Complexity Sheets](../problems/ds1-solved-questions.md)
