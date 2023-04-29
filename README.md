# 16-bit-basic-computer-using-logic-gates
Simulation done using Logisim open source software

The purpose of this project is to make a completely working basic computer using Logisim open source software. The implemented is of a 16-bit basic computer with mainly eight different registers. Below, a demonstration of how the controls where derived will be shown along with how it all connects together to form one complete basic computer. The basis on which these controls and gates where connected comes from multiple figures found in the Morris Mano 3rd edition text book. Figure 5-3 gave us an idea on the size of each of the main registers while figure 5-4 was used to tell how it all connected together and whether each register has specific inputs such as increment or clear. Table 5-2 was used at the end of the project design, when the circuit was complete, to test different direct and indirect functions such as clear accumulator, circulate left of right. Tables 5-3, 5-4 and 5-5 where used to formulate logic equations, this was simply done by choosing a register, for instance AC and seeing what was the equivalent to it in input combinations. One example of AC’s formula is rB8 and rB9. After these steps where repeated for all registers, drawing on Logisim started. The Logisim circuit relies on bit by bit design to make it easier to understand. The problem was that it was more work but guaranteed. To speed up the drawing processes, things such as 1-bit ALU was made the duplicated to make a 2-bit ALU. The 2-bit ALU was used to make an 8-bit that finally led to making the 16-bit ALU used in our main circuit. The register chips where placed in the main after completion. Each register chip had it own number of input. The input of each register came from their respective control chip. The memory was loaded with instructions and values and an output is displayed at the LEDs.
