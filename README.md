# 4BitCPU
A 4Bit CPU which was generated using Verilog and completely gate level logic, below is the description and requirements of the program: 
Design and implement in Verilog a simple 4-bit CPU. First you have to build (or use) the following modules:

-9-bit instruction register using nine D flip-flops. Include a clock pulse input that goes to all D flip-flops. Use gate level modeling.

-4-bit ALU. This is the module you have implemented in Project 2 (This is the embedded ALU which processes all of the computation that can be found in the code).

-Control module. This module takes the instruction OP code and outputs the Quadruple mux selection (Sel) and the ALU control code (ALUctl). Use the logic of the control module in 4-bitCPU.vl and implement it at gate-level.

-Quadruple 2x1 multiplexer (multiplexing 4-bit data) needed for the Writedata input of the register file. Use gate level modeling. 

