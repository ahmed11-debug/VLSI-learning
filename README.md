# Verilog HDL Practice

A collection of digital circuits designed and verified in Verilog as part of my VLSI learning journey. Each circuit is built using gate-level modeling and tested with a custom testbench, simulated on EDA Playground.

This repo is updated continuously as I progress through more advanced topics.

## Circuits

### 1. Half Adder
- `Sum = A XOR B`
- `Carry = A AND B`

### 2. Full Adder
- `Sum = A XOR B XOR Cin`
- `Cout = (A.B) + (B.Cin) + (A.Cin)`

### 3. Half Subtractor
- `Diff = A XOR B`
- `Borrow = A'.B`

### 4. Full Subtractor
- `Diff = A XOR B XOR Bin`
- `Borrow = A'B + A'Bin + B.Bin`

### 5. 4-bit Ripple Carry Adder (RCA)
Four Full Adders chained together to add two 4-bit binary numbers.

### 6. BCD Adder
Built on the 4-bit RCA with correction logic (+6) for values exceeding 9.

### 7. 2-Bit Comparator
Compares two 2-bit numbers A and B and produces three outputs.
- `GT = 1` when A > B
- `ET = 1` when A = B  
- `LT = 1` when A < B

Tested with all 16 input combinations using a nested loop testbench.

**More circuits added as I progress — multiplexers, flip flops, counters, FSMs, and beyond.**

## Tools Used
- **EDA Playground** — Verilog simulation and testing
- **Aldec Riviera Pro** — simulation engine

## Learning Resources
- All About VLSI — Verilog HDL Complete Course (YouTube)
- Neso Academy — Digital Logic Design (YouTube)

---
*This repo documents my hands-on practice while learning digital design and Verilog HDL fundamentals. Last updated: ongoing.*
