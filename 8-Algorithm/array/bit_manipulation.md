A binary system has only two states Logic "0" abd Logic "1" giving a base of 2
A decimal systems uses 10 different digits, 0 to 9 giving it a base of 10
A binary system is a weighted number who's weighted value increases from right to left
the weight of a binary digit doubles from right to left
a decimal number can be converted to a binary number by using the sum of weights method or the repeated division by 2 metod
when we convert numbers from binary to decimal or decimal to binary subscripts are used to avoid errors
when converting decimal number to binary numbers it is important to remember which is the least significat bit (LSB) and which is the most significant bit (MSB)


Any numbering system can be summerized as:

N = b subscripts(i) q superscript(i)

where 

N is a real positive number
b is the digit
q is the base value
integer i can be positive, negative or zero

N = b(i)q(i).....b3q3 + b2q2 + b1q1 + b0q0+b(-1)q(-1)+b(-2)q(-2)+... etc

Decimal Numbering System:

Each integer number column has values of units 10, 100, 1000 etc and move along the number from right to left.

Mathmatically the number written as 



Converting integer into binary

--- Start with the integer in question

--- Divide it by 2

--- Notice of the quotient and remainder

--- Conitnue dividing the quotient by 2 until get quotient of zero

--- then just write out the ramainders in the reverse order

	12 / 2 = 6 + 0
	6 / 2  = 3 + 0
	3 / 2  = 1 + 1
	1 / 2  = 0 + 1

12(10) ====> 1100(2)

Converting Decimal fraction into binary

--- Start with the fraction in question

--- Multyply by 2 until get a resulting fractional part to 0

--- then just write out the integer parts from the results of each multiplication
		
		0.375 x 2 = 0 + 0.75
		0.75 x 2 = 1 + 0.5
		0.5 x 2 = 1 + 0
		0. 375(10) ======> 0.011(2)


Converting binary integer to decimal

--- Start from the left

--- Take the current total

--- multiply it by 2 and add the current digit

--- Continue until there are no more digits left

		1011 
      left digits  current digits x 2
		1 			+ 0 x 2 			= 1
		0 			+ 1 x 2 			= 2
		1 			+ 2 x 2 			= 5
		1 			+ 5 x 2 			= 11 

		1011(2) =======> 11(10)


Converting fraction integer to decimal

--- Start from the right with the total of 0
--- take current total, add current digit and divide the result by 2 [replace divide by 1/2 multiplication] 
--- continue until there are no more digits left


		0.1011(2) =====> 

		 (1 + 0) x 1/2 = 0.5
		 (1 + 0.5) x 1/2 = 0.75
		 (0 + 0.75) x 1/2 = 0.375
		 (1 + 0.375) x 1/2 = 0.6875



Operations  with bits are used in Data compression (Data is compresses by converting it from one representation to another, to reduce the space). Exclusive or Encryption (an algorithm to encrypt the data for safety issues). In order to encode, decode or compress files we have to extract the data at bit  level. 

Bitwise Operations are faster and close to the system and sometimes optimize the program to a good level.

Bitwise oprators:

there are different bitwise operations used in the bit manipulation. these bit operations operate on the individual bits of the bit patterns. Bit operations are fast and can be used in optimizing time complexity. Some common bit operators are:

NOT(~): Bitwise NOT(~) is an unary operator that flips the bits of the number i.e. if the ith bit is 0. it will change it to 1 and vice versa. Bitwise Not is nothing but simply the one's complement of a number. Lets take an example.

		N = 5 (101)2
		~N = ~5 = ~(101)2 = (010)2

AND(&): Bitwise AND is a binary operator that operates on two equal length bit patterns. if both bits in the compared position of the bit patterns are 1, the bit in the resulting bit pattern is 1, otherwise 0

		A = 5 = (101)2
		B = 3 = (011)2

		A & B = (101)2 & (011)2 = (001)2 = 1



OR(|): Bitwise OR is also a binary operator that operates on two equal length bit patterns, similar to bitwise AND. if both bits in the compared position of the bit patterns are 0, the bit in the resulting bit pattern is 0, otherwise 1.

		A = 5 = (101)2, B = 3 = (011)2   
		A | B = (101)2 | (011)2 = (111)2 = 7

XOR(^): Bitwise XOR also takes two equal length bit patterns. if both in the compared position of the bit patterns are 0 or 1, the bit in the resulting bit pattern is 0, otherwise 1

		A = 5 = (101)2, B = 3 = (011)2
		A^B = (101)2 ^ (011)2 = (110)2



