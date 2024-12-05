[[base]] 2
0 or 1 is the total range of single units, in decimal this is 0 or 1 or 2 ... or 9

Decimal to Binary:
	Divide number by 2 and record remainder, either 0 or 1. The remainders from first to last read a binary number from left to right.
Binary to [[hex]]:
	Convert a single digit of hex into a 4-bit binary number. as a single digit is between 0 and 15, the size range of a 4-bit number.
	
***binary arithmetic***
**Addition:**
	0 + 0 = 0
	0 + 1 = 1
	1 + 0 = 1
	1 + 1 = (10) 0 carry 1

**Multiplication:**
	0 x 0 = 0
	1 x 0 = 0
	0 x 1 = 0
	1 x 1 = 1
![[binary_multi.png]]

**Subtraction:**
	0 - 0 = 0
	1 - 0 = 1
	1 - 1 = 0
	10 - 1 = 1

**Division:**
	same as decimal long division

**Addition, Subtraction using logic gates**
![[adder_subtractor.png]]

**Most Significant Bit - MSB**
The MSB is the far left bit in a byte, the one that denotes the highest value.
The MSB is used to signify the **Sign Magnitude** of the binary number. The sign magnitude refers to whether the number is positive(0) or negative (1). Like this; 01101011 or 10000001 11010111