# Interruptive Authority

> Preventing authorization collapse in autonomous AI systems

A structural approach to AI oversight beyond alignment.

**Alignment is not control.**

## Quick Links

- 📄 [Paper](paper/interruptive_authority.pdf)
- ⚙️ [Specification](spec/interruptive_authority_spec.md)
- 🧪 [Examples](examples/)

## Core Idea

Alignment ensures systems pursue the right objectives.

Interruptive Authority ensures humans retain the authority to stop them.

These are not the same.

## Problem

Most current approaches optimize behavior.

They do not preserve authority.

Most AI safety approaches focus on:
- goal correctness
- behavioral alignment
- constraint encoding

But overlook a structural failure mode:

> When a system participates in determining whether it should continue,
> authorization collapses into optimization.

We call this **authorization collapse**.

## Solution

Introduce **Interruptive Authority**:

> The retained human standing to suspend system operation,
> independent of the system’s own evaluative structure.
>
> ## Minimal Design Requirement
>
This defines the minimum conditions for preserving human interrupt authority. 
>
An interruption mechanism MUST satisfy the following properties:

- External: not derived from the system`s internal evaluation
- Unconditional: not overridable by system otpimization
- Immediate: capable of halting execution without negotiation

## Why It Matters

Without this separation:
- delegation → self-authorization
- oversight → simulation
- control → illusion

## Repository Contents

- `/paper` — formal manuscript
- `/spec` — system-level specification (in progress)
- `/examples` — implementation scenarios
- `/diagrams` — system architecture

## Discussion

We use Issues as an open forum for developing this concept.

Open questions:
- What constitutes true interruptive authority?
- Can alignment ever replace external authority?
- How do we reduce epistemic dependence in practice?

## Status

Draft — open for discussion, critique, and implementation exploration

## Contributing

See CONTRIBUTING.md

## License

MIT
