# G-CPU-Assembly-Programming

## Overview

This project focuses on assembly programming using the G-CPU integrated development environment (G-IDE). The primary objectives were to understand the workings of the G-CPU, write assembly code to manipulate data between ROM and SRAM, and simulate the program using Quartus. Additionally, the project involved hand-assembling the program and verifying it on the DE-10 Lite board.

## Project Details

### Pre-Lab Requirements

- **Design and Simulation:**
  - Open and edit the `eprom.mif` file to define the program that the G-CPU will execute.
  - Load data into registers X and Y, treating them as pointers to addresses.
  - Load data into register A from the address pointed to by X, transfer it to register B, and store it at the address pointed to by Y.
  - The process involves looping through the instructions until a specified condition is met.
  - Functional simulation was conducted using Quartus, with results compared to hand-simulation.

### Assembly Program

The main task was to write an assembly program to XOR pairs of numbers and store the results in an output table in SRAM. The input data was located in ROM, and the output data was stored in SRAM.

**Key Operations:**
- Registers X and Y were used to point to the input and output data.
- Register A served as a loop counter, while Register B was used for performing calculations.
- The program was assembled and tested using G-IDE.

### Hand Assembly

- The program was hand-assembled, and the results were compared with the G-IDE generated code to ensure accuracy.
- The `list` file included addresses, opcodes, assembly language instructions, and comments for each instruction.
<img width="649" alt="Hand Assembly Program" src="https://github.com/user-attachments/assets/c13bae18-2721-4d7e-b6d5-64f836560c1e">


### Simulation and Verification

- The program was tested by modifying data in `sram.mif` and `eprom.mif`, and the simulation results were compiled and analyzed.
- The final program was loaded onto the DE-10 Lite board for hardware verification, comparing the results with hand-simulation and Quartus simulation.

## Requirements

- **G-IDE Version:** G-IDE-Full-v1.4
- **Hardware:** DE-10 Lite FPGA Board
- **Software:** Quartus Prime Lite Edition

## Future Work

This project provided a solid foundation in assembly programming and insights into the workings of the G-CPU. Future applications could include developing custom instructions for the G-CPU and exploring hardware programming for microprocessors.

## Video Demonstration

A video demonstration of the project can be found [here](https://www.dropbox.com/scl/fi/80w5dubgb4jt8yq5nul4a/IMG_0129.MOV?rlkey=5pht6qq1d4gmpx7kdccq0dhyi&st=klr0f9kz&dl=0).
