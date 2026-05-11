# Cache Memory

**Subject:** COA
**Prerequisites:** [Memory Hierarchy](memory-hierarchy.md)
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [COA Comprehensive Study Materials - Kerala Notes](../sources/source-coa-comprehensive-study-materials-kerala-notes.md), [Cache Mapping - Practice Problems](../sources/source-cache-mapping-practice-problems.md)

## Definition

Cache memory is a small, fast memory placed between the CPU and main memory. It stores recently or frequently used blocks so the CPU can avoid slower main-memory accesses.

Cache effectiveness depends on locality of reference:

- Temporal locality: recently accessed data or instructions are likely to be accessed again.
- Spatial locality: nearby addresses are likely to be accessed soon.

## Performance Terms

- Hit: requested block is present in cache.
- Miss: requested block is absent and must be fetched from a lower memory level.
- Hit ratio: fraction of accesses that hit.
- Miss ratio: fraction of accesses that miss; `miss ratio = 1 - hit ratio`.
- Average memory access time: `AMAT = hit time + miss rate * miss penalty`.

For the source problem with effective access time 20 ns, cache access 10 ns, and main-memory access 110 ns:

```text
20 = h * 10 + (1 - h) * 110
20 = 110 - 100h
h = 0.90
```

So the hit ratio is 90 percent.

## Write Policies

Write-through updates the cache and the next lower memory level on each write. It simplifies consistency but increases write traffic. Write-back updates the lower level only when a dirty cache block is evicted.

> **[EXAM_TIP]** "Write-through" belongs to cache memory. If an MCQ asks which memory uses write-through for updating data, the expected answer is cache memory.

> **[CONNECTION]** Cache replacement ideas connect to OS [Virtual Memory](../os/virtual-memory.md), where page replacement also depends on locality and reference history.

> **[CONNECTION]** DBMS [Indexing and Buffering](../dbms/indexing-and-buffering.md) uses a software-managed cache of disk pages called the buffer pool.

## See Also

- [Cache Mapping](cache-mapping.md)
- [Cache Mapping Practice](../problems/cache-mapping-practice.md)
