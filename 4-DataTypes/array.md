Array is a container which can hold a fix number of items and these items should be of the same type.

important terms of Array:

Element: each item stored in an array is called an element.
Index : Each location of an element in an array has a numrical index, which is used to identify the element.

Array index start with 0
Each element can be accessed via its index

Basic Operations:

Traverse - print all the array element one by one.

Insertion - adds an element at the given index

Deletion - deletes an element at the given index 

Search - Search an element using the given index or by the value

Update - Updates an element at the given index


in python, array is created by importing array module to the python program


	from array import *

	arrayName = array(typecode, [initializers])

For example

	from array import *

	arrayName = array('i', [10, 20, 30, 40])

	for x in arrayName:
		print(x, end = ' ')

output: 10 20 30 40 

