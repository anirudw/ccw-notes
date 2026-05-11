# Previous Year Questions - Solved and Grouped

**Subject:** DS | OS | COA | DBMS | FLAT  
**Prerequisites:** [DBMS Fundamentals](../dbms/dbms-fundamentals.md), [Cache Memory](../coa/cache-memory.md), [Finite Automata and Regular Languages](../flat/finite-automata-regular-languages.md)  
**Exam Importance:** High  
**Last updated:** 2026-05-12  
**Sources:** [Previous Year Question Papers](../sources/source-previous-year-question-papers.md)

## Coverage Audit

| Bucket | Count |
|---|---:|
| DS | 46 |
| OS | 48 |
| COA | 46 |
| DBMS | 47 |
| FLAT | 46 |
| Outside configured buckets | 17 |
| **Total** | **250** |

> **[EXAM_TIP]** Questions outside DS, OS, COA, DBMS, and FLAT are kept in a separate section so the ingest is lossless while preserving the configured subject buckets.

## DS

| ID | Question | Answer |
|---|---|---|
| 2025-Apr Q01 | Insert `S E A R C H E X A M P L E` into an empty BST and find the height. | **b. 3**. Height is 3 edges on the longest root-to-leaf path. |
| 2025-Apr Q02 | Number of distinct binary trees possible with three nodes. | **b. 5**. Catalan number `C3 = 5`. |
| 2025-Apr Q03 | Best-case time complexity of an optimized bubble sort. | **c. O(N)**. A sorted array needs one pass when the swap flag is used. |
| 2025-Apr Q04 | Recursive functions use which data structure internally. | **b. Stack**. Activation records are pushed and popped in LIFO order. |
| 2025-Apr Q05 | Infix `a + b * c - d ^ e ^ f` to postfix. | **a. `abc*+def^^-`**. Exponentiation is right-associative. |
| 2025-Apr Q06 | Evaluate postfix `10 5 + 60 6 / * 8 -`. | **c. 142**. `(10 + 5) * (60 / 6) - 8 = 142`. |
| 2025-Apr Q07 | Average number of comparisons for successful sequential search. | **d. `(n + 1) / 2`**. |
| 2025-Apr Q08 | Correct statements about hash functions. | **c. i and iii**. Hashing maps keys to table positions and collisions are possible. |
| 2025-Apr Q09 | Traversal of a tree level by level. | **a. Level order**. It is implemented using BFS. |
| 2025-Apr Q10 | Given stack and queue operations, compute `s + q`. | **a. 86**. Final stack top `s = 62`, queue front `q = 24`. |
| 2023-Jun Q01 | Worst-case complexity of quicksort. | **c. O(n^2)**. |
| 2023-Jun Q02 | Output of the given recursive print function. | **d. `1 3 5 5 3 1`**. The function prints before and after the recursive call. |
| 2023-Jun Q03 | Prefix form of `A - B / (C * D op E)`. | **c. `-A/B*CopDE`**. Operator precedence places the parenthesized operation before division. |
| 2023-Jun Q04 | Possible pivot after the first quicksort partition of `4 9 6 2 5 7 1 8 3`. | **a. 7 or 9**. Both satisfy the partition condition for the shown array state. |
| 2023-Jun Q05 | Number of leaf nodes in a full `k`-ary tree with `n` internal nodes. | **c. `n(k - 1) + 1`**. |
| 2023-Jun Q06 | Inorder predecessor of a BST node with two children. | **c. It has no right child**. It is the maximum node in the left subtree. |
| 2023-Jun Q07 | Number of inversions in `5 1 6 2 4`. | **d. 6**. |
| 2023-Jun Q08 | Sequence container among the listed structures. | **b. Deque**. |
| 2023-Jun Q09 | Minimum queues needed to implement a priority queue. | **a. 1**. One queue is enough if insertion maintains priority order. |
| 2023-Jun Q10 | Data structure used in BFS. | **a. Queue**. |
| 2024-May Q01 | Properties of a binary search tree. | **a. Both statements are true**. Left subtree keys are smaller and right subtree keys are larger. |
| 2024-May Q02 | Height of the binary tree from given inorder and postorder traversals. | **d. 4**. Reconstructing the tree gives longest path length 4 edges. |
| 2024-May Q03 | Condition for a queue with only one element. | **d. None of these**. Correct condition is `FRONT = REAR`, not both null. |
| 2024-May Q04 | Evaluate prefix `+ A * - B C D` for `A=5, B=4, C=2, D=3`. | **c. 11**. `5 + ((4 - 2) * 3) = 11`. |
| 2024-May Q05 | BFS traversal of the displayed graph starting at `Q`. | **c. `QMNROP`**. This is valid for the neighbor order shown in the figure. |
| 2024-May Q06 | Sequence that can occur while searching for 88 in a BST. | **c. `190, 60, 90, 85, 88`**. It respects the narrowing BST search interval. |
| 2024-May Q07 | Data structure used for recursion. | **b. Stack**. |
| 2024-May Q08 | Correct loop to traverse to the last node of a linked list. | **c. `while(temp->link != NULL) temp = temp->link;`**. |
| 2024-May Q09 | Hashing method where each table slot has a linked list. | **a. Separate chaining**. |
| 2024-May Q10 | Complexity of merging two sorted linked lists of lengths `m` and `n`. | **c. O(m + n)**. |
| 2022-Jun Q01 | Postorder traversal of the displayed binary tree. | **a. `d e b f g c a`**. |
| 2022-Jun Q02 | Operation not normally associated with stack usage. | **d. Data transfer between two asynchronous processes**. |
| 2022-Jun Q03 | Worst-case time to search a linear linked list of length `n`. | **d. O(n)**. |
| 2022-Jun Q04 | Implementing a stack using queues. | **b. Two queues**. |
| 2022-Jun Q05 | Data structure suitable for Tower of Hanoi. | **d. Stack**. |
| 2022-Jun Q06 | Infix `a + b * c - d ^ e ^ f` to postfix. | **a. `abc*+def^^-`**. |
| 2022-Jun Q07 | Worst-case time complexity of heap sort. | **c. O(n log n)**. |
| 2022-Jun Q08 | Number of heap-sort delete-max operations represented by array `16 14 15 10 12 27 28`. | **b. 2**. The largest two elements have been moved to the sorted suffix. |
| 2022-Jun Q09 | Number of comparisons in the worst case for insertion sort. | **b. `n(n - 1) / 2`**. |
| 2022-Jun Q10 | Name for different keys producing the same hash value. | **c. Collision**. |
| 2018-Apr Q18 | Possible issue when traversing a circular linked list. | **C. Infinite loop**. |
| 2018-Apr Q19 | Stack underflow condition in an array stack. | **B. `TOP = -1`**. |
| 2018-Apr Q20 | Right child position of node `k` in a one-indexed binary heap. | **D. `2k + 1`**. |
| 2018-Apr Q21 | Traversal that lists BST keys in sorted order. | **C. Inorder traversal**. |
| 2018-Apr Q22 | Structure used to implement recursion. | **B. Stack**. |
| 2018-Apr Q23 | Sorting method that repeatedly selects the minimum element. | **A. Selection sort**. |

## OS

| ID | Question | Answer |
|---|---|---|
| 2025-Apr Q11 | Component not necessarily saved during a process context switch. | **b. TLB**. TLB entries may be flushed or tagged rather than stored as part of every process state. |
| 2025-Apr Q12 | Return value of `fork()` in child and parent. | **c. Child gets 0; parent gets the child process ID**. |
| 2025-Apr Q13 | Page replacement algorithm affected by Belady's anomaly. | **a. FIFO**. |
| 2025-Apr Q14 | Banker's algorithm is used for which purpose. | **a. Deadlock avoidance**. |
| 2025-Apr Q15 | Average waiting time for FCFS with arrivals `0,0,2,5,10` and bursts `10,5,3,20,2`. | **a. 12.8 ms**. Waiting times are `0, 10, 13, 13, 28`. |
| 2025-Apr Q16 | False statement about virtual memory. | **d. Virtual memory can be implemented only in multi-user systems**. |
| 2025-Apr Q17 | Synchronization is provided at which level. | **c. Both hardware and software level**. |
| 2025-Apr Q18 | Invalid deadlock-prevention statement. | **c. Never request a resource after releasing any resource**. This is not one of the standard prevention conditions. |
| 2025-Apr Q19 | Scheduling policy equivalent to FIFO. | **b. Non-preemptive scheduling**. FCFS is non-preemptive. |
| 2025-Apr Q20 | Page fault condition. | **b. Requested page is not in memory**. |
| 2025-Apr Q21 | Register that contains the address of the next instruction. | **b. Program counter**. |
| 2023-Jun Q11 | Context switches in the given SRTF scheduling instance. | **b. 2**. Excluding time zero and termination, switches occur between completed processes. |
| 2023-Jun Q12 | Resource not shared by threads of the same process. | **c. Stack and registers**. |
| 2023-Jun Q13 | Technique for solving starvation in priority scheduling. | **c. Aging**. |
| 2023-Jun Q14 | Main advantage of multiprogramming. | **a. High CPU utilization**. |
| 2023-Jun Q15 | Logical and physical address sizes for 64 pages, 512-byte pages, and 32 frames. | **c. 15-bit logical and 14-bit physical**. |
| 2023-Jun Q16 | FIFO page faults for the classic Belady sequence with 3 and 4 frames. | **d. 9 and 10**. |
| 2023-Jun Q17 | Total SCAN head movement for head 23 moving toward lower cylinders. | **c. 151**. Service down to 0, then up to the highest request. |
| 2023-Jun Q18 | Semaphore final value after `10` initial, `12` waits, and `x` signals gives `7`. | **b. 9**. `10 - 12 + x = 7`. |
| 2023-Jun Q19 | Disk scheduling algorithm with a uniform waiting-time pattern. | **c. C-SCAN**. |
| 2023-Jun Q20 | Fragmentation type in paging. | **b. Internal fragmentation**. |
| 2024-May Q11 | Advantage of round-robin scheduling. | **b. Better response time**. |
| 2024-May Q12 | Memory hole. | **b. Free memory block**. |
| 2024-May Q13 | Page number and offset for logical address 1142 with page size 200. | **a. Page 5 and offset 142**. |
| 2024-May Q14 | LRU faults for `A B C D A B E A B C D E` with four frames. | **c. 8**. |
| 2024-May Q15 | Final semaphore value from initial 9 after 27 `P` operations and 23 `V` operations. | **b. 5**. `9 - 27 + 23 = 5`. |
| 2024-May Q16 | SSTF total seek time for the listed disk queue. | **d. None of these**. Correct SSTF movement is 1745 cylinders. |
| 2024-May Q17 | Condition needed for deadlock. | **a. Mutual exclusion**. |
| 2024-May Q18 | Average FCFS waiting time for arrivals `3, 6, 9` and bursts `3, 6, 9`. | **Correct value: 1**. The provided options do not include the correct average waiting time. |
| 2024-May Q19 | Algorithm used for deadlock avoidance. | **c. Banker's algorithm**. |
| 2024-May Q20 | Information not normally stored in a PCB. | **d. Operating system information**. |
| 2022-Jun Q11 | Demand paging. | **a. Bringing a page into memory only when required**. |
| 2022-Jun Q12 | Banker's algorithm classification. | **Correct: deadlock avoidance**. The paper option says prevention, but the standard classification is avoidance. |
| 2022-Jun Q13 | Effect of successful `exec`. | **a. It does not return to the original program**. |
| 2022-Jun Q14 | TLB tag bits for 32-bit virtual address, 4 KB page, 128-entry 4-way TLB. | **c. 15 bits**. VPN is 20 bits and set index is 5 bits. |
| 2022-Jun Q15 | Page-table bit set when a page is modified after loading. | **c. Dirty bit**. |
| 2022-Jun Q16 | FIFO faults for 100 unique pages followed by the same pages in reverse using 4 frames. | **a. 196**. |
| 2022-Jun Q17 | Necessary condition for deadlock. | **a. Mutual exclusion**. |
| 2022-Jun Q18 | Scheduler that admits jobs into the ready queue. | **a. Long-term scheduler**. |
| 2022-Jun Q19 | Saving and loading process state during a switch. | **d. Context switching**. |
| 2022-Jun Q20 | Protection bits in a 32-bit PTE for 30-bit physical address and 4 KB pages. | **d. 14**. Frame number needs 18 bits. |
| 2018-Apr Q31 | Maximum number of running processes on an `m`-CPU system. | **D. m**. |
| 2018-Apr Q32 | Page replacement policy that may suffer Belady's anomaly. | **B. FIFO**. |
| 2018-Apr Q33 | Banker's algorithm is used for. | **B. Deadlock avoidance**. |
| 2018-Apr Q34 | Semaphore value after 8 waits and 3 signals starting at 4. | **A. -1**. |
| 2018-Apr Q35 | Physical address size for 1024 frames and 512-byte pages. | **D. 19 bits**. |
| 2018-Apr Q36 | Page size for 32-bit address, 9-bit page number, and 11-bit segment number. | **A. 4 KB**. |
| 2018-Apr Q37 | Disk scheduling algorithm also called the elevator algorithm. | **C. SCAN**. |

## COA

| ID | Question | Answer |
|---|---|---|
| 2025-Apr Q22 | Computer architectures mentioned in the options. | **d. All of these**. |
| 2025-Apr Q23 | Addressing mode where the instruction contains the operand address. | **b. Direct or absolute addressing**. |
| 2025-Apr Q24 | Feature commonly associated with CISC. | **b. Larger instruction set and fewer registers**. |
| 2025-Apr Q25 | Cycles to process 200 tasks on a 6-stage pipeline without stalls. | **d. 205 cycles**. `200 + 6 - 1`. |
| 2025-Apr Q26 | Advantage of register indirect addressing. | **d. It avoids storing the full memory address inside the instruction**. |
| 2025-Apr Q27 | Pipelining improves performance by exploiting. | **c. Instruction-level parallelism**. |
| 2025-Apr Q28 | Number of one-address instructions possible from the given opcode allocation. | **d. `2^30`**. Remaining opcode space expands into address fields. |
| 2025-Apr Q29 | Truth of the two addressing-mode statements. | **d. Neither S1 nor S2**. |
| 2025-Apr Q30 | DMA transfer. | **c. Between I/O units and memory**. |
| 2023-Jun Q21 | Reason for using a single-bus organization. | **c. Cost effectiveness and ease of attaching devices**. |
| 2023-Jun Q22 | Register connected to the data bus. | **c. MBR**. |
| 2023-Jun Q23 | Basic circuit for arithmetic addition. | **b. Parallel adder**. |
| 2023-Jun Q24 | Auto-increment and auto-decrement addressing statements. | **b. Statement 2 only**. |
| 2023-Jun Q25 | Five-bit two's-complement result of `-7 - (-5)`. | **a. `11110`**. This is `-2`. |
| 2023-Jun Q26 | Meaning of `Add LOCA, R0`. | **c. Add memory operand at LOCA to `R0` and store in `R0`**. |
| 2023-Jun Q27 | Effect of increasing cache associativity. | **a. Slower access time, fewer index bits, no block-size change**. |
| 2023-Jun Q28 | Set-associative cache lines for block `j`. | **a. From `(j mod v) * k` to `(j mod v) * k + (k - 1)`**. |
| 2023-Jun Q29 | Microinstruction organization with encoded control fields. | **b. Vertical organization**. |
| 2023-Jun Q30 | DMA transfer direction. | **c. I/O to memory**. |
| 2024-May Q21 | Fast memory located between CPU and main memory. | **c. Cache memory**. |
| 2024-May Q22 | Pipeline hazard caused by insufficient resources. | **b. Structural hazard**. |
| 2024-May Q23 | Pipeline item that is not a typical hazard. | **d. Logical hazard**. Structural, data, and control hazards are the standard pipeline hazards. |
| 2024-May Q24 | RTL. | **b. Register transfers inside the CPU**. |
| 2024-May Q25 | Time for an instruction taking 4 cycles on a 2 GHz processor. | **b. 2 ns**. Each cycle is 0.5 ns. |
| 2024-May Q26 | Hazards between `ADD R4,R5,R6` and `ADD R4,R4,R6`. | **d. RAW and WAW**. |
| 2024-May Q27 | Addressing mode where operand location is implied by instruction. | **b. Implied addressing mode**. |
| 2024-May Q28 | Architecture with many complex instructions. | **a. CISC**. |
| 2024-May Q29 | Five-bit two's-complement representation of `-2`. | **a. `11110`**. |
| 2024-May Q30 | Basic instruction cycle phases. | **a. Fetch, decode, execute**. |
| 2022-Jun Q21 | ROM size for a 4-bit multiplier. | **d. 2 Kbits**. 8 input address bits and 8 output bits. |
| 2022-Jun Q22 | Register or hardware matching question from the figure. | **a. A6 B1 C3 D5 E2 F4**. |
| 2022-Jun Q23 | Technique used to remove WAR and WAW hazards. | **c. Register renaming**. |
| 2022-Jun Q24 | Memory interleaving is used to. | **b. Reduce effective memory access time by increasing bandwidth**. |
| 2022-Jun Q25 | When the data TLB is accessed. | **c. After effective address calculation**. |
| 2022-Jun Q26 | Matching DMA, cache, interrupt I/O, and condition-code register. | **b. A2 B1 C3 D4**. |
| 2022-Jun Q27 | DMA mode that temporarily takes bus cycles from CPU. | **c. Cycle stealing**. |
| 2022-Jun Q28 | Interrupt priority scheme with fixed serial priority. | **a. Daisy chaining**. |
| 2022-Jun Q29 | Number of micro-operation sequences for `N` distinct opcodes. | **d. N**. If `N` meant opcode bits, the answer would be `2^N`; the paper wording says distinct opcodes. |
| 2022-Jun Q30 | Sets in a 64 KB, 4-way set associative cache with 128-byte blocks. | **b. 128 sets**. There are 512 lines and 128 sets. |
| 2018-Apr Q24 | Addressing mode where the operand is part of the instruction. | **C. Immediate addressing**. |
| 2018-Apr Q25 | Item that is not an assembler directive. | **D. ADD**. |
| 2018-Apr Q26 | Expansion of SCSI. | **B. Small Computer System Interface**. |
| 2018-Apr Q27 | Basic SRAM storage cell implementation. | **A or C**. The official key accepts both transistor-based and cross-coupled-inverter wording. |
| 2018-Apr Q28 | Address bits for 16384 blocks of 256 eight-bit words. | **A. 22 bits**. |
| 2018-Apr Q29 | Programmable logic device with AND and OR arrays. | **B. PLA**. |
| 2018-Apr Q30 | Main task in control-unit design. | **C. Generating control signals**. |

## DBMS

| ID | Question | Answer |
|---|---|---|
| 2025-Apr Q31 | Hierarchical data model relationship. | **a. Parent-child relationship**. |
| 2025-Apr Q32 | If a relation is in BCNF, it is also in which normal forms. | **d. 1NF, 2NF, and 3NF**. |
| 2025-Apr Q33 | Normal form that removes partial dependency. | **b. 2NF**. |
| 2025-Apr Q34 | Requirement for 2NF. | **d. Every non-key attribute depends on the whole primary key**. |
| 2025-Apr Q35 | If each `B` can map to many `A` values, but each `A` maps to one `B`. | **d. Many-to-one from A to B**. |
| 2025-Apr Q36 | Relation definition in relational model. | **b. A subset of Cartesian product of domains**. |
| 2025-Apr Q37 | Tables needed for a many-to-many relationship between two entity sets. | **b. 3 tables**. |
| 2025-Apr Q38 | Statements for `R(x,y,z,w)` with FDs `x -> y` and `z -> w`, with atomic attributes. | **a. i and iii only**. The relation is in 1NF and has primary key `xz`, but partial dependencies violate 2NF. |
| 2025-Apr Q39 | SQL query with department filter and `HAVING COUNT(*) > 5`. | **b. Total employees in departments D1 or D2 only for groups with more than 5 employees**. |
| 2025-Apr Q40 | Key referenced by a foreign key. | **b. Primary key**. A candidate or unique key is also valid in SQL, but the paper expects primary key. |
| 2023-Jun Q31 | Tables needed for a many-to-many relationship. | **b. 3**. |
| 2023-Jun Q32 | Maximum number of rows in a join of relations with `m` and `n` rows. | **a. mn**. |
| 2023-Jun Q33 | Dense index. | **a. One index entry for every search-key value**. |
| 2023-Jun Q34 | A BCNF relation is necessarily in. | **b. 3NF**. It is also in lower normal forms. |
| 2023-Jun Q35 | SQL command category of `CREATE`. | **b. DDL**. |
| 2023-Jun Q36 | Degree of a relation. | **d. Number of attributes**. |
| 2023-Jun Q37 | Block accesses to find a record in the given B+ tree setting. | **d. 4**. Three index levels plus the data block. |
| 2023-Jun Q38 | Highest normal form for `R(A,B,C,D,E)`, `AB -> CE`, `E -> AB`, `C -> D`. | **b. 2NF**. It has a transitive dependency through `C -> D`. |
| 2023-Jun Q39 | Concurrency problem shown by two writes overwriting each other. | **a. Lost update**. |
| 2023-Jun Q40 | Possible final values after interleaved transactions incrementing `P` and `Q`. | **b. `P = 1, Q = 1`**. Both can read old values before writes. |
| 2024-May Q41 | Highest normal form for `R(A,B,C,D,E)`, `AB -> C`, `B -> D`, `C -> E`. | **a. 1NF**. Partial dependency `B -> D` violates 2NF. |
| 2024-May Q42 | SQL statements about `HAVING` and `GROUP BY`. | **a. P and S**. `HAVING` can be used without `GROUP BY`; selected attributes need not all appear in `GROUP BY` if aggregated correctly. |
| 2024-May Q43 | SQL `LIKE` pattern for strings containing at least two zeroes. | **d. `%0%0%`**. |
| 2024-May Q44 | SQL query computing the minimum age per class having more than three enrolled students. | **b. It gives the age of the youngest student for each class with more than three enrolled students**. |
| 2024-May Q45 | Tables required for a many-to-many relationship. | **a. 3**. |
| 2024-May Q46 | False statement about B+ trees. | **b. Non-leaf nodes point to data records**. In B+ trees, data pointers are in leaves. |
| 2024-May Q47 | Decomposition of `X(P,Q,R,S)` into `Y(P,R)` and `Z(Q,R,S)`. | **c. II only**. The decomposition is lossless and dependency preserving, but not fully BCNF because `S -> Q` violates BCNF in `Z`. |
| 2024-May Q48 | True statement about SQL results. | **d. `ORDER BY` defaults to ascending order and duplicate rows are retained unless `DISTINCT` is used**. |
| 2024-May Q49 | SQL command category of `DELETE`. | **a. DML**. |
| 2024-May Q50 | Number of candidate keys for `R(A,B,C,D,E)`, `AB -> CD`, `ABC -> E`, `C -> A`. | **b. 2**. Candidate keys are `AB` and `BC`. |
| 2022-Jun Q31 | ACID property that guarantees committed changes persist. | **c. Durability**. |
| 2022-Jun Q32 | Normal form reached when transitive dependency is removed. | **c. 3NF**. |
| 2022-Jun Q33 | SQL command for deleting a table definition. | **a. DROP**. |
| 2022-Jun Q34 | Minimal superkey. | **b. Candidate key**. |
| 2022-Jun Q35 | FD set satisfied by the given relation instance. | **b. `YZ -> X` and `Y -> Z`**. |
| 2022-Jun Q36 | Meaning of the nested `NOT IN` SQL query over suppliers, catalog, and parts. | **Correct: suppliers who have no catalog entry for a blue part**. The listed options do not exactly match the SQL as printed. |
| 2022-Jun Q37 | Cardinality where many entities of `A` can be associated with one entity of `B`. | **d. Many-to-one from A to B**. |
| 2022-Jun Q38 | SQL access-control commands. | **b. GRANT and REVOKE**. |
| 2022-Jun Q39 | Cardinality of `One EXCEPT Two` and `One EXCEPT ALL Two`. | **b. 1 and 2**. |
| 2022-Jun Q40 | Relationship between BCNF and 3NF. | **c. Every BCNF relation is in 3NF**. |
| 2018-Apr Q38 | Index structure that supports direct access of data. | **A. B-tree**. |
| 2018-Apr Q39 | Subsystem responsible for restoring consistency after failure. | **C. Recovery subsystem**. |
| 2018-Apr Q40 | Number of possible serial schedules for `n` transactions. | **Any option credited by source**. Correct theoretical answer is `n!`. |
| 2018-Apr Q41 | Statement truth about database schemas and instances. | **D. S2 only**. |
| 2018-Apr Q42 | Snapshot of database content at a particular time. | **C. Instance**. |
| 2018-Apr Q43 | Two-phase locking variant that avoids deadlock by acquiring all locks first. | **B. Conservative 2PL**. |
| 2018-Apr Q44 | Serializability of the given schedule. | **D. Not serializable**. |

## FLAT

| ID | Question | Answer |
|---|---|---|
| 2025-Apr Q41 | Closure of CFLs under union. | **b. CFL**. Union of two CFLs is CFL. |
| 2025-Apr Q42 | Membership in `L*` for `L = {ab, aa, baa}`. | **c. i, ii, and iv**. The third string cannot be segmented into words of `L`. |
| 2025-Apr Q43 | Grammar for odd-length palindromes over `{a,b}`. | **b. `S -> aSa ; bSb ; a ; b`**. |
| 2025-Apr Q44 | Chomsky hierarchy from lowest to highest generative power. | **a. Regular, CFL, CSL, unrestricted**. |
| 2025-Apr Q45 | Extra memory used by a PDA. | **d. Stack**. |
| 2025-Apr Q46 | Operations used to build regular languages from basic languages. | **d. All mentioned**. Union, concatenation, and Kleene star are regular operations; the paper wording is defective because it says "cannot". |
| 2025-Apr Q47 | Output dependency in a Moore machine. | **b. Present state only**. |
| 2025-Apr Q48 | False statement among the listed decidability facts. | **d. Regular grammar equivalence is undecidable**. It is decidable. |
| 2025-Apr Q49 | Equivalent phrase for a Turing-decidable language. | **a. Recursive language**. |
| 2025-Apr Q50 | Complement of the NFA language over `{a}` shown in the figure. | **b. `{epsilon}`**. The NFA accepts one or more `a` symbols. |
| 2023-Jun Q41 | Strings over `{0,1}` having even numbers of both 0 and 1, excluding Kleene-star epsilon. | **b. `0011, 11001100`**. |
| 2023-Jun Q42 | Item not part of a finite automaton 5-tuple. | **d. Output alphabet**. |
| 2023-Jun Q43 | Conversion not generally possible by algorithm. | **c. NPDA to DPDA**. |
| 2023-Jun Q44 | Regular expression for strings beginning with `ab` and ending with `bba`. | **c. `ab(a+b)*bba`**. |
| 2023-Jun Q45 | Pumping lemma is used for. | **b. Proving a given language is not regular**. |
| 2023-Jun Q46 | Minimum DFA states for `(111 + 11111)*`. | **d. 9**. The unary language excludes lengths 1, 2, 4, and 7, then accepts all sufficiently large lengths. |
| 2023-Jun Q47 | If `L` is regular, then the halving language is. | **b. Regular**. Regular languages are closed under quotient-like finite-state transformations. |
| 2023-Jun Q48 | Language that cannot be generated by a regular grammar. | **d. `{0^n 1^n : n >= 0}`**. |
| 2023-Jun Q49 | CFL closure among star, union, and concatenation. | **d. All of these**. |
| 2023-Jun Q50 | Grammar classification for the grammar with a multi-symbol left-hand side. | **d. Type 0**. The grammar is not regular or context-free. |
| 2024-May Q31 | Regular expression for binary strings with no consecutive zeroes. | **c. `(1+01)*(epsilon+0)`**. |
| 2024-May Q32 | Minimum DFA states for strings containing three consecutive zeroes. | **a. 4**. |
| 2024-May Q33 | Equivalent grammars among the listed productions. | **b. i and iii**. Both generate the same `a+ b` pattern. |
| 2024-May Q34 | NP closure property not known or not generally guaranteed. | **d. Complement**. |
| 2024-May Q35 | Relationship between the two languages in the question. | **c. `L2` is CFL but not `L1`**. |
| 2024-May Q36 | Grammar class equivalent to Turing-machine-recognizable languages. | **b. Unrestricted grammar**. |
| 2024-May Q37 | Relationship between regular grammars and CFGs. | **a. Every regular grammar is context-free**. |
| 2024-May Q38 | Tree representation of derivation in a CFG. | **c. Both parse tree and derivation tree**. |
| 2024-May Q39 | Automata size for `(11 + 111)*`. | **a. DFA 4 and NFA 3**. |
| 2024-May Q40 | If both `L` and complement of `L` are recursively enumerable. | **c. `L` is recursive**. |
| 2022-Jun Q41 | How to prove a language is not regular. | **b. Show that no DFA can recognize it**. |
| 2022-Jun Q42 | String not accepted by the displayed DFA. | **a. epsilon**. |
| 2022-Jun Q43 | Regular expression for strings beginning with `ab` and ending with `bba`. | **c. `ab(a+b)*bba`**. |
| 2022-Jun Q44 | Statements about NFA-to-DFA conversion. | **c. Statement 1 can be true and statement 2 is true**. The initial DFA state is normally the epsilon-closure of the NFA start state. |
| 2022-Jun Q45 | Number of states in epsilon-closure of `f2` in the figure. | **c. 2**. The closure contains `f2` and `f3`. |
| 2022-Jun Q46 | Language class accepted by PDA. | **b. Context-free language**. |
| 2022-Jun Q47 | Productions invalid in Chomsky Normal Form. | **a. 2 and 4**. `S -> AAS` and `A -> aa` violate CNF form. |
| 2022-Jun Q48 | Correct statement about undecidability. | **a. Halting problem is unsolvable**. |
| 2022-Jun Q49 | Useless production in the grammar. | **d. `B -> bA`**. `B` is unreachable from the start symbol. |
| 2022-Jun Q50 | Production type `S -> A`. | **b. Unit production**. |
| 2018-Apr Q45 | Item that is not an application of context-free grammar. | **B. Type checking**. |
| 2018-Apr Q46 | Finite language property. | **A. Every finite language is regular**. |
| 2018-Apr Q47 | Minimum states for the automaton question in the source. | **B. 5 states**. |
| 2018-Apr Q48 | CFL non-closure property. | **A. Intersection**. |
| 2018-Apr Q49 | Membership in the given regular-expression language. | **Any option credited by source**. The source answer key awards marks for all options. |
| 2018-Apr Q50 | Grammar form where productions are `A -> BC` or `A -> a`. | **A. Chomsky Normal Form**. |

## Outside Configured Buckets

These entries are retained to keep the ingest lossless. They belong to mathematics, engineering, software engineering, or environmental studies rather than DS, OS, COA, DBMS, or FLAT.

| ID | Question | Answer |
|---|---|---|
| 2018-Apr Q01 | Classification of the stationary point in the given calculus problem. | **C. Neither maximum nor minimum**. |
| 2018-Apr Q02 | Order and degree of the given differential equation. | **A. Order 2 and degree 3**. |
| 2018-Apr Q03 | Force equilibrium condition in engineering mechanics. | **D. All force components sum to zero**. |
| 2018-Apr Q04 | Concept represented by revolving a plane area about an axis. | **A. Surface area of a body of revolution**. |
| 2018-Apr Q05 | Engineering graphics angle question. | **B. 120 degrees**. |
| 2018-Apr Q06 | Quadrant identification question in engineering graphics. | **C. Third quadrant**. |
| 2018-Apr Q07 | Year associated with the environmental act or event in the question. | **B. 1974**. |
| 2018-Apr Q08 | Non-renewable energy source in the options. | **C. Coal energy**. |
| 2018-Apr Q09 | Software process model used when requirements are unclear. | **C. Prototyping model**. |
| 2018-Apr Q10 | Process of deriving design or specifications from existing code. | **A. Reverse engineering**. |
| 2018-Apr Q11 | Result of the given discrete mathematics expression. | **C. `4x^3 + 9`**. |
| 2018-Apr Q12 | Truth of the algebraic-structure statements. | **B. Both statements are true**. |
| 2018-Apr Q13 | Condition for a function from a set of size `m` onto a set of size `n`. | **A or B**. The official key accepts both; mathematically, onto requires `m >= n`. |
| 2018-Apr Q14 | Relation property classification. | **D. Irreflexive and symmetric**. |
| 2018-Apr Q15 | Logical conclusion from the given premises. | **C. `p -> (q and r)`**. |
| 2018-Apr Q16 | Solution of the recurrence in the question. | **B**. |
| 2018-Apr Q17 | Asymptotic classification in the source. | **C. O(n)**. |

## Notes on Defective or Ambiguous Items

> **[EXAM_TIP]** When an MCQ has no correct listed option, write the mathematically correct result first and then mention the option mismatch. This is safer than memorizing a defective option.

- 2024-May Q18 has correct FCFS average waiting time `1`, but the printed options omit it.
- 2022-Jun Q36 SQL evaluates to suppliers with no blue-part catalog entry; the printed answer choices do not match exactly.
- 2025-Apr Q46 says "cannot" even though the intended closure operations are union, concatenation, and Kleene star.
- 2018-Apr Q40 and Q49 were officially credited for any option in the source key.

## Cross-References

- DS traversal, heap, sorting, stack, queue, and hashing questions connect to the time-complexity emphasis used throughout DS problems.
- OS paging, TLB, and page replacement questions connect directly to [COA Memory Hierarchy](../coa/memory-hierarchy.md) and [Cache Memory](../coa/cache-memory.md).
- COA cache and DMA questions connect to [DBMS Indexing and Buffering](../dbms/indexing-and-buffering.md), especially buffer pool and page-cache behavior.
- DBMS normal-form and dependency questions connect to [Normalization](../dbms/normalization.md).
- FLAT closure, grammar, and automata questions connect to [Chomsky Hierarchy and Closure](../flat/chomsky-hierarchy-and-closure.md), [Context-Free Languages and PDA](../flat/context-free-languages-pda.md), and [Turing Machines and Decidability](../flat/turing-machines-decidability.md).
