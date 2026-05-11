# SQL and Query Languages

**Subject:** DBMS
**Prerequisites:** [Relational Model](relational-model.md)
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [DBMS Comprehensive Study Materials - Kerala Notes](../sources/source-dbms-comprehensive-study-materials-kerala-notes.md)

## Language Classes

- DDL: Data Definition Language; defines schemas and table structures.
- DML: Data Manipulation Language; queries, inserts, deletes, and updates data.
- DCL: Data Control Language; controls privileges and access.
- TCL: Transaction Control Language; manages transaction boundaries.

> **[EXAM_TIP]** Schema definition belongs to DDL. Data retrieval and tuple changes belong to DML.

## SQL Commands and Clauses

| SQL item | Exam meaning |
| --- | --- |
| `DROP TABLE` | Removes the table/relation structure. |
| `DELETE FROM table` | Deletes rows from a table. |
| `ALTER TABLE` | Changes a table definition. |
| `AS` | Renames or aliases an expression/relation. |
| `CREATE SCHEMA` | Can group schema object creation and grants. |
| `CREATE TABLE AS` | Creates a table from a query result. |
| `CREATE VIEW AS` | Defines a virtual relation from a query. |
| `SELECT NAME FROM EMPLOYEE;` | Legal simple SQL query form. |

## Grouping

When a query uses `GROUP BY`, any selected non-aggregated attribute must normally appear in the `GROUP BY` list. Predicates on groups and aggregate results belong in the `HAVING` clause.

> **[EXAM_TIP]** The source marks `WITH` for the post-grouping predicate question, but the standard answer is `HAVING`.

## Views

A view is a virtual table defined by a query. It can hide complex queries, expose derived columns, and support data security by limiting visible data.

An SQL view is usually updatable only under restrictions, such as a simple select list, a single base relation, and no grouping or aggregate computation.

## Query Languages

Relational algebra is procedural. Tuple relational calculus and domain relational calculus are non-procedural. Tuple relational calculus uses a form like `{t | P(t)}`.
