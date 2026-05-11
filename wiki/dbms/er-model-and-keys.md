# ER Model and Keys

**Subject:** DBMS
**Prerequisites:** [Relational Model](relational-model.md)
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [DBMS Comprehensive Study Materials - Kerala Notes](../sources/source-dbms-comprehensive-study-materials-kerala-notes.md)

## Entity-Relationship Model

An entity is a distinct real-world object. An entity set is a set of entities of the same type that share the same attributes.

ER diagram symbols commonly tested:

| Concept | Symbol |
| --- | --- |
| Entity set | Rectangle |
| Attribute | Ellipse |
| Weak entity set | Double rectangle |
| Relationship between two entity sets | Binary relationship |

> **[VISUAL]** ER diagram symbol questions are best revised with a one-page symbol chart.

## Weak Entities

A weak entity depends on an identifying or owner entity set. It is meaningful only when linked to its identifying set.

## Keys

- Super key: one or more attributes that uniquely identify a tuple.
- Candidate key: minimal super key.
- Primary key: selected candidate key used as the main identifier.
- Foreign key: attribute(s) that reference a key in another relation.

> **[EXAM_TIP]** A primary-key/foreign-key pair represents referential linkage between tables. The common exam wording is parent-child or referenced/referencing relationship.

## Cardinality

Maximum cardinality indicates the maximum number of entities that can participate in a relationship. In the relational model, cardinality is also often used for the number of tuples in a relation. Read the question context carefully.
