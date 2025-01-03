# Sync-Ram-Module
## Simple Synchronous of RAM Module with read & write operations : This repository contains the implementation of a simple synchronous RAM (Random Access Memory) module in Verilog. The module supports both read and write operations
## NAME : MADHURA MAHESH PAWAR
## COMPANY : CODTECH IT SOLUTIONS PVT.LTD
## INTERN ID : CT08FEE
## DOMAIN : VLSI
## MENTOR : NEELA SANTOSH KUMAR 
## FEATURES: Clock Synchronous Design All operations are performed in synchronous with a clock signal.
## STEPS INVOLVED:
1.Source code for the RAM module.
2.Testbench code to validate the module functionality.
3.Supporting scripts for simulation and synthesis 
## TESTING : 
Read and write operations.
## SIMULATION REPORT :
  After running the simulation, you should observe the following:

  Write Operations: When we is asserted (set to 1), the data (din) is written to the specified address (addr).

  Read Operations: When we is de-asserted (set to 0), the data at the specified address (addr) is read and appears on 
  the output (dout).

  For the given testbench, you should see:

  0xAA is written to address 0x0.

  0x55 is written to address 0x1.

  Reading from address 0x0 yields 0xAA.

  Reading from address 0x1 yields 0x55.

  Reading from an unwritten address (e.g., 0x2) will give an undefined value (likely 0x00).
