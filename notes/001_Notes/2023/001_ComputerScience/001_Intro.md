#### Variables
	- Are temporary member address locations

Global - A variable that can be accessed anywhere in the code
Local - A variable that is only available in a single function or part

```
const pi = 3.1412 // constant
let temp = 25 // local var
```


#### Data Types
String - Text
Integer - Whole number
Float - Decimal number
Boolean - True/False


## Pseudocode


Begin
NUM1, NUM2 are FLOAT
INPUT(NUM1, NUM2)
SUM <- NUM1 + NUM2
OUTPUT(SUM)
End


Begin
NUM, NUM1, NUM2, NUM3 are FLOAT
INPUT(NUM1, NUM2, NUM3)

CASE NUM OF:
	NUM1 > NUM2 AND NUM1 > NUM3 : OUTPUT(NUM1)
	NUM2 > NUM1 AND NUM2 > NUM3 : OUTPUT(NUM2)
	NUM3 > NUM2 AND NUM3 > NUM1 : OUTPUT(NUM3)
ENDCASE
End

```
print(max(int(input("> ")), int(input("> ")), int(input("> "))))
```

#### Problem
Write the code for a program that will add 3 numbers entered by the user and then determine if the sum of the numbers is greater than 15. If it is, the program will display a relevant message.


```Pseudocode
BEGIN
NUM1, NUM2, NUM3, SUM AS FLOAT
INPUT(NUM1, NUM2, NUM3)
SUM <- NUM1 + NUM2 + NUM3
	IF SUM > 15 THEN:
		OUTPUT("Greater than 15.")
	ENDIF
END
```


```python
# print("Greater than 15" if (float(input("> ")) + float(input("> ")) + float(input("> "))) > 15)


num1 = float(input("Number 1: "))
num2 = float(input("Number 2: "))
num3 = float(input("Number 3: "))

total = num1 + num2 + num3
if total > 15:
    print("Greater than 15.")

```


## The division method

104/2 = 0
52/2 = 0
26/2 = 0
13/2 = 1
6/2 = 0
3/2 = 1
1/2 = 1

71/2 = 1
35/2 = 1
17/2 = 1
8/2 = 0
4/2 = 0
2/2 = 0
1/2 = 1

99/2 = 1
49/2 = 1
24/2 = 0
12/2 = 0
6/2 = 0
3/2 = 1
1/2 = 1

## The Table Method

125
|           | 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| --------- | --- | --- | --- | --- | --- | --- | --- | --- |
| Binary    | 0   | 1   | 1   | 1   | 1   | 1   | 0   | 1   |
| Sub Total | 125 | 61  | 29  | 13  | 5   | 1   | 1   | 0   |


## Exercise 1
A CD manufacturing company charges Multimedia companies $6.50 per CD if they create less than 1000 copies. If the company requires more than 10000, they only pay $5.00 a copy. Otherwise, they pay $5.70 a copy. Write a program that will allow the company to calculate how much to charge for different jobs they do. Use the extended If..Then..Else statement.

```Pseudocode
BEGIN
INIT copies AS INTEGER
INIT price, total AS FLOAT
INPUT(copies)
IF copies < 1000 THEN:
	price <- 6.50
ELSE IF copies > 10000 THEN:
	price <- 5.00
ELSE THEN:
	price <- 5.70
ENDIF
total <- price*copies
OUTPUT(total)
END
```

```python
copies = int(input("Copies? "))
if copies < 1000:
	price = 6.5
elif copies > 10000:
	price = 5
else:
	price = 5.7
total = copies * price
print(total)
```

## Exercise 2

Write a program that will display 6 different comments based on the results of random numbers from 1 to 6. Use the Select Case statement.

```Pseudocode
BEGIN
INIT num AS INTEGER
num <- RANDOM INT
CASE num OF:
	1 : OUTPUT(1)
	2 : OUTPUT(2)
	3 : OUTPUT(3)
	4 : OUTPUT(4)
	5 : OUTPUT(5)
	6 : OUTPUT(6)
ENDCASE
END
```

```python
import random
num = random.randint(1,6)
match num:
	case 1:
		print(1)
	case 2:
		print(2)
	case 3:
		print(3)
	case 4:
		print(4)
	case 5:
		print(5)
	case 6:
		print(6)
	case _:
		print("ERROR")
```


## Exercise 3
Most countries use a sliding scale income tax program based on the amount of money earned. Here is an example of the tax on an individual’s weekly income:

```Pseudocode
BEGIN
INIT income, tax AS FLOAT
INPUT(income)
CASE income OF:
	<200:
		tax <- 0
	<900:
		tax <- 0 + (income - 100) * 0.28
	<1800:
		tax <- 112 + (income - 500) * 0.32
	<3000:
		tax <- 196 + (income - 1000) * 0.46
	>3000:
		tax <- 656 + (income - 2000) * 0.60
ENDCASE
OUTPUT(tax)
END
```

```python
income = float(input("Income? "))
if income < 200:
	tax = 0
elif income < 900:
	tax = 0 + (income - 100) * 0.28
elif income < 1800:
	tax = 112 + (income - 500) * 0.32
elif income < 3000:
	tax = 196 + (income - 1000) * 0.46
else:
	tax = 656 + (income - 2000) * 0.60

print(tax)

```

## Exercise 1
Print the integers from 1 to 100

```Pseudocode
BEGIN
FOR i = 1 TO 100:
	OUTPUT(i)
NEXT
END
```

```python
for i in range(100):
	print(i)
```



































