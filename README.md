Branch Predictor 2-bit

Input: number of entries 
Output範例: 可以供輸入number of entries in BHT


RISCV.txt:

	    li R1,0 
      li R2,4
    Loop:
      beq R1,R2,End
	    addi R2,R2,-1
	    beq R0,R0,Loop //R0就是我們常用的x0唷
    End:

