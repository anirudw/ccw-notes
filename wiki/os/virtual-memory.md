# Virtual Memory

**Subject:** OS
**Prerequisites:** [Memory Hierarchy](../coa/memory-hierarchy.md)
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [COA Comprehensive Study Materials - Kerala Notes](../sources/source-coa-comprehensive-study-materials-kerala-notes.md)

## Definition

Virtual memory is an OS memory-management abstraction that gives a process a logical address space independent of the physical RAM currently assigned to it. The OS and hardware translate virtual addresses to physical addresses using page tables and related hardware such as a TLB.

Virtual memory is not SRAM, DRAM, or a single physical memory device. It is a mapping and storage-management technique backed by RAM and secondary storage.

## COA Connection

> **[CONNECTION]** COA [Cache Mapping](../coa/cache-mapping.md) splits an address into tag/index/offset fields. Paging similarly splits a virtual address into page number and page offset.

> **[CONNECTION]** COA [Cache Memory](../coa/cache-memory.md) and OS virtual memory both exploit locality. Cache replacement works on cache blocks; page replacement works on pages.

## Exam Notes

- A physical address is an address in main memory.
- Aging registers are counters that estimate how long ago pages were referenced; they support page-replacement decisions.
- A CPU executing OS code is commonly described as running in system/supervisor/kernel mode.

> **[EXAM_TIP]** If a source claims "virtual memory consists of Static RAM," verify it. Standard OS definition treats virtual memory as an address-space abstraction, not a type of chip.
