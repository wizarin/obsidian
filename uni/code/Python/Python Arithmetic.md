PEMDAS operators are used with int and float data types
Integers are whole numbers
Floats are represented using a fixed amount of space - 64 binary digits. This is a limitation which leads to inaccurate arithmetic due to not being able to represent the whole number.
0.3333 * 3 = 1
but with float it equals 0.99999 because we can't represent 1/3 accurately.

Operators need an operand on either side to work.

Parenthesis                         ()
Exponent                            **
Multiplication, Modulus     * , %
Division                               /
Addition                             +
Subtraction                         -

Modulus (%) gives the integer remainder of an integer division
Floor division (//) rounds the result down to the nearest integer, also known as integer division, as opposed to float division (/)

**Built-in numeric functions**
round(value, significant figures)
	rounds the input to the nearest integer
abs(value)
	 returns the absolute value (the positive value) of the input
pow(value1,value2)
	value1 to the power of value2
range()
	creates a range of integers between two given values
type()
	returns the data type of the given value
