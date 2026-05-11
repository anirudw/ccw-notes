# Chomsky Hierarchy and Closure

**Subject:** FLAT
**Prerequisites:** [Finite Automata and Regular Languages](finite-automata-regular-languages.md), [Context-Free Languages and PDA](context-free-languages-pda.md)
**Exam Importance:** High
**Last updated:** 2026-05-12
**Sources:** [FLAT Comprehensive Study Materials - Kerala Notes](../sources/source-flat-comprehensive-study-materials-kerala-notes.md)

## Hierarchy

The usual containment chain is:

```text
Regular subset CFL subset CSL subset Recursive subset R.E.
```

Associated machines:

| Class | Grammar type | Machine |
| --- | --- | --- |
| Regular | Type 3 | Finite automaton |
| Context-free | Type 2 | Pushdown automaton |
| Context-sensitive | Type 1 | Linear bounded automaton |
| Recursively enumerable | Type 0 | Turing machine |

## Closure Highlights

| Class | Union | Intersection | Complement |
| --- | --- | --- | --- |
| Regular | Yes | Yes | Yes |
| CFL | Yes | No | No |
| DCFL | No in general | No in general | Yes |
| CSL | Yes | Yes | Yes |
| Recursive | Yes | Yes | Yes |
| R.E. | Yes | Yes | No |

> **[EXAM_TIP]** Closure tables are high-yield. Most trick questions ask you to separate CFL from regular/CSL closure behavior.

## Countability

- Finite automata, grammars, and Turing machines are countable as descriptions.
- The set of all languages over a nonempty finite alphabet is uncountable.

> **[DERIVATION]** The uncountability result follows by identifying languages over `Sigma` with subsets of `Sigma*`. Since `Sigma*` is countably infinite, its power set is uncountable.
