# DS1 Solved Questions and Complexity Sheets

**Subject:** DS  
**Prerequisites:** [Linear Structures](../ds/linear-structures.md), [Trees and Search Trees](../ds/trees-and-search-trees.md), [Graph Traversal](../ds/graph-traversal.md), [Sorting and Searching](../ds/sorting-and-searching.md)  
**Exam Importance:** High  
**Last updated:** 2026-05-12  
**Sources:** [DS1 and Supporting Images](../sources/source-ds1-and-supporting-images.md)

## Coverage Audit

Total covered entries: 15 numbered entries from `DS1.pdf` plus 2 supporting complexity images.

> **[EXAM_TIP]** Several entries overlap previous-year DS questions. For repeated exam topics, prefer the concise claims in the DS topic pages and use this page as the source audit trail.

## DS1 Entries

| ID | Source prompt | Answer or extracted claim |
| --- | --- | --- |
| DS1-01 | Given postorder `8,9,6,7,4,5,2,3,1` and inorder `8,6,9,4,7,2,5,1,3`, find binary-tree height. | Root is `1`. The longest root-to-leaf path is `1 -> 2 -> 4 -> 6 -> 8` or `1 -> 2 -> 4 -> 6 -> 9`, so height is `4` edges, or `5` nodes if counting nodes. |
| DS1-02 | External DSA resource link. | Preserved as source context: `https://www.wscubetech.com/resources/dsa`. |
| DS1-03 | Circular queue with only one element. | `FRONT = REAR`; the same array index is both the first and last element. |
| DS1-04 | Evaluate prefix `+ A * - B C D` for `A=5, B=4, C=2, D=3`. | `5 + ((4 - 2) * 3) = 11`. |
| DS1-05 | BFS example, graph prompt image-only. | OCR-visible output: `[0, 1, 2, 3, 4]`. |
| DS1-06 | BFS example with disconnected component, prompt image-only. | OCR-visible output: `[0, 2, 3, 1, 4, 5]`; after finishing the component of `0`, BFS restarts at `4` and visits `5`. |
| DS1-07 | BFS example, prompt image-only. | OCR-visible output order: `0 1 2 3 4`. |
| DS1-08 | Which sequence can be examined while searching for key `88` in a BST? | `190, 60, 90, 85, 88`. It respects the narrowing search interval. |
| DS1-09 | Find the last node of a linked list. | `while (temp->next != NULL) { temp = temp->next; }` leaves `temp` at the last node. |
| DS1-10 | Check whether a linked list is empty. | `if (head == nullptr)` is true when the list has no nodes. |
| DS1-11 | Count nodes in a linked list. | Loop while `head` is not null, increment the length, then advance `head = head->next`. |
| DS1-12 | Embedded complexity tables. | Sorting and data-structure operation complexities are distributed to [Sorting and Searching](../ds/sorting-and-searching.md), [Linear Structures](../ds/linear-structures.md), [Trees and Search Trees](../ds/trees-and-search-trees.md), and [Hashing](../ds/hashing.md). |
| DS1-13 | Comparisons for merging sorted lists of sizes `m` and `n`. | Worst case: `m + n - 1` comparisons; best case: `min(m, n)` comparisons; time complexity: `O(m + n)`. |
| DS1-14 | Insert `10, 1, 3, 5, 15, 12, 16` into an empty BST and find height. | Longest path is `10 -> 1 -> 3 -> 5`; height is `3` edges. |
| DS1-15 | Maximum number of binary trees with three unlabeled nodes. | Catalan number `C_3 = binom(6, 3) / 4 = 5`. |

## Supporting Images

| Source image | Extracted focus | Distributed to |
| --- | --- | --- |
| `WhatsApp Image 2026-05-10 at 9.39.59 AM.jpeg` | Array sorting algorithms: quicksort, mergesort, heapsort, bubble, insertion, selection, tree sort, shell sort, bucket, radix, counting, cubesort. | [Sorting and Searching](../ds/sorting-and-searching.md) |
| `WhatsApp Image 2026-05-10 at 9.42.19 AM.jpeg` | Linear search, binary search, and common sorting algorithm complexities. | [Sorting and Searching](../ds/sorting-and-searching.md) |

## See Also

- [Previous Year Questions - Solved and Grouped](previous-year-questions-solved.md#ds)
- [DS Previous Year Patterns](../ds/previous-year-patterns.md)
