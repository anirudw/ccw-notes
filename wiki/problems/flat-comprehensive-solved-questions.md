# FLAT Comprehensive Solved Questions

**Subject:** FLAT
**Prerequisites:** [Finite Automata and Regular Languages](../flat/finite-automata-regular-languages.md), [Context-Free Languages and PDA](../flat/context-free-languages-pda.md), [Turing Machines and Decidability](../flat/turing-machines-decidability.md)
**Exam Importance:** High
**Last updated:** 2026-05-12
**Sources:** [FLAT Comprehensive Study Materials - Kerala Notes](../sources/source-flat-comprehensive-study-materials-kerala-notes.md)

## Coverage Audit

Total covered answer-key entries: 128.

- Chapter 1: 46 entries = 23 Level 1 + 23 Level 2.
- Chapter 2: 32 entries = 19 Level 1 + 13 Level 2.
- Chapter 3: 50 entries = 27 Level 1 + 23 Level 2.
- Visible question prompts: 126. Chapter 3 Level 1 Q25 and Q26 have answer-key entries, but their prompts are absent from the rendered PDF.

> **[EXAM_TIP]** This source has several answer-key and OCR defects. Rows marked "corrected" should be revised from the corrected answer here, not from the PDF key.

## Chapter 1 - Finite Automata and Regular Sets

### Level 1

| ID | Question | Correct answer |
| --- | --- | --- |
| C1-L1-01 | What closure properties does the class of regular sets have? | (d) All listed statements are acceptable: finite union, finite intersection, and some infinite unions preserve regularity. |
| C1-L1-02 | What can happen to the number of states when an NFA is converted to an equivalent DFA? | (d) It sometimes remains the same; in general it can grow up to `2^n`. |
| C1-L1-03 | What is the tightest common classification of every finite language? | (a) Regular language. |
| C1-L1-04 | Which statement about the class of finite automata is correct? | (a) Finite automata are countable/effectively enumerable. |
| C1-L1-05 | How many states are needed for the minimal FA over `{0,1}*` whose last two symbols are the same? | (b) 5 states. |
| C1-L1-06 | Strings over `{0,1}` with fixed-position constraints from the left and right are best classified as what? | Corrected: (a) Regular set. The source marks a broader class, but fixed finite-position constraints are regular. |
| C1-L1-07 | How many states are needed for a minimal DFA acting as a binary mod-3 counter? | (a) 3 states. |
| C1-L1-08 | How many states are needed for strings whose fourth symbol from the right is `1`? | (d) 16 states. |
| C1-L1-09 | Which regular expression denotes binary strings with no two consecutive `1`s? | (b) `(0+10)*(epsilon+1)`. |
| C1-L1-10 | How many states are needed for binary strings whose integer value is divisible by 4? | (b) 3 states in the minimized remainder/suffix DFA. |
| C1-L1-11 | What regular expression describes strings with at least two consecutive `0`s? | (b) Intended form: `(0+1)*00(0+1)*`. |
| C1-L1-12 | Which expression generates strings over `a,b` with even occurrences of substring `ab`? | (c) Source answer. |
| C1-L1-13 | What does the given transition diagram recognize? | (b) Not ending with `10` according to the source diagram solution. |
| C1-L1-14 | Which regular expressions denote binary strings not containing `000` as a substring? | (a) and (b). |
| C1-L1-15 | How many states are needed for `(a+b)*abb`? | (b) 4 states. |
| C1-L1-16 | What language is represented by `(0*011*100*)* union (1*100*011*)*`? | (c) Strings with the same number of disjoint appearances of `10` and `01`. |
| C1-L1-17 | Which expression defines strings over `{a,b}` with at least one substring `ab`? | Corrected: (c) `(a*b*)*ab(a*b*)*`; the PDF key says all choices, but several choices overgenerate or undergenerate. |
| C1-L1-18 | How many states are needed for `(0+1)*(00+11)`? | (c) 5 states. |
| C1-L1-19 | What is `(aa)* + a(aa)* + aaaaa*a*` equivalent to? | (a) `(a+aa+aaa)*`, i.e. `a*`. |
| C1-L1-20 | What is the complement of `{a^n b^n : n != 100}`? | Corrected: context-free/DCFL but not regular. The PDF marks context-sensitive, which is only a broader class. |
| C1-L1-21 | If `p` is prime and `a^(p-1) = r mod p`, what is `r`? | (c) `1`, by Fermat's little theorem when `p` does not divide `a`. |
| C1-L1-22 | What is the expression for strings over `{0,1}` starting with `00` and ending with `11`? | (b) Intended form: `00(0+1)*11`. |
| C1-L1-23 | What machine class accepts `{ww^R : w in (a+b)*}` among the listed options? | (d) Multitape/multiheaded Turing machine; a PDA would also accept palindromes, but PDA is not listed. |

### Level 2

| ID | Question | Correct answer |
| --- | --- | --- |
| C1-L2-01 | Which statement about minimal finite automata is true? | (a) Even number of `0`s and even number of `1`s needs 4 states. |
| C1-L2-02 | Which statement about large fixed-position DFAs is true? | (a) The 1000th-symbol-from-right language needs `2^1000` states. |
| C1-L2-03 | Does the given Mealy machine have an equivalent Moore machine? | (d) Yes; Mealy and Moore machines are equivalent in expressive power. |
| C1-L2-04 | Which statement about Moore, Mealy, and two-way finite automata is false? | (d) None of the listed definitions is false. |
| C1-L2-05 | What is the DFA state bound after converting an `n`-state NFA? | (d) At most `2^n` DFA states. The PDF misnumbers this as another Q06. |
| C1-L2-06 | Which statement about formal-language descriptions is true? | (c) A language description need not use the particular symbol `epsilon`; another notation can denote the empty string. |
| C1-L2-07 | What is a regular expression for strings over `{0,1}` with no consecutive `0`s? | (a) `(1+01)*(epsilon+0)`. |
| C1-L2-08 | Strings where every 7-symbol block has at least two `0`s and three `1`s form what kind of set? | (b) Infinite regular set. |
| C1-L2-09 | How many states are needed for base-3 strings congruent to 0 mod 7 and 0 mod 5? | Corrected: (a) 35 states, using modulo `lcm(7,5)`. The PDF key incorrectly points to "none". |
| C1-L2-10 | How many states are needed for strings not containing substring `0001`? | (a) 5 states. |
| C1-L2-11 | What language is accepted by the given FA diagram? | (b) `{(10)^n : n > 0}` according to the source diagram solution. |
| C1-L2-12 | What happens when that FA is given input `111`? | (c) It is rejected by moving to the dead state. |
| C1-L2-13 | How many states are needed for binary strings starting with `1` and congruent to 0 mod 29? | (d) 31 states. |
| C1-L2-14 | Which regular expression is not equivalent to the others? | (c). |
| C1-L2-15 | How should `{ww : w in (0+1)* and length(w)<100000}` be ordered by language class? | (a) Finite subset, hence regular, CFL, and recursive. |
| C1-L2-16 | Which listed language is non-regular? | Source-intended: (b). As printed, this row has OCR/source duplication; the unbounded intended version is non-regular. |
| C1-L2-17 | Which statement about `L1={0^p1^q}`, `L2={0^p1^q : p=q}`, `L3={0^p1^q0^r : p=q=r}` is not true? | Corrected: (c) is not true because `L3` is not context-free. |
| C1-L2-18 | What is true of `L1={www : length(w)<3000}` and `L2={a^n b^m : m>=2000n}`? | (b) `L1` is regular; `L2` is CFL but not regular. |
| C1-L2-19 | Which regular-expression identities are valid? | (c) (ii) and (iii) are valid; (i) is not. |
| C1-L2-20 | How many states are needed for the source expression involving `(a+epsilon)`? | Source answer: 3 under the source's partial-DFA convention. A complete DFA may need a dead state depending on the exact expression. |
| C1-L2-21 | How many states are needed when `#0` is divisible by 300 and `#1` by 200? | (c) 60000 states. |
| C1-L2-22 | Which statement about formal languages is correct? | (b) The set of all languages is uncountable. |
| C1-L2-23 | What is the transition function type for the epsilon-transition graph question? | Corrected concept: extended NFA transition maps `Q x Sigma*` to `2^Q`; the source key marks (c) because nondeterminism requires sets of possibilities. |

## Chapter 2 - Context-Free Languages and Pushdown Automata

### Level 1

| ID | Question | Correct answer |
| --- | --- | --- |
| C2-L1-01 | What can be said about the intersection of two CFLs? | (b) May be CFL; also (d) it is always context-sensitive under the usual hierarchy. |
| C2-L1-02 | Which statements about CFLs are true? | (b) Union of two CFLs is CFL; (d) complement of a CFL is recursive/context-sensitive in the source convention. |
| C2-L1-03 | Which of `L1={1^n0^n1^n0}` and `L2={a^n b^k : n<k<2n}` is context-free? | Corrected: (c) `L2` is CFL but `L1` is not. The PDF answer letter conflicts with its own explanation. |
| C2-L1-04 | What language is generated by `S->AB`, `A->aA/a`, `B->bBc/epsilon`? | (d) None of the listed choices exactly, because `B` can derive `epsilon`. |
| C2-L1-05 | Recursive sets, CFLs, and R.E. sets are all closed under which operation? | (d) Union. |
| C2-L1-06 | CFL is not closed under which operations? | (d) Intersection, complement, and difference. |
| C2-L1-07 | Which language cannot be accepted by any DPDA? | (b) Unmarked palindromes `{x : x=rev(x)}`. |
| C2-L1-08 | What is a language accepted by an LBA called? | (c) Context-sensitive language. |
| C2-L1-09 | Which determinism statement is correct? | (b) Deterministic and nondeterministic PDAs are not equivalent in power. |
| C2-L1-10 | Which statement about nondeterminism is incorrect? | (b) DPDA and NPDA are not equivalent, so saying they are equivalent is incorrect. |
| C2-L1-11 | Which machine accepts `0* union {0^n1^n} union {0^n1^(2n)}`? | (c) PDA, but not DPDA in the source's intended classification. |
| C2-L1-12 | Which statement about PDA acceptance is correct? | (d) PDA acceptance by final state and by empty store are equivalent models for CFLs. |
| C2-L1-13 | For palindromes `{ww^R}`, which statement is correct? | (c) Over a one-symbol alphabet the language is regular and accepted by an NFA. |
| C2-L1-14 | If a CFL over alphabet `{a}` is generated by a CFG, what can be said? | (d) It is regular and has a regular expression. |
| C2-L1-15 | What is true of `L={ww : w in Sigma*}`? | (a) It is context-sensitive but not context-free. |
| C2-L1-16 | What is true of `L={a^i b^j a^i b^j : i,j>1}`? | (c) It models matching parameter counts; it is CSL and not CFL. |
| C2-L1-17 | Which statement about the two ratio languages and their union is false? | (d) The union is not DCFL in the source's intended example. |
| C2-L1-18 | Which statement about `L1={a^n b^n c^i}` and `L2={a^m b^j c^j}` is false? | (d) Their union is inherently ambiguous, so "not inherently ambiguous" is false. |
| C2-L1-19 | Which statement about linear grammars is correct? | (a) Not every CFL has a linear grammar. |

### Level 2

| ID | Question | Correct answer |
| --- | --- | --- |
| C2-L2-01 | What accepts the long palindrome/copy-style language in the source? | (d) Multitape, multiheaded Turing machine. |
| C2-L2-02 | For `L` = strings not containing `101`, and the pumping lemma statement, which option is correct? | Corrected: (c) Both statements are true: `L` is regular and satisfies the pumping lemma. |
| C2-L2-03 | Given arbitrary CFG `G1` and LR(k) grammar `G2`, which statement is correct? | (d) If `L` is DCFL, then `L$` is generated by some LR(k) grammar. |
| C2-L2-04 | Which statement about DPDAs and empty-store acceptance is correct? | (c) If `L` is DCFL, then `L$` can be generated by some LR(k) grammar. |
| C2-L2-05 | Which statement about NPDA, 2-way PDA, and 2-stack PDA power is false? | (d) It is false that their powers are not ordered as intended; 2-stack PDA reaches TM power. |
| C2-L2-06 | Which statement about CNF, GNF, and operator grammars is false? | (d) `S -> a` is simultaneously CNF, GNF, and operator-grammar compatible. |
| C2-L2-07 | Which Chomsky-hierarchy statement is true? | Corrected: none of the printed options is true; regular grammars can generate every finite language. The PDF marks (d), which is false. |
| C2-L2-08 | Given two PDAs for `L1` and `L2`, which statement is false? | Corrected: as printed, (c) and (d) are false because CFLs are closed under concatenation but not complement. The source focuses on (d). |
| C2-L2-09 | Which statement about `L1={a^n b^(2n)}` and `L2={c a^n b^n}` is false? | (c) `L1 union L2` is accepted by a DPDA because the leading `c` disambiguates. |
| C2-L2-10 | Which statement about `L1={ww^R}`, non-palindromes, and `L3={wxw^R}` is false? | (d) They are not all inherently ambiguous. |
| C2-L2-11 | Which statement about regular sets `R1`, `R2`, arbitrary CFL `L1`, and DCFL `L2` is false? | Corrected: at least (d) is false because equivalence of regular sets is decidable; as printed, (c) is also suspect due `R1=epsilon*`. |
| C2-L2-12 | Which bounded-stack-machine statement is false? | Source-inconsistent. Correct concept: constant-bounded stack gives only regular languages; unbounded input-dependent stack can accept CFLs. |
| C2-L2-13 | Which statement about inverse homomorphism of `L1={a^n b^(2n)}` is false? | (c) CFLs are closed under inverse homomorphism, so `L2` is CFL. |

## Chapter 3 - Turing Machines, CSLs, Recursive and R.E. Sets

### Level 1

| ID | Question | Correct answer |
| --- | --- | --- |
| C3-L1-01 | To evaluate C expressions without function calls, which resource is mandatory? | Source answer: (b) two stacks. Concept note: expression parsing/evaluation is stack-based; the source wording is loose. |
| C3-L1-02 | If `P=NP`, which statement follows? | (c) Both listed closure/equality consequences are intended. |
| C3-L1-03 | Recursive sets are safely closed under which listed operation? | (d) Inverse homomorphism. Also closed under Kleene star under standard definitions; arbitrary erasing homomorphism/substitution needs care. |
| C3-L1-04 | Classify `L1={<M>: L(M) has a word of length <1000}` and `L2={<M>: M accepts a word within 1000 steps}`. | Corrected concept: `L1` is R.E. but not decidable in general; `L2` is recursive/decidable. |
| C3-L1-05 | What accepts the grammar `S -> aSa | bSb | d`? | (a) All listed stronger machines in the chain can accept it; it is a deterministic CFL. |
| C3-L1-06 | What accepts the language with equal numbers of `a`s and `b`s? | (a) It is accepted by the listed machine hierarchy; the source orders them as TM, LBA, PDA, DPDA. |
| C3-L1-07 | What does a 2DFA with unlimited writable input tape become? | (c) LBA. |
| C3-L1-08 | What Chomsky type is every finite set accepted by a finite automaton? | (d) Type 3, regular. |
| C3-L1-09 | Which language classes are closed under complement? | (b) CSL and (c) recursive sets. |
| C3-L1-10 | What language is accepted by the given Turing machine diagram? | (c) Source diagram solution gives the `0^n 1 0^n 1`-style language. |
| C3-L1-11 | What is the tightest class of that diagram language? | Corrected: CFL/DCFL, not regular, if the Q10 language is `0^n 1 0^n 1`. The PDF marks regular inconsistently. |
| C3-L1-12 | Which objects can be effectively enumerated? | (d) Finite automata can be effectively enumerated. |
| C3-L1-13 | Which complexity statement implies `P=NP`? | (c) If every problem in NP is NP-complete, then `P=NP`. |
| C3-L1-14 | Which listed problems are undecidable? | Corrected: (c) emptiness of CSLs and (d) emptiness of R.E. sets are undecidable. |
| C3-L1-15 | Which collections are uncountable? | (d) All listed power sets are uncountable. |
| C3-L1-16 | Which listed problem is not decidable? | (d) Universality of a CFL. |
| C3-L1-17 | What is the union of regular sets and CSLs as classes? | (b) Countably infinite; regular languages are contained in CSLs. |
| C3-L1-18 | Given DFA `M1` and NFA `M2`, what is decidable? | (b) Whether their regular languages are equal. |
| C3-L1-19 | For DCFL/LR(k)/2DFA languages, which statement is correct in the source? | Source answer: (a) no algorithm for emptiness of intersection of two DCFL-style languages. Mark for review against syllabus. |
| C3-L1-20 | For a PDA language `L1`, which statement is correct? | (a) `L1 = empty` is decidable. |
| C3-L1-21 | Are arbitrary C and Java programs necessarily algorithms? | (d) Neither is necessarily an algorithm. |
| C3-L1-22 | What is decidable about an assignment statement in an arbitrary C program? | (b) Liveness/deadness style questions are undecidable in general. |
| C3-L1-23 | Which graph-coloring statement is correct? | (d) Graph coloring is decidable but computationally intractable/NP-complete in general. |
| C3-L1-24 | For recursive `L` accepted by an LBA and homomorphism `h`, what is correct? | (c) The emptiness of `h(L)` tracks the emptiness of `L`; for LBA descriptions this is undecidable. |
| C3-L1-25 | Prompt absent from rendered PDF; only the answer-key row is present. | Source answer: (d). Solution says the listed machines describe R.E. sets, so halting/equivalence/universality questions are undecidable except the stated universal-simulation fact. |
| C3-L1-26 | Prompt absent from rendered PDF; only the answer-key row is present. | Source answer: (d). Solution says the machines are variations of standard Turing machines and accept exactly the R.E. sets. |
| C3-L1-27 | What is decidable about the set of Turing machines describing Hamiltonian-cycle problems? | Source answer: (c). Concept: Hamiltonian cycle itself is decidable; Rice-style nontrivial TM-language properties are undecidable. |

### Level 2

| ID | Question | Correct answer |
| --- | --- | --- |
| C3-L2-01 | What language does the displayed single-tape Turing machine accept? | Corrected from rendered table: (d) all binary strings, since `(0+1)*01(0+1)* union 1*0* = (0+1)*`. The source key says (a), but the table contradicts it. |
| C3-L2-02 | Match the grammars with their classifications. | (d) `P-1, Q-2, R-3, S-6` according to the source key. |
| C3-L2-03 | Which closure statement is true? | (c) Regular sets are closed under intersection, but CFLs are not. |
| C3-L2-04 | In the linked TM-language question with `L_n=empty` and `L_m=Sigma*`, which statement is correct? | Source answer: (a). The source wording is ambiguous because the languages are described semantically but supplied by TMs. |
| C3-L2-05 | What can Rahim determine about the complement of `L_n`? | Corrected concept: if `L_n=empty`, then its complement is `Sigma*`, which is regular/recursive/R.E.; the printed options are defective. |
| C3-L2-06 | What is the standard relationship among `P`, `NP`, `PSPACE`, and `EXPTIME`? | (a) `P subseteq NP subseteq PSPACE subseteq EXPTIME`; strictness of some inclusions is not fully known. |
| C3-L2-07 | Which statement about TMs and finite-state machines is false? | (c) Both (a) and (b) are false/unsafe as stated. A TM's extra power comes from unbounded memory, not merely a halt state. |
| C3-L2-08 | Which statement is false? | (d) Every regular expression denotes a regular set, so the statement saying otherwise is false. |
| C3-L2-09 | What does the displayed TM accept? | (c) `(0+1)+`, according to the source diagram solution. |
| C3-L2-10 | What class is the language accepted by that halting TM? | (b) Recursive set. |
| C3-L2-11 | What is `L1` in the linked question? | (a) Regular and not finite, under the source's selected branch `L1=(0+1)*`. |
| C3-L2-12 | What is `L2` if both `L2` and its complement are R.E.? | (d) R.E.; more precisely it is recursive/decidable. |
| C3-L2-13 | What does the displayed TM over `{a,b}` accept? | (d) Even-length strings over `{a,b}`. |
| C3-L2-14 | Which PCP simulation statement is correct? | (a) PCP can be simulated through intersection of two deterministic CFL-style languages in the source result. |
| C3-L2-15 | For CSG/LBA languages, which statement is correct? | (a) Emptiness, finiteness, infiniteness, and universality questions are undecidable for CSL descriptions. |
| C3-L2-16 | For a deterministic TM language and a two-stack PDA language, which statement is correct? | (c) It is possible that both languages are `Sigma*`. |
| C3-L2-17 | Which CFG/program-language statement is correct? | (b) Ambiguity of a CFG is undecidable. |
| C3-L2-18 | Can one always determine whether two arbitrary DPDAs accept a common string? | (d) Source answer: no, the intersection-emptiness question is undecidable in this setting. |
| C3-L2-19 | Is exhaustive testing of an arbitrary software package decidable? | (b) Exhaustive testing is undecidable in general. |
| C3-L2-20 | Does decidability of each regular language imply decidability of an arbitrary infinite union of regular languages? | Corrected: (d) None of the absolute statements is right; some infinite unions are decidable and some can define undecidable languages. |
| C3-L2-21 | If `L1` is R.E. but not recursive, what can be said? | (b) It is partially decidable and (c) not decidable; if forced to one option, use (c) for "not decidable". |
| C3-L2-22 | Given nondeterministic and deterministic Turing machines, which statement is correct? | (d) Both language descriptions suffer from halting/emptiness undecidability in general. |
| C3-L2-23 | Under epsilon-free homomorphism, which membership statement is correct? | Corrected: membership for R.E. languages may be undecidable, while membership for CSL, CFL, and regular languages is decidable. The printed option has a wording error. |

## Source Defects To Remember

- Chapter 1 Level 2 has a numbering defect: the NFA-to-DFA question is printed as another Q06 but belongs to Q05.
- Chapter 3 Level 1 Q25 and Q26 prompts are absent from the rendered PDF; only answer-key entries exist.
- Several PDF answer keys conflict with standard FLAT facts; corrected rows are marked explicitly.
