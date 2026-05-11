# Transactions and Security

**Subject:** DBMS
**Prerequisites:** [DBMS Fundamentals](dbms-fundamentals.md), [SQL and Query Languages](sql-and-query-languages.md)
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [DBMS Comprehensive Study Materials - Kerala Notes](../sources/source-dbms-comprehensive-study-materials-kerala-notes.md)

## Transactions

DBMSs support ACID properties to keep data reliable during transactions. Locks are used to maintain transactional integrity and consistency during concurrent access.

> **[CONNECTION]** Concurrency control has a conceptual link to OS process synchronization, though this wiki has not yet ingested the OS semaphore sources.

## Access Control

DBMS security uses authorization, roles, and privileges. The source includes an Oracle-style role example: if `SCOTT` receives `SELECT` through role `r1` and also directly, revoking only the direct grant still leaves role-based access available.

## Roles and Privileges

- `db_accessadmin` is associated with adding or removing access/user IDs in the source question.
- `REVOKE` removes privileges from a user or role, depending on what is named in the statement.

## Encryption

Encryption uses a key to transform readable data into protected ciphertext. Decryption requires the corresponding decryption key, or the same key in symmetric encryption.

> **[EXAM_TIP]** If an MCQ asks which key is needed to read encrypted data, answer decryption key. If it asks which key encrypts the data, answer encryption key.
