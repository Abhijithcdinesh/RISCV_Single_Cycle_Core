# RISCV_Single_Cycle_Core
This project implements a single-cycle RISC-V processor in Verilog HDL. It executes one instruction per clock cycle and includes key components such as the Program Counter (PC), Instruction Memory, ALU, Register File, and Data Memory.  
Single-Cycle Core – Executes each instruction in one clock cycle, providing a simple and easy-to-understand design.  

Key Modules

Program Counter (PC) – Holds the current instruction address.  
PC Adder – Computes the next instruction address.  
Instruction Memory – Stores RISC-V machine code instructions.  
ALU – Performs arithmetic and logic operations.  
Register File – Stores CPU registers for computation.  
Data Memory – Handles memory read/write operations  
Supports Basic RISC-V Instructions (Load, Store, ALU Operations, and Branching).  
