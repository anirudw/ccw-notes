# Indexing and Buffering

**Subject:** DBMS
**Prerequisites:** [Memory Hierarchy](../coa/memory-hierarchy.md)
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [COA Comprehensive Study Materials - Kerala Notes](../sources/source-coa-comprehensive-study-materials-kerala-notes.md), [Cache Mapping - Practice Problems](../sources/source-cache-mapping-practice-problems.md), [DBMS Comprehensive Study Materials - Kerala Notes](../sources/source-dbms-comprehensive-study-materials-kerala-notes.md)

## Definition

DBMS indexing and buffering are storage-layer techniques for reducing slow disk I/O. Indexes, commonly tree-based or hash-based, reduce the number of pages that must be searched. The buffer pool keeps recently used disk pages in main memory.

## DBMS Source Claims

- A high-speed, large-capacity disk is a key hardware component for DBMS operation.
- A major goal of a database system is to minimize block transfers between disk and memory.
- A buffer helps achieve that goal by holding copies of disk blocks in memory.
- Hashing is an access method based on key transformation.
- File organization is treated as a DBMS utility in the source.

> **[EXAM_TIP]** If a question asks what minimizes disk-memory block transfers, answer buffer.

> **[EXAM_TIP]** The source marks RAID 1 for best write performance in a log-file question. Standard COA/DBMS reasoning usually chooses RAID 0 for highest raw write throughput when redundancy is ignored; RAID 1 is mirroring for reliability.

## COA Connection

> **[CONNECTION]** COA [Memory Hierarchy](../coa/memory-hierarchy.md) explains why DBMSs avoid repeated disk access: secondary storage is lower and slower than RAM and CPU cache.

> **[CONNECTION]** COA [Cache Memory](../coa/cache-memory.md) and a DBMS buffer pool both exploit locality. The hardware cache stores memory blocks; the DBMS buffer pool stores database pages.

> **[CONNECTION]** COA [Cache Mapping](../coa/cache-mapping.md) uses block placement rules. DBMS page layout and indexing also depend on fixed-size blocks/pages, although placement is managed by software rather than cache hardware.

## Exam Notes

- When analyzing DBMS performance, count page I/O first; CPU cache effects are usually a secondary detail.
- Buffer-pool replacement is conceptually related to cache/page replacement but controlled by the DBMS.
- B-tree style indexes are useful because their nodes are page-sized, limiting disk-page reads.
