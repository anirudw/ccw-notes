# DBMS Comprehensive Solved Questions

**Subject:** DBMS
**Prerequisites:** [DBMS Fundamentals](../dbms/dbms-fundamentals.md), [Relational Model](../dbms/relational-model.md), [SQL and Query Languages](../dbms/sql-and-query-languages.md)
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [DBMS Comprehensive Study Materials - Kerala Notes](../sources/source-dbms-comprehensive-study-materials-kerala-notes.md)

## Coverage Audit

Total covered question entries: 108.

- Section A: 56 solved MCQs, numbered 1-56.
- Section B: 52 short Q/A entries, source labels 1-52 with label 4 missing and label 24 repeated once.
- One source answer marker is blank: Section A Q37. The explanation implies ASCII text format, so it is marked as inferred.

> **[EXAM_TIP]** Use this page as the coverage checklist for the PDF. Every source question entry has a row with its question prompt and covered answer/concept.

## Section A - Solved MCQs

| ID  | Question                                                                                                                                        | Covered answer/concept                                                                                                                                                         |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| A01 | What is the full form of DBMS?                                                                                                                  | DBMS stands for Database Management System.                                                                                                                                    |
| A02 | What is a database?                                                                                                                             | A database is an organized collection of data that can be accessed, updated, and managed.                                                                                      |
| A03 | What is DBMS?                                                                                                                                   | A DBMS stores, modifies, and retrieves data.                                                                                                                                   |
| A04 | Who created the first DBMS?                                                                                                                     | Charles Bachman created the first DBMS, Integrated Data Store (IDS).                                                                                                           |
| A05 | Which type of data can be stored in a database?                                                                                                 | Databases can store text, files, image-oriented data, audio, video, and other data forms.                                                                                      |
| A06 | In which format is data stored in a DBMS?                                                                                                       | DBMS data is stored in table format in the relational exam context.                                                                                                            |
| A07 | Which listed option is not a type of database?                                                                                                  | Decentralized is not listed as a standard database type in the source; listed types include hierarchical, network, relational, distributed, cloud, NoSQL, and object-oriented. |
| A08 | Which listed option is not an example of DBMS?                                                                                                  | Google is not itself a DBMS; MySQL, Microsoft Access, and IBM DB2 are DBMS examples.                                                                                           |
| A09 | Which listed option is a feature of DBMS?                                                                                                       | Source issue: "single-user access only" is not a DBMS feature. Correct DBMS features include low redundancy, security, multi-user access, and ACID support.                    |
| A10 | Which listed option is a feature of a database?                                                                                                 | A database feature is a user interface for access.                                                                                                                             |
| A11 | Which listed option is not a function of the database?                                                                                          | Analyzing code is not a database function.                                                                                                                                     |
| A12 | Which listed option is a function of the DBMS?                                                                                                  | DBMS functions include storing data, multi-user access control, and data integrity.                                                                                            |
| A13 | Which listed option is a component of the DBMS?                                                                                                 | DBMS components include data, data languages, data manager, hardware, and software.                                                                                            |
| A14 | What is a set of same-type entities sharing the same attributes called?                                                                         | Entity set means entities of the same type sharing the same properties/attributes.                                                                                             |
| A15 | What is information about data called?                                                                                                          | Metadata means information about data.                                                                                                                                         |
| A16 | What does an RDBMS consist of?                                                                                                                  | An RDBMS consists of a collection of tables.                                                                                                                                   |
| A17 | Which integrity constraint requires referencing attribute values to occur in the referenced relation?                                           | Referential integrity requires referenced key values to exist in the referenced relation.                                                                                      |
| A18 | Which hardware component is most important for DBMS operation?                                                                                  | A high-speed, large-capacity disk is a key DBMS hardware component.                                                                                                            |
| A19 | DBMS acts as an interface between which two parts of an enterprise-class system?                                                                | DBMS acts as an interface between database applications and the database.                                                                                                      |
| A20 | Which language class offers query, insert, delete, and alter tuple operations?                                                                  | DML supports querying, inserting, deleting, and altering tuples/data.                                                                                                          |
| A21 | What is a set of one or more attributes that uniquely identifies a record?                                                                      | A super key is one or more attributes that uniquely identify a record/tuple.                                                                                                   |
| A22 | Which SQL command removes a relation?                                                                                                           | `DROP TABLE` removes a relation/table structure from SQL.                                                                                                                      |
| A23 | Which set must be associated with a weak entity set for it to be meaningful?                                                                    | A weak entity set needs an identifying set to be meaningful.                                                                                                                   |
| A24 | Which SQL command correctly deletes the values in relation `teaches`?                                                                           | `DELETE FROM teaches;` deletes the rows/values in relation `teaches`.                                                                                                          |
| A25 | Which listed language is procedural?                                                                                                            | Relational algebra is procedural.                                                                                                                                              |
| A26 | Which join operation does not preserve non-matched tuples?                                                                                      | Inner join does not preserve non-matched tuples.                                                                                                                               |
| A27 | Which normal form has a relation containing information about a single entity in the source question?                                           | Source answer: 4NF. Exam concept: 4NF deals with non-trivial multivalued dependencies and superkeys.                                                                           |
| A28 | In the SQL hierarchy, the top level consists of what, each containing what?                                                                     | Top hierarchy in the SQL environment/catalog model: catalogs contain schemas.                                                                                                  |
| A29 | What indicates the maximum number of entities involved in a relationship?                                                                       | Maximum cardinality indicates the maximum number of entities involved in a relationship.                                                                                       |
| A30 | Which fixed role can add or remove user IDs?                                                                                                    | `db_accessadmin` handles adding/removing access or user IDs in the source's fixed-role question.                                                                               |
| A31 | Why is `SELECT dept_name, ID, avg(salary) FROM instructor GROUP BY dept_name;` erroneous?                                                       | The grouped SQL query is erroneous because selected `ID` is neither grouped nor aggregated.                                                                                    |
| A32 | Customer folders in filing cabinets are an example of which database model?                                                                     | Filing cabinets organized by customer are treated as a hierarchical database example.                                                                                          |
| A33 | After groups are established, which SQL clause applies predicates using aggregate functions?                                                    | Corrected: after groups are established, SQL applies aggregate predicates in the `HAVING` clause.                                                                              |
| A34 | Which listed item is not a DBMS utility?                                                                                                        | Source issue: explanation says process organization is not a DBMS utility; backup, loading, and file organization are utilities.                                               |
| A35 | What does a foreign key combined with a primary key create?                                                                                     | Corrected: a foreign-key/primary-key pair creates a referential or parent-child relationship between tables.                                                                   |
| A36 | Which DBMS technology maintains transactional integrity and consistency?                                                                        | Locks help maintain transactional integrity and consistency.                                                                                                                   |
| A37 | What is correct about a file produced by a spreadsheet?                                                                                         | Source answer marker is blank; explanation implies spreadsheet output stored as ASCII text format.                                                                             |
| A38 | What is the function of `DELETE FROM r WHERE P;`?                                                                                               | `DELETE FROM r WHERE P;` deletes tuples satisfying condition `P`.                                                                                                              |
| A39 | Which command form resembles `CREATE VIEW`?                                                                                                     | `CREATE TABLE ... AS` resembles `CREATE VIEW ... AS` because both are query-defined.                                                                                           |
| A40 | Under which conditions is an SQL view query updatable?                                                                                          | A view is updatable only under restrictions such as simple selected attributes, one relation, and no grouping/aggregates.                                                      |
| A41 | When is the `ROLLUP` operator used inside `GROUP BY`?                                                                                           | `ROLLUP` groups columns from right to left to compute subtotals.                                                                                                               |
| A42 | What is the best way to represent attributes in a large database in the source question?                                                        | Concatenation is the source answer for representing attributes in a large database.                                                                                            |
| A43 | Which SQL command subset manipulates Oracle structures such as tables?                                                                          | DDL is the SQL subset used to define/manipulate database structures such as tables.                                                                                            |
| A44 | Which SQL function constructs buckets useful for ranking/histograms?                                                                            | `NTILE()` builds buckets useful for ranking/histogram-style grouping.                                                                                                          |
| A45 | Which SQL command can issue multiple `CREATE TABLE`, `CREATE VIEW`, and `GRANT` statements in one transaction?                                  | `CREATE SCHEMA` can issue multiple `CREATE TABLE`, `CREATE VIEW`, and `GRANT` statements in one transaction.                                                                   |
| A46 | Which key is required to handle encrypted data so unauthorized users cannot access it?                                                          | Decryption key is needed to read encrypted data; encryption key is used to encrypt it.                                                                                         |
| A47 | What is the process of viewing a cross-tab with a fixed value of one attribute called?                                                          | Slicing fixes one dimension/attribute value in cube or cross-tab analysis.                                                                                                     |
| A48 | Which normal form is considered adequate for designing a normal RDBMS?                                                                          | 3NF is commonly considered adequate for normal RDBMS design.                                                                                                                   |
| A49 | Which RAID level is popular for log-file storage because of best write performance?                                                             | Source issue: source marks RAID 1; standard "best write performance" answer is RAID 0 when redundancy is ignored.                                                              |
| A50 | Which expression represents a tuple relational calculus query?                                                                                  | Tuple relational calculus query form is `{t \| P(t)}`.                                                                                                                         |
| A51 | Which is the oldest DB model in the source question?                                                                                            | Source answer: network model is the oldest DB model. Verify against syllabus because hierarchical and network models are both early models.                                    |
| A52 | After granting `SELECT` through role `r1`, granting direct `SELECT`, then revoking direct `SELECT` from `SCOTT`, can `SCOTT` query `OE.ORDERS`? | SCOTT can still query `OE.ORDERS` because `SELECT` is still available through role `r1`.                                                                                       |
| A53 | Which schema establishes a top-to-bottom relationship among items?                                                                              | Hierarchical schema establishes a top-to-bottom relationship.                                                                                                                  |
| A54 | What helps minimize block transfers between disk and memory?                                                                                    | Buffering minimizes block transfers between disk and memory.                                                                                                                   |
| A55 | What happens if the same data is stored in two database locations?                                                                              | Duplicate storage wastes space and can cause inconsistency.                                                                                                                    |
| A56 | What are logical design and a data snapshot at a given instant called?                                                                          | Logical design is schema; data snapshot at a given instant is instance.                                                                                                        |

## Section B - Short Questions and Answers

| ID | Question | Covered answer/concept |
| --- | --- | --- |
| B01 | In the relational model, what is cardinality termed as? | Cardinality is the number of tuples. |
| B02 | What kind of language is relational calculus? | Relational calculus is non-procedural. |
| B03 | What is the view of total database content? | Total database content is the conceptual view. |
| B05 | What type of operator is Cartesian product in relational algebra? | Cartesian product in relational algebra is a binary operator. |
| B06 | What is DML provided for? | DML is for manipulation and processing of database data. |
| B07 | What is the SQL `AS` clause used for? | SQL `AS` clause is used for rename/alias operation. |
| B08 | What does ODBC stand for? | ODBC means Open Database Connectivity. |
| B09 | How many levels can database architecture be viewed as? | Database architecture is commonly viewed as three levels. |
| B10 | In a relational model, what are relations termed as? | Relations are tables. |
| B11 | In which language is the database schema written? | Database schema is written using DDL. |
| B12 | What is the external level in database architecture? | External level is the view level. |
| B13 | How are records organized in the hierarchical model? | Hierarchical model organizes records as a tree. |
| B14 | How are attributes represented in an ER diagram? | ER diagram attributes are represented by ellipses. |
| B15 | What must the primary key be for entity integrity? | Entity integrity requires the primary key to be not null. |
| B16 | Which language do application programs use to request data from the DBMS? | Application programs request data from DBMS using DML. |
| B17 | What is a logical schema? | Logical schema describes the entire database. |
| B18 | Related fields in a database are grouped to form what? | Related fields are grouped to form a data record. |
| B19 | Which language is the de facto standard for interfacing application programs with relational database systems? | SQL is the de facto standard interface language for relational database systems. |
| B20 | What is a particular application's view of database data called? | A particular application's view of database data is a subschema. |
| B21 | How is an entity set represented in an ER diagram? | An entity set is represented by a rectangle. |
| B22 | What is a report generator used for? | A report generator prints reports/files on paper. |
| B23 | Which DBMS language component can be embedded in a program? | The DBMS language component embeddable in a program is DML. |
| B24a | What does a relational database developer call a record? | A record is called a tuple. |
| B24b | What does conceptual design involve? | Conceptual design models data independently of a specific DBMS. |
| B25 | What does a subschema express? | A subschema expresses the external view. |
| B26 | What does the SQL `COUNT` function return? | Corrected: SQL `COUNT` returns a numeric count of rows or non-null values, not the values themselves. |
| B27 | What is an advantage of the database-management approach? | Integrated data can be accessed by multiple programs. |
| B28 | What is a DBMS query language designed to support? | DBMS query language supports end users with English-like commands; the source also lists application support fragments. |
| B29 | What can completely define a schema? | Corrected: schema definition is primarily done using DDL; DML manipulates stored data. |
| B30 | Which access method uses key transformation? | Key transformation access method is hashing. |
| B31 | Which SQL statement changes the definition of a table? | SQL `ALTER` changes the definition of a table. |
| B32 | Which ER symbol represents a weak entity set? | A weak entity set is represented by a double rectangle. |
| B33 | Which model uses the SET concept? | SET concept is used in the network model. |
| B34 | What kind of query language is relational algebra? | Relational algebra is a procedural query language. |
| B35 | What key represents the relationship between tables? | The key representing relationship between tables is a foreign key. |
| B36 | Which operation produces a relation with attributes of both `R1` and `R2`? | Cartesian product produces a relation with attributes from both `R1` and `R2`. |
| B37 | What are properties of entities called? | Entity properties are attributes. |
| B38 | When is it better to use files than a DBMS, according to the source? | Source issue: source says files are better when multiple users need access; standard DBMS reasoning says this is when DBMS is better than files. |
| B39 | What is the conceptual model independent of? | Conceptual model is independent of both hardware and software. |
| B40 | What is a relationship between two entities called? | Relationship maintained between two entities is binary. |
| B41 | Which operation is used to select only certain columns of a table? | Projection is used when only certain columns are needed. |
| B42 | Which listed SQL types are valid? | Valid SQL types include `CHARACTER`, `NUMERIC`, and `FLOAT`. |
| B43 | What is the RDBMS terminology for a row? | RDBMS terminology for a row is tuple. |
| B44 | What is the full form of DDL? | DDL means Data Definition Language. |
| B45 | What are advantages of a view? | View advantages include data security, derived columns, and hiding complex queries. |
| B46 | Which expression is legal SQL? | `SELECT NAME FROM EMPLOYEE;` is a legal SQL expression. |
| B47 | What are users who use easy-to-use menus called? | Easy-to-use menu users are naive users. |
| B48 | Which database level is closest to users? | The database level closest to users is the external level. |
| B49 | What is a set of possible data values called? | A set of possible data values is a domain. |
| B50 | Which operations form the basic set for manipulating relational data? | Relational algebra forms the basic operation set for manipulating relational data. |
| B51 | What is another name for a weak entity? | Another name for a weak entity in the source is child. |
| B52 | Which database object does not physically exist? | A view is the database object that usually does not physically exist. |

## Coverage Notes

- The source has no separate B04 entry in the second section.
- The repeated B24 labels are preserved as B24a and B24b so the coverage count remains exact.
- Rows marked "source issue" should be revised from the corrected concept on this page.
