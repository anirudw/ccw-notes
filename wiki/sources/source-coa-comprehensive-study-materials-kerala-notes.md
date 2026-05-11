# COA Comprehensive Study Materials - Kerala Notes

**Subject:** COA
**Prerequisites:** [Memory Hierarchy](../coa/memory-hierarchy.md), [Addressing Modes](../coa/addressing-modes.md)
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [COA Comprehenisve Study Materials - Kerala Notes.pdf](../../raw/COA%20Comprehenisve%20Study%20Materials%20-%20Kerala%20Notes.pdf)

## Summary

This source is a 43-page COA multiple-choice question collection. It emphasizes exam-recognition facts: cache memory and locality, memory hierarchy, instruction and addressing terminology, assembly language, fixed/floating representation, I/O organization, interrupts, DMA, microinstructions, and basic logic/register concepts.

The document is useful as a high-yield checklist rather than as a full theory text. Several answer-key entries conflict with standard COA definitions, so the topic pages record corrected technical definitions where needed.

## Key Takeaways

- Cache memory is repeatedly tested as the fast memory between CPU and RAM, based on locality of reference.
- Memory hierarchy questions focus on access time, volatility, and the order from registers/cache through main memory to secondary storage.
- Addressing-mode questions test why modes exist and how effective addresses are formed.
- I/O and interrupt questions focus on memory-mapped I/O, vectored interrupts, DMA, PSW saving, and flag/status bits.
- Register-transfer terminology appears often: instruction code, micro-operation, microinstruction, program counter, shift register, and flip-flop.

## Specific Exam-Focused Claims

- SIMD uses many processing units under a common control unit.
- Von Neumann architecture is classified as SISD in Flynn's taxonomy.
- Floating-point representation is used for real-number values.
- Subtraction in binary computers is generally implemented using 2's complement.
- A flip-flop stores one bit.
- A group of bits that directs the computer to perform a specific operation is an instruction code.
- The average time to reach a memory location and obtain its contents is access time.
- RAM is unsuitable for permanent storage because it is volatile.
- Cache memory acts between CPU and RAM.
- Cache memory is based on locality of reference.
- Cache performance is commonly measured using hit ratio or miss ratio.
- Write-through is a cache update policy.
- Associative memory is accessed by content rather than by a normal address.
- Stack-organized computers use zero-address instructions.
- A k-bit register field can specify 2^k registers.
- A PC-relative address is formed by adding the program counter to the address/displacement field.
- A vectored interrupt supplies branch information through an interrupt vector.
- DMA transfers data directly between memory and an I/O device without ordinary programmed CPU transfer for each word.
- An I/O interface transfers binary information between internal storage and external devices.
- A status bit is also called a flag bit.
- An instruction pipeline is commonly modeled as a FIFO buffer.

## Verify Before Memorizing

> **[EXAM_TIP]** Treat this PDF as a question bank, not an authority for disputed theory.

- The source answer key says a reduced bus cycle time keeps the same bandwidth in one item. Standard bandwidth calculation doubles throughput if transfer cycles are unchanged and each cycle halves in duration.
- The source answer key marks a memory-mapped I/O item in a way that conflicts with the usual rule: memory-mapped I/O uses ordinary memory instructions, while isolated I/O uses separate IN/OUT style instructions.
- The source answer key associates virtual memory with Static RAM in one item. Standard definition: virtual memory is an OS memory-management abstraction backed by page tables and secondary storage, not an SRAM device.
- The source answer key has a direct/immediate addressing ambiguity. Standard rule: immediate addressing stores the operand value in the instruction; direct addressing stores the operand address in the instruction.
- The source answer key says DRAM is used as main memory because of higher speed. Standard rationale is high density and lower cost per bit compared with SRAM; DRAM also needs refresh.

## Distributed Pages

- [Memory Hierarchy](../coa/memory-hierarchy.md)
- [Cache Memory](../coa/cache-memory.md)
- [Cache Mapping](../coa/cache-mapping.md)
- [Addressing Modes](../coa/addressing-modes.md)
- [I/O, Interrupts, and DMA](../coa/io-interrupts-dma.md)
