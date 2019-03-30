Stack is an ordered collection of items where items are add to and removed from the end called the "top". Stacks are ordered LIFO i.e. Last In First Out.

Stack() creates a new stack thaat is empty. It needs no parameters and returns an empty stack

push(item)  adds a new item to the top of the stack. It needs the item and returns nothing.

pop() removes the top item from the stack. It needs no parameters and returns the item.

peek() returns the top  item from the stack but does not remove it. It needs no parameters. the stack is not modified.

is_empty() tests to see whether the stack is empty. It needs no parameters and returns a boolean value.

size() returns the number of itemms on the stack. it needs no parameters and returns an integer




	class Stack:

		def __init__(self):
			 '''initialize the new empty stack(). it needs no parameters'''
			 self.items = []

		def is_empty(self):
			''' tests to check whether the stack is empty. it needs no parameters and return a boolean value'''
			return self.items == []

		def push(self, item):
			''' adds a new item to the top of the stack. It needs the items and returnn nothing'''
			self.items.append(item)

		def pop(self):
			''' removes the top item from the stack. it needs no parameters and returns the item '''
			return self.item.pop()

		def peek(self):
			''' returns top item from the stack but does  not remove it. it needs no parameters and the stack is not modified '''
			return self.items[len(self.items) -1]

		def size(self):
			''' returns the number of items on the stack. It needs no parameters and returns an integer'''
			return len(self.items)


we must create a stack object and then use it. like this


	s = Stack()
	# output True
	print(s.is_empty())
	s.push(4)
	s.push('dog')
	# output 'dog'
	print(s.peek())
	s.push(True)
	s.push(8.4)
	# output 4
	print(s.size())
	#output 8.4
	print(s.pop())
	# output True
	print(s.pop())

	print(s.size())













