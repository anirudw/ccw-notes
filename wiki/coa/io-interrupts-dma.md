# I/O, Interrupts, and DMA

**Subject:** COA
**Prerequisites:** [Addressing Modes](addressing-modes.md), [Memory Hierarchy](memory-hierarchy.md)
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [COA Comprehensive Study Materials - Kerala Notes](../sources/source-coa-comprehensive-study-materials-kerala-notes.md)

## I/O Interface

An I/O interface provides a method for transferring binary information between internal storage and external devices.

In memory-mapped I/O, device registers are assigned addresses in the memory address space, so ordinary memory-style instructions can access them. In isolated I/O, the processor uses a separate I/O address space and may provide special IN/OUT instructions.

> **[EXAM_TIP]** If a question contrasts memory-mapped I/O with isolated I/O, remember: memory-mapped I/O uses normal memory instructions; isolated I/O uses separate I/O instructions.

## Interrupts

A vectored interrupt is one in which the interrupting source supplies branch information through an interrupt vector. This lets the processor jump to the correct interrupt service routine.

The Program Status Word (PSW) is saved when an interrupt is recognized so execution state can be restored after service.

Status bits are also called flag bits.

## DMA

DMA stands for Direct Memory Access. It allows an I/O device or controller to transfer data directly to or from memory with reduced CPU involvement.

> **[CONNECTION]** DMA and cache both affect memory consistency: when I/O writes memory directly, cache coherence or cache flushing may be needed on real systems.

## Related Register Facts

- A shift register can shift binary information left or right.
- The program counter tracks the address of the next instruction to fetch.
- A microprogram sequencer generates the address of the next microinstruction.
- Microinstructions are stored in control memory.
