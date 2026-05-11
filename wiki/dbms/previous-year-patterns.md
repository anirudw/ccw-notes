# DBMS Previous Year Patterns

**Subject:** DBMS  
**Prerequisites:** [Relational Model](relational-model.md), [ER Model and Keys](er-model-and-keys.md), [SQL and Query Languages](sql-and-query-languages.md), [Normalization](normalization.md), [Transactions and Security](transactions-and-security.md)  
**Exam Importance:** High  
**Last updated:** 2026-05-12  
**Sources:** [Previous Year Question Papers](../sources/source-previous-year-question-papers.md)

## Summary

The DBMS PYQs focus on relational definitions, ER mapping, SQL query meaning, normal forms, functional dependencies, keys, indexing, B+ trees, transactions, locking, and recovery.

## High-Yield Claims

> **[EXAM_TIP]** BCNF implies 3NF, 2NF, and 1NF. The reverse is not guaranteed.

> **[EXAM_TIP]** For normal-form questions, first find candidate keys, then classify each FD by whether its left side is a superkey and whether the right side is prime.

> **[CONNECTION]** B+ trees and hashing connect DBMS indexing to DS trees and hashing, while buffer pages connect to [COA Cache Memory](../coa/cache-memory.md).

## Recurring PYQ Areas

- Relational model: relation, tuple, attribute, domain, degree, schema, instance.
- Keys and ER mapping: candidate key, primary key, foreign key, many-to-many mapping tables.
- SQL: `GROUP BY`, `HAVING`, `LIKE`, `DELETE`, `CREATE`, nested `NOT IN`, aggregate query interpretation.
- Normalization: 1NF, 2NF, 3NF, BCNF, partial and transitive dependency.
- Indexing: dense index, B+ tree access count, B-tree direct access.
- Transactions: ACID, serializability, lost update, two-phase locking, recovery.

## Solved Coverage

See [Previous Year Questions - Solved and Grouped](../problems/previous-year-questions-solved.md#dbms) for all 47 DBMS PYQ entries.
