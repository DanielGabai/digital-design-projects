# Digital Design Projects

## Overview
This repository contains a collection of digital logic projects built using Falstad Circuit Simulator.

These projects were created to explore and practice hardware design fundamentals in preparation for ASIC/FPGA development and digital system design.

The projects progress from basic combinational logic to sequential circuits, and ultimately to a custom instruction-driven datapath — modeling the core structure of a CPU.

---

## Tools Used
- Falstad Circuit Simulator

---

## Projects

### `counters/` — 3-Bit Synchronous Counter
- 3-bit counter using T Flip-Flops
- Active-high Reset and Enable control
- Counts on rising clock edge when enabled
- Demonstrates sequential logic and state holding

---

### `fsm/` — Traffic Light Controller (Finite State Machine)
- State machine controlling Red, Yellow, Green light sequence
- Synchronous state transitions using Flip-Flops
- Clear state diagram design and output logic

---

### `alu/` — 4-Bit Arithmetic Logic Unit (ALU)
- 4-bit ALU performing:
  - AND
  - OR
  - XOR
  - ADD (with Carry Out)
- Ripple carry adder for addition
- Output selected using 4-to-1 multiplexers

---

### `datapath/` — 4-Bit Datapath with Register and ALU
- Register stores data with Load Enable control
- ALU performs operations between Register value and external Data In
- MUX selects Register input (Data In vs ALU Output)
- Demonstrates core CPU datapath principles

---

### `control-logic/` — 4-Bit Datapath with Custom Instruction Control
- Full instruction-driven control of datapath
- 4-bit instruction format:
  - `[3:2]` ALU OpCode
  - `[1]` Register Input Select (Data In vs ALU Out)
  - `[0]` Load Enable
- Manual instruction loading via switches
- Demonstrates control unit logic and instruction execution cycle
- Models the architecture of a simple processor core

---

## Author
Daniel Gabai  
Electrical & Computer Engineering Student  
