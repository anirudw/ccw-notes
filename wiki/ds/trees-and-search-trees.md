# Trees and Search Trees

**Subject:** DS  
**Prerequisites:** [Linear Structures](linear-structures.md)  
**Exam Importance:** High  
**Last updated:** 2026-05-12  
**Sources:** [DS1 and Supporting Images](../sources/source-ds1-and-supporting-images.md), [Previous Year Question Papers](../sources/source-previous-year-question-papers.md)

## Binary Tree Basics

A binary tree node has at most two children. Common traversals are:

- Inorder: left, root, right.
- Preorder: root, left, right.
- Postorder: left, right, root.
- Level order: breadth-first traversal using a queue.

Tree height is often measured as the number of edges on the longest root-to-leaf path. Some sources count nodes instead, so check the question wording.

## Reconstructing From Inorder and Postorder

In postorder traversal, the last item is the root. In inorder traversal, the root splits the left and right subtrees.

For the DS1 traversals:

```text
postorder = 8,9,6,7,4,5,2,3,1
inorder   = 8,6,9,4,7,2,5,1,3
```

Root is `1`. Reconstructing recursively gives the longest path:

```text
1 -> 2 -> 4 -> 6 -> 8
```

So the height is `4` edges, or `5` nodes under the node-count convention.

## Binary Search Tree

In a BST, every key in the left subtree is smaller than the node key, and every key in the right subtree is larger than the node key.

During search, each visited key narrows the valid interval for all later keys. For key `88`, the sequence:

```text
190, 60, 90, 85, 88
```

is valid:

- `88 < 190`, so go left.
- `88 > 60`, so go right; later keys must be between `60` and `190`.
- `88 < 90`, so go left; later keys must be between `60` and `90`.
- `88 > 85`, so go right; later keys must be between `85` and `90`.

## BST Insertion Height Example

Insert:

```text
10, 1, 3, 5, 15, 12, 16
```

The longest path after insertion is:

```text
10 -> 1 -> 3 -> 5
```

Height is `3` edges.

## Counting Binary Trees

The number of distinct binary tree shapes with `n` unlabeled nodes is the Catalan number:

```text
C_n = (1 / (n + 1)) * binom(2n, n)
```

For `n = 3`:

```text
C_3 = binom(6, 3) / 4 = 20 / 4 = 5
```

## Search Tree Operation Costs

| Structure | Average search/insert/delete | Worst search/insert/delete | Space |
| --- | ---: | ---: | ---: |
| Unbalanced BST | `O(log n)` if balanced | `O(n)` if skewed | `O(n)` |
| AVL tree | `O(log n)` | `O(log n)` | `O(n)` |
| Splay tree | `O(log n)` amortized | `O(n)` single operation | `O(n)` |
| B-tree | `O(log n)` | `O(log n)` | `O(n)` |
| Skip list | `O(log n)` expected | `O(n)` | `O(n)` expected |

> **[EXAM_TIP]** Inorder traversal of a BST gives keys in sorted order.

> **[CONNECTION]** B-trees are central to database indexes; see [DBMS Indexing and Buffering](../dbms/indexing-and-buffering.md).

## See Also

- [Graph Traversal](graph-traversal.md)
- [Sorting and Searching](sorting-and-searching.md)
- [DS1 Solved Questions and Complexity Sheets](../problems/ds1-solved-questions.md)
