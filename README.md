Kebish Pius - kep259
Pitt Email: kep259@pitt.edu

My project works with all the test cases and I believe that all the instructions properly work. The design is messy but I believe that every instruction does work. There is a subcircuit with my control unit. My Instruction fetch is at the bottom and the LED is to the right

Control Signals
1. MemtoReg (2 bits) - This decides what to store to the register file. (00) - ALU Result, (01) - RAM Memory, (10) - HI, (11) - LO
2. Branch Type (2 bits) - This determines whether it is a bp, bx, bn, or bz. (00) - bp, (01) - bn, (10) - bz, (11) - bx
3. Put (1 bit) - Determines if it is a put operation
4. RegWrite (1 bit) - Write Enable signal for register file
5. ALU Src (1 bit) - Chooses between the immediate or DataRB(Data B from register file). (0) - DataRB, (1) - Immediate
6. ALU OP (3 bits) - Decides the operation to perform in the ALU - (Codes given in project) 
7. Halt (1 bit) - Determines if it is a halt operation and freezes the PC
8. is_jump (1 bit) - Determines if the instruction is a jump. (1) - Jump, (0) - No jump
9. Memwrite (1 bit) - Determines if we need to write to memory. (0) - No, (1) - Yes
10. is_branch (1 bit) -  Determines if the instruction is a branch. (0) - No Branch, (1) - Branch

I started the project a little later than I would have liked cause I was busy with a bunch of things. However, I was able to quickly get the ALU and Regfile done. Most of the struggle came with the instructions and phase 2. 
