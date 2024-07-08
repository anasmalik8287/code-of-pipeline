# code-of-pipeline
This repository contains a Verilog implementation of a pipelined MIPS32 processor. The design includes the five stages: Instruction Fetch (IF), Instruction Decode (ID), Execute (EX), Memory Access (MEM), and Write-Back (WB).

Description
The MIPS32 pipeline simulator supports basic arithmetic, logical, memory, and branch operations. It is designed to illustrate the behavior of a basic pipelined processor.

Features
Five-Stage Pipeline: IF, ID, EX, MEM, WB stages.
Instructions Supported: ADD, SUB, AND, OR, SLT, MUL, ADDI, SUBI, SLTI, LW, SW, BEQZ, BNEQZ, HLT.
Hazard and Control Handling: Simple mechanisms to handle pipeline hazards.
