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













