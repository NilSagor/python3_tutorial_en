1.
Read the problem at least three times(or however many times I feel comfortable).
explain to others see if he/her understanding of my explanation match the problem or not

think like:
-- how can a computer tell what is an even number?
-- what am I passing into this function? [an Array]
-- what will the data types of the elements in the array? [Number] 
-- what is the goal of this function? what am I returning at the end of this function?
[the goal is to take all the even numbers, return an empty array]

2.
Work through the problem manually with at least three sets of sample data

Try out large set of data. maximum and minimum variable data

ex 	[1] one element
	[1, 2] two elements
	[1, 2, 3, 4, 5, 6] multiple elements
	[-1, 0, 1, 2] negative and zero value elements
	[-800.10, 1, 2, 800.36 300] floating point value elements

-- i. 	First look at the only element [1]
-- ii. 	Decide if it is even, it is not
-- iii. Notice there is no more elements in the array
-- iv. 	Determine there are no even numbers in this provided array.
-- v. 	Return an empty array
--  	Now 2nd Sample let's go through the array [1, 2]
-- i. 	Look at the first element in array [1, 2]
-- ii. 	it is 1
-- iii. Decide if it is even, it is not
-- iv. 	look at the next element in the array
-- v. 	It is 2
-- vi. 	Decide if it is even, it is even
-- vii. Make an array evenNumbers and add 2 to this array
-- xi. 	Notice that there are no more elements in this array
-- x. 	Return the array evenNumber which is [2]

Try different sets with large data [Max and min elements]

3. 
Simplify and optimize steps

Looking for patterns and seeing if there's anything I can generalize. Seeing if I can reduce any steps or if I am repeating any steps

--  1. create a funciton selectNumbers
-- 	2. Create a new empty array evenNumbers where I will store even numbers, if found any
-- 	3. Go through each element in the array [1, 2]
-- 	4. Find the first element
-- 	5. Decide if it is even by seeing if it is divisible by 2. if it is even, I will add that to evenNumbers array
-- 	6. Find next element
-- 	7. Repeat step #4
-- 	8. Repeat step #5 and #4 until there are no more elements in this array
-- 	9. Return the array evenNumbers regardless of whether it has anything in it.

		like n = 1, n = 2, ... ....
		Suppose it is true for n = k
		prove it is true for n = k + 1

4. 
Write Pseudocode line by line by focus logic and steps [ forget about  syntax]

		function selectNumbers
		create an array evenNumbers and set that equal to an empty array
		for each element in that array
			if that element is even 
				if element is even (if there is no remainder when divided by 2)
					add that to array evenNumbers

		return evenNumbers

5. 
Translate Pseudocode into code and debug:

6. 
Simplify and optimize

7.
Debug

8.
Write useful comment

9.
 






