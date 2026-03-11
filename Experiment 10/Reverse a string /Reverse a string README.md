#Program statement"
Write a Python program which prints the reverse of a given input string. Use a function with name reverse_string() and call this function for performing the reversing operation.

#Code#

def reverse_string(s):
	return s[::-1]

user_input = input("Enter a string: ")
result = reverse_string(user_input)
print(f"Original String: {user_input}")
print(f"Reversed String: {result}")

#Algorithm#
