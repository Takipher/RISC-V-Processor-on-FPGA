# RISC-V-Processor-on-FPGA
A step-by-step educational RISC-V CPU implemented in Verilog.
For learners, by a learner — to understand **how processors really work** at the hardware level.

Not optimized. Not industrial. Just clean, testable, and pedagogical.
I'm not an expert. This project is a way for me to understand RISC-V by building it from the ground up — and maybe help others do the same.


If you like the content, feel free to star the repo and sharing it! 

---

## What is a RISC-V CPU ?

It is a CPU based on the RISC-V architecture, an open, modular, and royalty-free instruction set architecture. 

- RISC -> A family of processor that follow the principles of simple and reduced instructions set, aiming for efficiency and performance.
- V -> Stands for the fifth generation of RISC architectures, following predecessors like MIPS, SPARC, and others.

---

## Why a RISC-V CPU ?

Because others architectures was :

| Problem                      | Example                                           | 
| ---------------------------- | ------------------------------------------------- |
| **Closed / Proprietary**  | ARM, x86: expensive licenses, inaccessible specs |
| **Too Complex**           | x86 = overloaded with historical legacy          |
| **Not Modular**           | hard to adapt to specific needs                  |

---

## Build Plan

This CPU will be constructed in **incremental steps**, each with simulation, waveform, and explanation.

- [x] Step 1 — Instruction Fetch (PC + IMEM)
- [ ] Step 2 — Instruction Decode + Immediate Generator
- [ ] Step 3 — Register File (read/write ports)
- [ ] Step 4 — ALU + Control Signals
- [ ] Step 5 — Branch Logic + PC Update
- [ ] Step 6 — Memory Access Unit (DMEM)
- [ ] Step 7 — Writeback Logic
- [ ] Step 8 — Top-Level CPU (Single-Cycle)
- [ ] Step 9 — Deployment on FPGA (Nexys Video)


