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
* Output is displayed on the seg7 display

## Lab4Part2
* Using the multiplexer from Lab3Part3 and adding in the ability for data to be stored in a register

## Lab4Part3
* Building a rotating register that allows for shifting of bits
* Option to rotate bits or apply an arithmetic shift to the bits

## Lab5Part1
* A simple 4 bit synchronous counter using 4 T flip-flops that operates off user input

## Lab5Part2
* A 4 bit counter that counts on its own and is cable of going at 4 different speeds (1/sec, 2/sec, 0.5/sec and 50million/s)

## Lab5Part3
* A morse code encoder that uses the LEDs to output the code for letters I-P

## Lab6Part1
* A finite state machine(FSM) used to detect when the pattern "1111" or "1101" is detected in the users input

## Lab6Part2
* A finite state machine that is used to calculate "Ax^2 + Bx + C" where A, B, C, and x are inputted by the user

## Lab7Part1 
* A memory module that is able to write/read to/from specific addresses

## Lab7Part2
* Displaying a 4x4 pixel square onto a specified location and with a specified colour on the VGA display
