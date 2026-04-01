## Problem Statement
Write a Python program to manage a phone number database using a dictionary. The dictionary stores contact names as keys and phone numbers as values.

----

##Code

n = int(input())
contacts = {}

for _ in range(n):
	cmd = input().split()

	if cmd[0] == "ADD":
		contacts[cmd[1]] = cmd[2]

	elif cmd[0] == "REMOVE":
		if cmd[1] in contacts:
			del contacts[cmd[1]]

	elif cmd[0] == "DISPLAY":
		if len(contacts) == 0:
			print("No contacts")
		else:
			for name in sorted(contacts):
				print(f"{name}: {contacts[name]}")

----

## Algorithm 

