# COA Previous Year Patterns

**Subject:** COA  
**Prerequisites:** [Memory Hierarchy](memory-hierarchy.md), [Cache Memory](cache-memory.md), [Addressing Modes](addressing-modes.md), [I/O, Interrupts, and DMA](io-interrupts-dma.md)  
**Exam Importance:** High  
**Last updated:** 2026-05-12  
**Sources:** [Previous Year Question Papers](../sources/source-previous-year-question-papers.md)

## Summary

The COA PYQs emphasize cache organization, addressing modes, instruction execution, DMA, interrupts, pipelining, hazards, register-transfer concepts, and basic arithmetic circuits.

## High-Yield Claims

> **[EXAM_TIP]** Pipeline questions commonly use `n + k - 1` cycles for `n` instructions in a `k`-stage pipeline when no stalls are given.

> **[EXAM_TIP]** Cache set count is `cache size / (block size * associativity)`. Direct-mapped, fully associative, and set-associative questions usually reduce to tag, index, and offset bits.

> **[CONNECTION]** Cache and TLB ideas connect directly to [OS Virtual Memory](../os/virtual-memory.md) and [DBMS Indexing and Buffering](../dbms/indexing-and-buffering.md).

## Recurring PYQ Areas

- Cache memory: associativity, set count, cache access tradeoffs, memory hierarchy.
- Addressing modes: immediate, direct, implied, register indirect, auto-increment, auto-decrement.
- Pipeline behavior: structural, data, control hazards; RAW, WAR, WAW; register renaming.
- I/O: DMA transfer, cycle stealing, interrupts, daisy chaining.
- Datapath basics: program counter, MBR, arithmetic circuits, RTL, instruction cycle.
- Representation: two's-complement arithmetic and ROM-size calculations.

## Solved Coverage

See [Previous Year Questions - Solved and Grouped](../problems/previous-year-questions-solved.md#coa) for all 46 COA PYQ entries.
