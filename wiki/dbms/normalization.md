# Normalization

**Subject:** DBMS
**Prerequisites:** [Relational Model](relational-model.md), [ER Model and Keys](er-model-and-keys.md)
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [DBMS Comprehensive Study Materials - Kerala Notes](../sources/source-dbms-comprehensive-study-materials-kerala-notes.md)

## Definition

Normalization organizes relational schemas to reduce redundancy and avoid insertion, deletion, and update anomalies.

## Exam-Focused Forms

- 2NF removes partial dependency on a candidate key.
- 3NF reduces transitive dependency problems and is often treated as adequate for normal RDBMS design.
- BCNF is stricter than 3NF: every non-trivial functional dependency must have a superkey on the left.
- 4NF handles non-trivial multivalued dependencies; the determinant must be a superkey.
- 5NF handles certain join dependency issues.

> **[EXAM_TIP]** The DBMS source says 3NF is usually adequate for normal RDBMS design. This is a common university-exam answer, even though BCNF/4NF can be required for stricter designs.

## Redundancy

Storing the same data in more than one place wastes storage and can cause inconsistency when one copy changes and another does not.
