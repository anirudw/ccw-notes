# OS Previous Year Patterns

**Subject:** OS  
**Prerequisites:** [Virtual Memory](virtual-memory.md), [Previous Year Questions - Solved and Grouped](../problems/previous-year-questions-solved.md)  
**Exam Importance:** High  
**Last updated:** 2026-05-12  
**Sources:** [Previous Year Question Papers](../sources/source-previous-year-question-papers.md)

## Summary

The OS PYQs repeatedly test scheduling, process state, threads, semaphores, deadlock handling, paging, TLBs, page replacement, and disk scheduling. Numerical questions usually require simulating the policy exactly rather than memorizing a final formula.

## High-Yield Claims

> **[EXAM_TIP]** Banker's algorithm is deadlock avoidance, not deadlock prevention.

> **[EXAM_TIP]** FIFO page replacement can show Belady's anomaly. Always simulate frame contents when asked for page-fault counts.

> **[CONNECTION]** Paging and TLB questions connect OS memory management to [COA Memory Hierarchy](../coa/memory-hierarchy.md) and [Cache Memory](../coa/cache-memory.md).

## Recurring PYQ Areas

- CPU scheduling: FCFS, SRTF, round robin, waiting time, response time, context switches.
- Process and thread state: `fork`, `exec`, PCB contents, thread-shared and thread-private resources.
- Synchronization: semaphore arithmetic, starvation, aging, mutual exclusion.
- Deadlocks: necessary conditions, prevention, avoidance, Banker's algorithm.
- Memory management: paging, page faults, internal fragmentation, TLB tags, page-table fields.
- Storage scheduling: SCAN, C-SCAN, SSTF, total head movement.

## Solved Coverage

See [Previous Year Questions - Solved and Grouped](../problems/previous-year-questions-solved.md#os) for all 48 OS PYQ entries.
