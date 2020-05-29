Branch Predictor 2-bit

Input : number of entries 

Output範例 : 可以供輸入number of entries in BHT


RISCV.txt:

        0x110	    li R1,0

        0x114	    li R2,4

    LoopI:

        0x118	    beq R1,R2,EndLoopI

        0x11C	    addi R2,R2,-1

        0x120	    beq R0,R0,LoopI 

        EndLoopI:


