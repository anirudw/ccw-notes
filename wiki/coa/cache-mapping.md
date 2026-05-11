# Cache Mapping

**Subject:** COA
**Prerequisites:** [Cache Memory](cache-memory.md), [Memory Hierarchy](memory-hierarchy.md)
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [COA Comprehensive Study Materials - Kerala Notes](../sources/source-coa-comprehensive-study-materials-kerala-notes.md), [Cache Mapping - Practice Problems](../sources/source-cache-mapping-practice-problems.md)

## Definition

Cache mapping defines where a main-memory block is allowed to reside in cache and how a CPU address is split into lookup fields.

## Address Fields

For byte-addressed memory:

```text
block offset bits = log2(block size in bytes)
cache lines       = cache size / block size
```

For word-addressed memory, compute the offset using block size in words.

## Direct Mapping

Each memory block maps to exactly one cache line.

```text
index bits = log2(number of cache lines)
tag bits   = address bits - index bits - offset bits
```

> **[EXAM_TIP]** Direct mapping is fast and simple, but it can cause conflict misses because many memory blocks compete for the same cache line.

## Fully Associative Mapping

Any memory block can be placed in any cache line. There is no index field.

```text
tag bits = address bits - offset bits
```

This needs associative comparison across tags, so hardware cost is higher.

## k-Way Set-Associative Mapping

Cache lines are divided into sets. A memory block maps to one set, but can occupy any line within that set.

```text
sets     = cache lines / k
set bits = log2(sets)
tag bits = address bits - set bits - offset bits
```

## High-Yield Worked Formats

For a 16-bit word address, 128 cache blocks, and 16-word blocks:

| Mapping | Tag | Block/Set | Word |
| --- | ---: | ---: | ---: |
| Direct mapped | 5 | 7 block bits | 4 |
| Fully associative | 12 | none | 4 |
| 2-way set-associative | 6 | 6 set bits | 4 |

For a 32-bit byte address with direct mapping, 512 cache blocks, and 32-byte blocks:

```text
offset = log2(32) = 5 bits
index  = log2(512) = 9 bits
tag    = 32 - 9 - 5 = 18 bits
```

> **[CONNECTION]** The tag/index/offset split is similar in spirit to OS [Virtual Memory](../os/virtual-memory.md), where a virtual address is split into page number and page offset.

> **[CONNECTION]** DBMS [Indexing and Buffering](../dbms/indexing-and-buffering.md) uses block/page granularity, so cache-block thinking helps when analyzing disk pages and buffer-pool hits.

## See Also

- [Cache Mapping Practice](../problems/cache-mapping-practice.md)
