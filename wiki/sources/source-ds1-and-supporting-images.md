# DS1 and Supporting Images

**Subject:** DS  
**Prerequisites:** [DS Previous Year Patterns](../ds/previous-year-patterns.md)  
**Exam Importance:** High  
**Last updated:** 2026-05-12  
**Sources:** [DS1.pdf](../../raw/DS1.pdf), [WhatsApp Image 2026-05-10 at 9.39.59 AM.jpeg](../../raw/WhatsApp%20Image%202026-05-10%20at%209.39.59%20AM.jpeg), [WhatsApp Image 2026-05-10 at 9.42.19 AM.jpeg](../../raw/WhatsApp%20Image%202026-05-10%20at%209.42.19%20AM.jpeg)

## Summary

`DS1.pdf` is a short DS revision packet with 15 numbered entries. It covers binary tree reconstruction, circular queue state, prefix expression evaluation, BFS examples, BST search paths, linked-list traversal checks, sorting and data-structure complexity tables, merging sorted lists, BST insertion height, and Catalan counting of binary trees.

The two WhatsApp images are complexity cheat sheets. One focuses on sorting algorithms; the other summarizes search and sort algorithm best, average, worst, and space complexity.

## Coverage

| Source | Extracted content | Ingest status |
| --- | ---: | --- |
| `raw/DS1.pdf` | 15 numbered entries plus embedded image explanations | Covered |
| `raw/WhatsApp Image 2026-05-10 at 9.39.59 AM.jpeg` | Sorting complexity table | Covered |
| `raw/WhatsApp Image 2026-05-10 at 9.42.19 AM.jpeg` | Search and sorting complexity table | Covered |

Complete question-level coverage is in [DS1 Solved Questions and Complexity Sheets](../problems/ds1-solved-questions.md).

## Key Takeaways

- Tree height in these sources is measured as edge count unless a question explicitly asks for number of nodes on the path.
- `FRONT = REAR` is the key circular-queue condition when exactly one element is present.
- Prefix expression `+ A * - B C D` evaluates as `A + ((B - C) * D)`.
- BFS is queue-based and may require restarting from unvisited vertices in disconnected graphs.
- BST search paths must obey a narrowing low/high interval at every visited node.
- Merging two sorted lists takes `O(m + n)` time and at most `m + n - 1` element comparisons.
- Distinct binary tree shapes with `n` unlabeled nodes are counted by the Catalan number `C_n`.

## Source Issues Flagged

> **[EXAM_TIP]** The PDF has image-only prompts and OCR-noisy tables. Revise from the distributed wiki pages and solved sheet rather than from raw OCR alone.

- Several BFS prompts are diagrams without reliable text extraction; the solved sheet preserves the visible output orders.
- The Catalan formula for binary trees should be `C_n = (1 / (n + 1)) * binom(2n, n)`. For `n = 3`, this gives `5`.
- Complexity tables hide important assumptions: binary search needs sorted random-access data, linked-list deletion may be `O(n)` if the node must first be searched, and hash-table `O(1)` operations assume good hashing and controlled load factor.

## Distributed Pages

- [Linear Structures](../ds/linear-structures.md)
- [Trees and Search Trees](../ds/trees-and-search-trees.md)
- [Graph Traversal](../ds/graph-traversal.md)
- [Sorting and Searching](../ds/sorting-and-searching.md)
- [Hashing](../ds/hashing.md)
- [DS1 Solved Questions and Complexity Sheets](../problems/ds1-solved-questions.md)
