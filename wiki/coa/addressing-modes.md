# Addressing Modes

**Subject:** COA
**Prerequisites:** [Memory Hierarchy](memory-hierarchy.md)
**Exam Importance:** High
**Last updated:** 2026-05-11
**Sources:** [COA Comprehensive Study Materials - Kerala Notes](../sources/source-coa-comprehensive-study-materials-kerala-notes.md)

## Definition

An addressing mode is the rule used by an instruction to interpret its address or operand field and compute the effective address or operand value.

Addressing modes are used to:

- provide programming flexibility, such as pointers and loop control;
- reduce the number of bits needed in some instruction fields;
- specify how the instruction address field should be interpreted or modified.

## Common Modes

| Mode | Meaning |
| --- | --- |
| Immediate | Operand value is inside the instruction itself. |
| Direct or absolute | Instruction address field contains the effective memory address. |
| Indirect | Instruction address field points to a memory location that contains the effective address. |
| Indexed | Effective address is address field plus an index register. |
| Relative | Effective address is program counter plus displacement/address field. |
| Implied | Operand is implicit in the opcode, such as accumulator operations. |
| Stack or zero-address | Operands are taken from the stack, so the instruction need not name operand addresses. |

> **[EXAM_TIP]** Stack-organized computers are associated with zero-address instructions.

> **[EXAM_TIP]** If an MCQ says the operand value itself is explicitly present in the instruction, the standard answer is immediate addressing.

## Instruction-Format Facts

- A group of bits that tells the computer to perform a specific operation is an instruction code.
- If an operation-code field has `n` bits, it can represent `2^n` distinct operations.
- If a register field has `k` bits, it can specify `2^k` registers.
- Assembly language uses symbolic or alphabetic codes in place of raw binary machine code.
- The `ORG` directive is a pseudo-instruction, not a machine instruction.
- Translation from symbolic assembly to binary is commonly described as a two-pass assembler process.

## Source Caution

The source answer key has a direct/immediate addressing ambiguity. Use the formal definitions above for technical accuracy.
