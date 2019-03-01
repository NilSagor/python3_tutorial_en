What is Dictionary?
How to create?
How to access elements from a dictionary?
How to change or add elements in dictionary?
How to delete elements from dictionary?
Dictionary comprehensionn:
Membership test
Iterating a dictionary
Interationg though a nested dictionary
    class = {1:{'Name': 'John', 'Age': 27, 'Sex': 'Male'},
			2: {'Name': 'July', 'Age': 26, 'Sex': 'Female'}
			}
	for class_id, class_info in class.items():
		print("\n Person ID:", class_id)

		for key in class_info:
		    print(key + ':', class_info[key])		