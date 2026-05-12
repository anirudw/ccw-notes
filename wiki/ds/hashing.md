# Hashing

**Subject:** DS  
**Prerequisites:** [Arrays and linear structures](linear-structures.md)  
**Exam Importance:** High  
**Last updated:** 2026-05-12  
**Sources:** [DS1 and Supporting Images](../sources/source-ds1-and-supporting-images.md), [Previous Year Question Papers](../sources/source-previous-year-question-papers.md)

## Core Idea

Hashing maps a key to a table index using a hash function. The goal is fast search, insertion, and deletion without keeping all keys sorted.

```text
index = h(key) mod table_size
```

A collision occurs when two different keys map to the same table slot.

## Collision Handling

Separate chaining stores a linked list or bucket at each table slot. When several keys hash to the same index, they are kept in that bucket.

Open addressing stores all keys inside the table itself and probes for another slot after a collision.

## Complexity

| Operation | Average | Worst |
| --- | ---: | ---: |
| Search | `O(1)` | `O(n)` |
| Insert | `O(1)` | `O(n)` |
| Delete | `O(1)` | `O(n)` |

Average `O(1)` assumes a good hash function and a controlled load factor. Worst case occurs when many keys collide into the same bucket or probe chain.

> **[EXAM_TIP]** "Different keys producing the same hash value" is a collision. "Each table slot stores a linked list" is separate chaining.

> **[CONNECTION]** Hashing appears again in [DBMS Indexing and Buffering](../dbms/indexing-and-buffering.md), where hash-based file organization uses the same key-to-bucket idea.

## See Also

- [Sorting and Searching](sorting-and-searching.md)
- [Linear Structures](linear-structures.md)
