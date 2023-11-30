# Pipelined-processor-implementation-in-C++
Assignment 2 of the course Computer Architecture at IIT Delhi under Prof. Rijurekha Sen. 

=====================================================================
A. 5 Stage Basic MIPS pipeline without bypassing
=====================================================================
=====================================================================
E. Branch prediction for control hazard [4 marks]
=====================================================================
Implement a branch predictor with 2-bit saturating counters and branch history registers (BHR).
Use 2^14 2-bit saturating counters indexed using 14 LSBs of each branch instruction and a 2 bit
Branch History Register (BHR) that records the outcomes of the previous 2 branches.
branchtrace is a trace of branch instructions consisting of the PC at which each branch occurs,
and whether the branch is Taken(1) or Not Taken(0).
Predict varying the start state of (a) each 2-bit saturating counter between 00,01,10,11 and (b)
each BHR also as 00,01,10,11. Predict using only saturating counters, only BHRs and some
ways of combining the two. For each of these variations, your output file should indicate, for
each branch in the trace, whether it was predicted as Taken(1) or Not Taken(0). Compute
branch prediction accuracy of each output file, as (#correct predictions/#total predictions).
Include these branch prediction accuracies in a table in the PDF report above. Each row in the
table should mention the prediction strategy and the corresponding accuracy.

