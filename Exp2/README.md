# EXPERIMENT 02 – 4-BIT RIPPLE CARRY ADDER

## AIM
To design and simulate a 4-bit ripple carry adder using full adders.

## THEORY

A **binary adder** is used to perform arithmetic addition of binary numbers.

### Full Adder

A full adder adds three inputs: A, B, and carry-in.

**Equations:**
S = A ⊕ B ⊕ Cin
Cout = AB + BCin + ACin

### Ripple Carry Adder

A 4-bit ripple carry adder is constructed by connecting **four full adders in series**.

- Carry output of each stage becomes input to the next stage.
- This causes **propagation delay**, known as ripple effect.

### Advantages

- Simple and easy to design
- Requires fewer components

### Disadvantages

- Slow due to carry propagation delay

## PROCEDURE

1. Design a 1-bit full adder.
2. Connect four full adders in series.
3. Provide two 4-bit inputs.
4. Observe sum and carry outputs.
5. Verify correctness.

## RESULT

The 4-bit ripple carry adder was successfully designed and verified.

---
