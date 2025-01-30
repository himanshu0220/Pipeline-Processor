# PIPELINE PROCESSOR DESIGN

COMPANY NAME : CODTECH IT SOLUTION

NAME : HIMANSHU ARUN DAHAKE

INTERN ID : CT08IPL

DOMAIN : VLSI

BATCH DURATION : January 5th, 2025 to February 5th, 2025

MENTOR NAME : NEELA SANTOSH

# DESCRIPTION

A 4-stage pipelined processor is a simple yet efficient design that enhances the execution speed of instructions by breaking down the instruction cycle into four sequential stages. This approach increases throughput by allowing multiple instructions to be processed simultaneously at different stages.

Designing a 4-stage pipelined processor with basic instructions (ADD, SUB, AND, LOAD) involves implementing the following pipeline stages:

1. Fetch (IF) – Fetches the instruction from memory.
2. Decode (ID) – Decodes the instruction and reads registers.
3. Execute (EX) – Performs arithmetic or logical operations.
4. Write Back (WB) – Writes results back to registers.

Pipeline Working Mechanism:

At every clock cycle, a new instruction enters the pipeline while previous instructions progress through their respective stages. This enables overlapping execution, where multiple instructions are executed in parallel, increasing efficiency.
For example:
At Cycle 1, ADD R1, R2 is fetched.
At Cycle 2, ADD moves to decode while SUB R2, R3 is fetched.
At Cycle 3, ADD moves to execute, SUB moves to decode, and AND R0, R1 is fetched.
The process continues, with new instructions entering at each clock cycle.


