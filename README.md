# Pipelined-processor-implementation-in-C++
Assignment 2 of the course Computer Architecture at IIT Delhi under Prof. Rijurekha Sen. 

Implemented the following (detailed problem description in pdf) :

1. **5 Stage Basic MIPS pipeline without bypassing**\n
   Implement in C++ the basic 5 stage MIPS pipeline —
   a. IF (Instruction Fetch)
   b. ID (Instruction Decode)
   c. EX(ALU execute)
   d. MEM (memory read/write)
   e. WB (write back to register)

2. **5 Stage Basic MIPS pipeline with bypassing** 
   Implement 5stage_bypass.cpp, where you forward input to the EX/MEM stages, not just from L3, but from L4 and L5.

3. **7-9 Stage pipeline without and with bypassing**
   Implement the 7-9 stage pipeline where we use 7 stages for ALU operations and 9 stages for
load-store operations.

4. **Branch prediction for control hazard**
   Implement a branch predictor with 2-bit saturating counters and branch history registers (BHR).Use 2^14 2-bit saturating counters indexed using 14 LSBs of each branch instruction and a 2 bit Branch History Register (BHR) that records the outcomes of the previous 2 branches.

