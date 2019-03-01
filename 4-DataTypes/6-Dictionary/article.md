What is Dictionary?

How to create?

Each element in a dictionary is represented by a key:value pair
key must be of immutable(string, number or tuple) and must be unique.
value can be of any data type and repeat

	# empty dictionary
	my_dict={}
	
	# with integer key
	my_dict = {1:'pen', 2:'pencil'}

	# with mixed keys 
	my_dict = {'name' : 'John', 2:[1,2,3]}


In python, dictionary creates with

How to access elements from a dictionary?

How to change or add elements in dictionary?

How to delete elements from dictionary?

Dictionary comprehensionn:

Membership test

To determine whetehr a key is in a dictionary, we use in and not in
Membership test only for keys, not for values

	#initiate a Dictionary variable
	squares = {1:1, 2:4, 3:9, 5:25, 7:49, 9:81}

	#output: True
	print(1 in squares)

	# output: True
	print(6 not in squares)

	#output: False
	print(4 in squares)

	# membership test only for keys, not for value
	# output: False
	print(49 in squares)
Iterating a dictionary

Interationg though a nested dictionary

	class = {1:{'Name': 'John', 'Age': 27, 'Sex': 'Male'},
		2: {'Name': 'July', 'Age': 26, 'Sex': 'Female'}
		}

	for class_id, class_info in class.items():
		print("\n Person ID:", class_id)

		for key in class_info:
		    print(key + ':', class_info[key])		