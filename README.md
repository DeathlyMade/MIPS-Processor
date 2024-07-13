
# MIPS Processor

MIPS Processor is a project focused on simulating both pipelined and non-pipelined MIPS processors. This simulation addresses various control, structural, and data hazards effectively, providing a comprehensive understanding of MIPS architecture and pipeline processing.








## Project Overview

The MIPS Processor project aims to provide an educational tool for understanding the workings of both pipelined and non-pipelined MIPS processors. By simulating these processors, the project demonstrates how different types of hazards (control, structural, and data) are detected and resolved, offering insights into the complexities of processor design and operation.



## Features

- Non-Pipelined MIPS Processor Simulation: Simulates the basic operations of a MIPS processor without pipelining.
- Pipelined MIPS Processor Simulation: Simulates a MIPS processor with pipelining, showing how instructions are processed in stages.
- Hazard Detection and Resolution: Effectively detects and resolves control, structural, and data hazards.
- Instruction Execution Visualization: Provides a clear visualization of how instructions are executed in both pipelined and non-pipelined processors.
- Performance Metrics: Offers performance metrics to compare the efficiency of pipelined vs non-pipelined processing.



## Architecture
The project is divided into several key components:

1. Instruction Fetch (IF): Fetches the next instruction to be executed from memory.
2. Instruction Decode (ID): Decodes the fetched instruction and reads necessary registers.
3. Execute (EX): Performs arithmetic or logical operations.
4. Memory Access (MEM): Accesses data memory for load and store instructions.
5. Write Back (WB): Writes the results back to the register file.
### Hazards and Their Resolution
- Control Hazards: Managed using techniques like branch prediction and delayed branching.
- Structural Hazards: Addressed by designing the hardware to avoid resource conflicts.
- Data Hazards: Handled using forwarding, stalls, and pipeline interlocks.