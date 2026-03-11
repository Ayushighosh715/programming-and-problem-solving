#program Statement#
Write a Python program to remove all punctuation marks from a given string and print the resulting string.
Punctuation marks are special characters that are not letters, digits, or spaces.
The program should keep all letters (uppercase and lowercase), digits, and spaces, but remove all punctuation marks.

#Code#

str = input()

new_st =""

for ch in str:
	if ch.isalnum() or ch.isspace() :
		new_st = new_st + ch

print(new_st)

#Algorithm#

