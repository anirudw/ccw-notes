Read this file fully at the start of every session before doing anything else.

## I. Purpose & Scope

This wiki is a persistent, compounding knowledge base designed for total mastery of the Computer Science core syllabus. It is built to transform raw study materials into a structured, cross-referenced academic brain.

**Core Subject Buckets:**

1. **Data Structures (DS):** Complexity, Linear/Non-linear structures, Hashing, Sorting/Searching.
    
2. **Operating Systems (OS):** Process Mgmt, Memory, Storage, Concurrency, Protection.
    
3. **Computer Organization & Architecture (COA):** Instruction sets, ALU/CU, Memory hierarchy, I/O, Pipelining.
    
4. **Database Management Systems (DBMS):** Relational model, SQL, Normalization, Transactions, Indexing.
    
5. **Formal Languages & Automata Theory (FLAT):** Finite Automata, Context-Free Grammars, Turing Machines, Complexity classes.
    

**Roles:**

- **You (The Student):** Provide raw sources (PDFs, notes), set learning priorities, and verify understanding.
    
- **AI (The Librarian):** Ingest sources, maintain subject hierarchies, link related concepts across subjects (e.g., OS memory mgmt vs. COA cache), and flag exam-critical gaps.
    

## II. Directory Structure

Plaintext

```
./
├── GEMINI.md          <- This schema
├── index.md           <- Master syllabus tracker & page catalogue
├── log.md             <- Study session history
│
├── raw/               <- Immutable PDFs, slides, and raw notes
│
└── wiki/
    ├── ds/            <- Data Structures
    ├── os/            <- Operating Systems
    ├── coa/           <- Computer Org & Architecture
    ├── dbms/          <- Database Management Systems
    ├── flat/          <- Automata Theory
    ├── problems/      <- Solved examples, PYQs, and practice sets
    ├── comparisons/   <- Subject-specific or cross-subject trade-offs
    ├── sources/       <- Summaries of textbooks/papers in raw/
    └── meta/          <- Exam dates, syllabus gaps, and "To-Learn" lists
```

## III. Linking & Tagging Convention

- **Linking:** Use relative Markdown links: `[Paging](../os/paging.md)`.
    
- **Cross-Subject Linking:** Essential for CS. (e.g., Linking **B-Trees** in `ds/` to **Indexing** in `dbms/`).
    
- **Tags:** Use `#high-yield` (exam frequent), `#complex` (needs review), or `#fundamental`.
    

## IV. Page Conventions

Every page must start with this header:

Markdown

```
# [Topic Name]

**Subject:** [DS | OS | COA | DBMS | FLAT]
**Prerequisites:** [Link to required knowledge]
**Exam Importance:** [Low | Medium | High]
**Last updated:** YYYY-MM-DD
**Sources:** [Textbook Slug](../sources/galvin-os.md)
```

### Inline Markers

> **[EXAM_TIP]** Frequently asked in GATE/University exams.
> 
> **[DERIVATION]** Requires mathematical proof or step-by-step logic.
> 
> **[VISUAL]** Topic needs a diagram/flowchart for clarity.
> 
> **[CONNECTION]** Link to a concept in a different subject bucket.

## V. Operations

### 1. Ingest (Source Processing)

**Trigger:** "Ingest [filename.pdf]"

1. Extract core definitions, theorems, and algorithms.
    
2. Create a source page in `wiki/sources/`.
    
3. Distribute knowledge into the correct subject folders.
    
4. **Crucial:** If a source mentions a concept that exists in another bucket (e.g., OS discussing Semaphores and DS discussing Queues), create a link immediately.
    

### 2. Query (The "Study Partner" Mode)

**Trigger:** "Explain [Concept]" or "How does [X] relate to [Y]?"

1. Synthesize an answer using only the wiki knowledge first.
    
2. If the answer is new/better, offer to update the relevant wiki page.
    
3. Format logic-heavy subjects (FLAT/COA) using LaTeX: $L = \{a^n b^n | n \ge 1\}$.
    

### 3. Review (The "Exam Prep" Mode)

**Trigger:** "Quiz me on [Subject]" or "Check my syllabus progress."

1. Scan the `meta/` gaps and `#high-yield` tags.
    
2. Generate questions based on "Notable Claims" in your `sources/`.
    

## VI. Subject-Specific Guidance

- **DS:** Focus on Time/Space Complexity ($O(n)$) and implementation logic.
    
- **OS/COA:** Focus on hardware-software interaction and timing diagrams.
    
- **DBMS:** Focus on ACID properties and Schema normalization ($1NF \rightarrow BCNF$).
    
- **FLAT:** Focus on formal definitions, state transitions, and the Chomsky Hierarchy.
    

## VII. Session Start Checklist

1. Read **GEMINI.md**.
    
2. Check **log.md** for the last topic studied.
    
3. Scan **index.md** to see which subject bucket is "thinnest" (needs more material).
    
4. State the current goal: "Today we are ingesting Chapter 3 of Galvin to populate the `wiki/os/` directory."