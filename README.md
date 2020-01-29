# Verilog-Labs
* A collection of labs that were done for the ECE244 Digital Systems course. To be used on DE1-SoC FPGA Boards.
* DE1-SoC.qsf file must be imported first for board pin assignments.

## Lab3Part1
* Using always blocks and case statements to implement a 6-to-1 Multiplexer

## Lab3Part2
* A 4 bit Full Adder

## Lab3Part3
* A 6-to-1 multiplexer that is cable of doing the following:
	
		case 0: A + B using the adder from Part II of this Lab (ripple-carry adder)
		case 1: A + B using the Verilog ‘+’ operator
		case 2: A XNOR B in the lower four bits of ALUout and A NAND B in the upper four bits
		case 3: Output 8’b0001111 if at least 1 of the 8 bits in the two inputs is 1 (use a single OR operation)
		case 4: Output 8’b1110000 if exactly 1 bit of the A switches is 1, and exactly 2 bits of the B switches are 1
		case 5: Display the A switches in the most significant four bits of ALUout and the complement of the B switches in the least significant four bits without complementing the bits individually
