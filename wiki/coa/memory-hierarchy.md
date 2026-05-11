# Memory Hierarchy

**Subject:** COA
**Prerequisites:** None
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [COA Comprehensive Study Materials - Kerala Notes](../sources/source-coa-comprehensive-study-materials-kerala-notes.md)

## Definition

Memory hierarchy orders storage by speed, cost, capacity, and distance from the CPU. A typical order from fastest/smallest to slowest/largest is:

1. CPU registers
2. [Cache memory](cache-memory.md)
3. Main memory, usually DRAM
4. Secondary storage

The lowest level in the hierarchy among cache, RAM, registers, and secondary memory is secondary memory.

## Core Facts

- Access time is the average time required to reach a storage location and obtain its contents.
- RAM is volatile, so it is not suitable for permanent storage.
- DRAM is commonly used for main memory because it provides higher density and lower cost per bit than SRAM, though it needs refresh circuitry.
- Associative memory is accessed by content; this is the conceptual basis for fully associative cache lookup.

> **[EXAM_TIP]** If an MCQ asks for "lowest in memory hierarchy" among registers, cache, RAM, and secondary memory, choose secondary memory.

> **[CONNECTION]** OS [Virtual Memory](../os/virtual-memory.md) extends the memory hierarchy by giving each process an address space that can be backed by RAM and secondary storage.

> **[CONNECTION]** DBMS [Indexing and Buffering](../dbms/indexing-and-buffering.md) relies on the same hierarchy: disk pages are copied into a buffer pool, then into CPU caches during query execution.
