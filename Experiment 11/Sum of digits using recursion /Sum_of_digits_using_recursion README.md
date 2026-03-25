## Problem Statement
Write a recursive function sum_of_digits_recursive(n) that calculates the sum of the digits of a given non-negative integer n.

---
## Code 
def sum_of_digits_recursive(n):
	if n ==0:
		return 0
	else:
		return n % 10 + sum_of_digits_recursive(n // 10)

number = int(input())
result = sum_of_digits_recursive(number)	

print(sum_of_digits_recursive(number))
