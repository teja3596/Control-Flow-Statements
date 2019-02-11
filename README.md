# Control-Flow-Statements
## If-else statement
---
An if else statement is a conditional statement that executes a block of code if a specified condition is true. If the condition is false, another block of code can be executed.

#### Syntax:
```
if(condition):
    statement(s)
else:
    statement(s)
```
#### Example:
```
year = int(input("Enter the year: "))
if year%4 == 0:
    print(year," is leap year.")
else:
    print(year," is not a leap year.")
```
#### Output:
Enter the year: 2019
2019  is not a leap year.
## If-elif..else statement
---
The elif allows to check for multiple expressions. If the condition for if is false, it checks the condition of the elif. If the condition for elif is true, it executes the block of code. If all the conditions are false, the else condition is executed.
#### Syntax:
```
if(condition):
    statement(s)
elif(condition):
    statement(s)
else:
    statement(s)
```
#### Example:
```
a = 20
b = 20
if a > b:
    print('a is greater than b.')
elif a < b:
    print('b is greater than a.')
else:
    print('a equals to b.')
```
#### Output:
a equals to b.

## While Loop
---
Using a while loop we can execute a set of statements as long as a condition is true.
#### Syntax:
```
while condition:
    statement(s)
```
#### Example:
```
n = 0
sum = 0
while n <= 10:
    sum = sum+n
    n+=1
print("The sum of first 10 natural numbers is ",sum)
```
#### Output:
The sum of first 10 natural numbers is  55

## For Loop
---
For loop executes the sequence of code according to the specified times and conditions.
#### Syntax:
```
for a variable in sequence:
    statement(s)
```
#### Example:
```
n = 10
for i in range(1,6):
    print(n*i)
```
#### Output:
10
20
30
40
50
## Continue and Break Statements
---
Using 'Continue' statement we can stop the current iteration, and continues with the next iteration.
Using 'Break' statement we can stop the loop even if the while condition is true.
#### Example for break:
```
list = [10,20,30,40,50,60,70,50]
for i in range(0,len(list)):
    if list[i] == 50:
        break
        i+=1
print('Index is ',i)
```
#### Output:
Index is 4
#### Example for continue:
```
list = [15,30,45,78,90,45,78]
for i in range(0,len(list)):
    if list[i]%2 == 0:
        print(list[i])
        continue
         i+=1
```
#### Output:
30
78
90
78



