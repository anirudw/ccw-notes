# Turing Machines and Decidability

**Subject:** FLAT
**Prerequisites:** [Context-Free Languages and PDA](context-free-languages-pda.md), [Chomsky Hierarchy and Closure](chomsky-hierarchy-and-closure.md)
**Exam Importance:** High
**Last updated:** 2026-05-12
**Sources:** [FLAT Comprehensive Study Materials - Kerala Notes](../sources/source-flat-comprehensive-study-materials-kerala-notes.md)

## Definition

A Turing machine is a formal model of computation with finite control and an unbounded tape. It recognizes recursively enumerable languages. If it halts on every input, it decides a recursive language.

## Core Distinctions

- Recursive language: membership is decidable; the machine halts on all inputs.
- Recursively enumerable language: membership is semidecidable; the machine halts on members but may loop on nonmembers.
- If both a language and its complement are R.E., then the language is recursive.

> **[EXAM_TIP]** "Accepted by a TM" usually means R.E.; "decided by a TM" means recursive.

## Decidable Problems

- Membership for regular languages, CFLs, CSLs, and recursive languages.
- Emptiness for regular languages and CFLs.
- Equivalence for regular languages.
- Finiteness for CFLs.

## Undecidable Problems

- Halting problem.
- Emptiness of R.E. languages.
- Universality of CFLs.
- Most nontrivial semantic properties of Turing-machine languages, by Rice's theorem.
- Ambiguity of a CFG.

> **[CONNECTION]** Undecidability explains why exhaustive software testing cannot be complete in general, while practical testing in OS/DBMS codebases uses bounded approximations.
