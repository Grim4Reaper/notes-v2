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





END
```

```python



```






