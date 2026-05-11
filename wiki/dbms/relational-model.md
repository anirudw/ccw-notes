# Relational Model

**Subject:** DBMS
**Prerequisites:** [DBMS Fundamentals](dbms-fundamentals.md)
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [DBMS Comprehensive Study Materials - Kerala Notes](../sources/source-dbms-comprehensive-study-materials-kerala-notes.md)

## Definition

The relational model represents data as relations. In RDBMS terminology, a relation is a table, a tuple is a row, and an attribute is a column.

## Core Terms

| Term | Meaning |
| --- | --- |
| Relation | Table. |
| Tuple | Row or record. |
| Attribute | Column or property. |
| Domain | Set of possible values for an attribute. |
| Cardinality | Number of tuples in a relation, in many relational-model MCQs. |
| Schema | Logical design/structure of the database. |
| Instance | Snapshot of stored data at a given time. |
| Subschema | External view used by an application/user group. |

> **[EXAM_TIP]** The source's final MCQ asks for "logical design" and "snapshot at a given time": answer is schema and instance.

## Constraints

Entity integrity requires a primary key to be non-null. Referential integrity requires foreign-key values in the referencing relation to match key values in the referenced relation, or be null if the schema permits.

## Operations

Relational algebra is procedural and returns relations as output. Relational calculus is non-procedural: it specifies what result is needed without prescribing a step-by-step evaluation strategy.

Projection selects columns. Cartesian product is a binary operation that combines attributes from two relations.

> **[CONNECTION]** Relation storage and page access connect to [Indexing and Buffering](indexing-and-buffering.md), which in turn connects to COA [Cache Memory](../coa/cache-memory.md).
