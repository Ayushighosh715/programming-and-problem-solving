## Problem Statement
Write a Python program to check if a given date is valid. If the date is valid, print the next day's date (incremented date). If the date is invalid, print "Invalid Date".

## Algoritm
1. Start
2. Input day, month, year
3.  Check if year > 0 and month is between 1 and 12
  If not → Print "Invalid Date" and Stop
4. Find maximum days in the given month
31 days → Jan, Mar, May, Jul, Aug, Oct, Dec
30 days → Apr, Jun, Sep, Nov
February → 28 days (29 if leap year)
5. If day is not between 1 and max days → Print "Invalid Date" and Stop
6. Increment date
If day < max days → day = day + 1
Else if month < 12 → day = 1, month = month + 1
Else → day = 1, month = 1, year = year + 1
7. Print new date (DD-MM-YYYY)
8. Stop


## Flowchart 
![Flowchart]()

--

## Execution
<p align="center">
  <img src="Increment Date.png" width ="900">
</p>
