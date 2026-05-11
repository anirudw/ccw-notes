# DBMS Fundamentals

**Subject:** DBMS
**Prerequisites:** None
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [DBMS Comprehensive Study Materials - Kerala Notes](../sources/source-dbms-comprehensive-study-materials-kerala-notes.md)

## Definition

A database is an organized collection of data or information that can be accessed, updated, and managed. A DBMS, or Database Management System, is software that stores, modifies, retrieves, secures, and manages that data.

## Core Features

- Minimum data duplication and redundancy.
- Multi-user access with authorization.
- Data integrity and consistency.
- Security for stored data.
- Backup and recovery support.
- User interfaces and query languages.
- ACID support for reliable transactions.

> **[EXAM_TIP]** If the option says "single-user access only," it is not a DBMS feature. The source MCQ is worded badly here.

## Components

- Hardware: disks, memory, and other physical resources.
- Software: DBMS engine and user tools.
- Data: stored information and metadata.
- Data manager: manages DBMS operations.
- Data languages: DDL, DML, DCL, and related command classes.

## Types and Examples

Common database models include relational, hierarchical, network, object-oriented, distributed, centralized, cloud, and NoSQL databases. MySQL, Microsoft Access, and IBM DB2 are DBMS examples.

Google itself is not a DBMS; Google services may use database systems internally.

## Data and Metadata

Metadata is information about data, such as attribute type, size, constraints, and meaning. Data may be text, files, images, audio, video, or other structured/unstructured forms, but relational DBMS exam questions usually model it as tables.

> **[CONNECTION]** DBMS storage depends on hardware concepts from COA [Memory Hierarchy](../coa/memory-hierarchy.md), especially the speed gap between disk, RAM, and cache.
