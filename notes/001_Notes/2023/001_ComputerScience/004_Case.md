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
INIT income AS FLOAT










END
```











