# Previous Year Question Papers

**Subject:** DS | OS | COA | DBMS | FLAT  
**Prerequisites:** [DBMS Fundamentals](../dbms/dbms-fundamentals.md), [Cache Memory](../coa/cache-memory.md), [Finite Automata and Regular Languages](../flat/finite-automata-regular-languages.md)  
**Exam Importance:** High  
**Last updated:** 2026-05-12  
**Sources:** `raw/CST308-QP (1).pdf`, `raw/CST308-QP-1.pdf`, `raw/CST308-QP-2.pdf`, `raw/CST308-QP-3.pdf`, `raw/CSE Comprehensive QBANK April 2018 - Kerala Notes.pdf`

## Summary

This source page tracks the previous-year question papers used to build the grouped solved sheet. The CST308 papers map cleanly to the core Computer Science buckets, while the April 2018 Kerala Notes paper also contains mathematics, engineering graphics, mechanics, software engineering, and environmental questions outside the configured buckets.

## Coverage

| Source | Exam session | Questions | Ingest status |
|---|---:|---:|---|
| `CST308-QP (1).pdf` | April 2025 | 50 | Covered |
| `CST308-QP-1.pdf` | June 2023 | 50 | Covered |
| `CST308-QP-2.pdf` | May 2024 | 50 | Covered |
| `CST308-QP-3.pdf` | June 2022 | 50 | Covered |
| `CSE Comprehensive QBANK April 2018 - Kerala Notes.pdf` | April 2018 | 50 | Covered |

Total attended questions: **250**.

## Key Takeaways

> **[EXAM_TIP]** The CST308 papers are highly patterned: DS, OS, COA, DBMS, and FLAT usually appear as consecutive blocks of ten questions each.

> **[EXAM_TIP]** Cache mapping, paging, scheduling, normalization, transaction serializability, and finite automata closure properties recur across years.

> **[EXAM_TIP]** Some papers contain defective or ambiguous MCQs. The solved sheet preserves those defects instead of forcing an incorrect option.

## Exam-Focused Claims

1. FIFO page replacement can show Belady's anomaly; LRU and optimal replacement do not.
2. BCNF implies 3NF, 2NF, and 1NF, but a 3NF relation need not be in BCNF.
3. Regular languages are closed under union, concatenation, Kleene star, complement, and intersection.
4. CFLs are closed under union, concatenation, and Kleene star, but not under arbitrary intersection or complement.
5. Cache mapping questions reduce to block size, number of lines, number of sets, tag bits, index bits, and offset bits.
6. Pipeline timing questions commonly use `n + k - 1` cycles for `n` instructions in a `k`-stage pipeline when no stalls are present.
7. SQL aggregation questions often test whether `WHERE`, `GROUP BY`, and `HAVING` are being applied in the correct order.

## Cross-References

- Cache and memory hierarchy questions connect to [Cache Memory](../coa/cache-memory.md) and [DBMS Indexing and Buffering](../dbms/indexing-and-buffering.md).
- Paging, TLB, and virtual memory questions connect OS memory management to [COA Memory Hierarchy](../coa/memory-hierarchy.md).
- Automata closure and grammar questions connect to [Finite Automata and Regular Languages](../flat/finite-automata-regular-languages.md), [Context-Free Languages and PDA](../flat/context-free-languages-pda.md), and [Chomsky Hierarchy and Closure](../flat/chomsky-hierarchy-and-closure.md).
- Normal forms and dependency questions connect to [Normalization](../dbms/normalization.md).
