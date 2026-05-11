# Cache Mapping Practice

**Subject:** COA
**Prerequisites:** [Cache Mapping](../coa/cache-mapping.md), [Cache Memory](../coa/cache-memory.md)
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [Cache Mapping - Practice Problems](../sources/source-cache-mapping-practice-problems.md)

## Formula Sheet

```text
cache lines = cache size / block size
offset bits = log2(block size)
direct index bits = log2(cache lines)
sets = cache lines / associativity
set bits = log2(sets)
tag bits = address bits - index/set bits - offset bits
```

> **[EXAM_TIP]** Convert all sizes to powers of 2 before splitting the address. Most cache-address questions are one-line arithmetic once the powers are visible.

## Problem 1

Direct-mapped cache size = 32 KB, block size = 32 bytes, CPU address = 32 bits.

```text
cache size = 32 KB = 2^15 bytes
block size = 32 bytes = 2^5 bytes
cache lines = 2^15 / 2^5 = 2^10
index bits = log2(2^10) = 10
```

Answer: 10 index bits.

## Problem 2

Cache has 128 blocks of 16 words. Main memory is word-addressable with 16-bit addresses, so it has 64K words. Each memory block has 16 words.

```text
word offset = log2(16) = 4 bits
memory blocks = 64K / 16 = 4096 = 2^12
cache blocks = 128 = 2^7
```

Direct-mapped format:

```text
tag = 16 - 7 - 4 = 5 bits
block/index = 7 bits
word = 4 bits
```

Fully associative format:

```text
tag = 16 - 4 = 12 bits
word = 4 bits
```

2-way set-associative format from the source image:

```text
sets = 128 / 2 = 64 = 2^6
set = 6 bits
tag = 16 - 6 - 4 = 6 bits
word = 4 bits
```

## Problem 3

4-way set-associative cache, total size = 64 KB, block size = 16 bytes.

```text
cache size = 64 KB = 65536 bytes
block size = 16 bytes
cache lines = 65536 / 16 = 4096
sets = 4096 / 4 = 1024
```

Answer: 1024 sets.

## Problem 4

Direct-mapped cache with 512 blocks, block size = 32 bytes, 32-bit byte address.

```text
offset bits = log2(32) = 5
index bits = log2(512) = 9
tag bits = 32 - 9 - 5 = 18
```

Answer: 18 tag bits.

## Problem 5

Source question text: unavailable in the extracted PDF content. The text layer exposes only the label `5.`, and the embedded image extracted from that page contains the solution for Problem 4 rather than a readable Problem 5 prompt.

Do not revise from this item until the PDF is manually inspected in a reader.

## Problem 6

The extracted question duplicates the 4-way, 64 KB, 16-byte-block set-count setup.

Answer: 1024 sets.
