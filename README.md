# Basic-Computer

## Overview

The objective of this project is to design and implement a basic CPU system using Verilog. The project was developed in two main phases:

- **Phase 1:** Focused on building the Arithmetic Logic Unit (ALU) and associated components.
- **Phase 2:** Involved creating the CPU system that integrates the ALU and can execute a set of 32 distinct instructions.


## Phase 1: ALU System

### Description

In the first phase, we implemented the Arithmetic Logic Unit (ALU) and several registers and register files. 
### Key Components

- **Registers and Register Files:** Implemented various registers to hold data and perform different operations on it.
- **ALU:** Designed to handle multiple arithmetic, logic and shift operations.

**Note:** The memory module and helper were provided as part of the project specifications and were not implemented by us.

### Details

For an in-depth explanation of the ALU design and functionality, please refer to [Report-1](./Report-1.pdf).

## Phase 2: CPU System

### Description

In the second phase, we integrated the ALU into a CPU capable of executing 32 different instructions. This involved creating a control unit to generate the necessary signals for executing each instruction and managing the data flow within the CPU.

### Details

For a comprehensive overview of the CPU design and its implementation, please refer to [Report-2](./Report-2.pdf).

## Remarks
Sign Extension in ALU: Initially, we implemented sign extension for 8-bit operations. However, in Phase 2, we modified this to zero extension as per the project requirements.

Assumptions: The project was implemented with some assumptions regarding system behaviors. These assumptions are documented in the respective reports.






