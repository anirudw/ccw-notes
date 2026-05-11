# Cache Mapping - Practice Problems

**Subject:** COA
**Prerequisites:** [Cache Mapping](../coa/cache-mapping.md), [Memory Hierarchy](../coa/memory-hierarchy.md)
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [Cache mapping - practice problems.pdf](../../raw/Cache%20mapping%20-%20practice%20problems.pdf)

## Summary

This 4-page source contains address-format and set-count practice questions for direct-mapped, fully associative, and set-associative cache organization. Some solution content is embedded as images; those images confirm the main solved results for questions 1, 2, 3/6, and 4.

## Key Takeaways

- Direct-mapped cache indexing is determined by the number of cache lines.
- Block offset bits are determined by the block size in addressable units.
- Fully associative mapping removes the index/set field and uses a larger tag.
- k-way set-associative mapping uses `sets = cache lines / k`.
- Address-format questions are easiest when cache size, block size, and address size are converted to powers of 2.

## Specific Exam-Focused Claims

- A 32 KB direct-mapped cache with 32-byte blocks has 2^10 cache lines, so it needs 10 index bits.
- A 512-line direct-mapped cache with 32-byte blocks and 32-bit byte addresses uses 9 index bits, 5 offset bits, and 18 tag bits.
- A 64 KB, 4-way set-associative cache with 16-byte blocks has 4096 total lines and 1024 sets.
- For a 16-bit word address, 128 cache blocks, and 16-word blocks: direct mapping uses tag/block/word fields of 5/7/4 bits.
- For the same 16-bit word-addressed setup, fully associative mapping uses tag/word fields of 12/4 bits.
- With two blocks per set in the same setup, set-associative mapping uses tag/set/word fields of 6/6/4 bits.

## Distributed Pages

- [Cache Mapping](../coa/cache-mapping.md)
- [Cache Mapping Practice](../problems/cache-mapping-practice.md)
