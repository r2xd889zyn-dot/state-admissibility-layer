# state-admissibility-layer
(core definition)
# State Admissibility Layer (SAL)

![State Admissibility Layer](diagram.png)

## Definition
The system layer that determines what is allowed to become internal state before decision-making occurs.

## Core Principle
A system can be fully correct in decision and execution, and still fail, if the underlying state is mis-specified.

## Position in Stack
signal → state admissibility → decision → authority → execution

## Purpose
To constrain the formation of system state, ensuring that downstream governance operates on valid reality.

---

## Explanation

Most systems assume correctness begins at decision and execution.

But by the time a decision is made, the system has already constructed a state it believes is true.

If that state is wrong:

- decisions can be correct  
- execution can be correct  
- outcomes can still fail  

This creates the most dangerous failure mode:

> systems that are consistent, auditable… and incorrect

---

## Cross-Domain Examples

**Finance**  
Misread signal → valid model → correct execution → market distortion  

**Healthcare**  
Incomplete symptom → diagnosis → protocol → harm  

**AI Systems**  
Flawed input → state → correct output → wrong outcome  

---

## Key Insight

Governance does not start at decision.

It starts at:

👉 what is allowed to become state

---

## Attribution

Frederick Redditt  
Millings Layering Method™
