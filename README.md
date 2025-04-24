# 19CS301--Module-1
Exp.No:1(a)	PYTHON BASICS-PRINTING MULTILINE STRING

### AIM
To create a python program to print the string in multiline using triple quotes.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Use triple quotes (''' or """) to define a string that spans multiple lines.

Step 3:	 Use the print() function to display the multi-line string.

Step 4:	 Terminate the program

### PROGRAM
```string_single_quotes = '''I am a string literal
... has more than one
... line
....placed inside triple single quotes'''


string_double_quotes = """I am a string literal
... has more than one
... line
....placed inside triple double quotes"""


print(string_single_quotes)
print(string_double_quotes)
```
### OUTPUT
![image](https://github.com/user-attachments/assets/61c091af-7bf7-496e-98d7-5d1039b10e4e)


 
### RESULT
Thus the python program for printing multiline strings has been implemented and executed successfully.

Exp.No:1(b)	DATA TYPES-PYTHON PROGRAM TO PRINTING INTEGER LITERALS

### AIM
To write a python program to print the following integer literals 123,456,789
### ALGORITHM
Step 1:	Begin the program.

Step 2:	Initialize the integer literals 123, 456, and 789.

Step 3:	Use the print() function to display the numbers 123, 456, and 789.

Step 4:	Terminate the program.

### PROGRAM
```num1 = 123
num2 = 456
num3 = 789
print(num1)
print(num2)
print(num3)
```
### OUTPUT
![image](https://github.com/user-attachments/assets/c1420ca6-469e-4a77-91cc-4cf807111aca)

 

### RESULT
Thus the python program for printing the Integer Literals has been implemented and executed successfully.






Exp.No:1(c)	VARIABLES AND EXPRESSIONS, OPERATORS ADDING TWO COMPLEX NUMBERS

### AIM
To write a python program for adding two complex numbers, get the user input using the eval() function.
### ALGORITHM
Step 1:	Begin the program.

Step 2:	Use eval() to get two complex numbers as input from the user.

Step 3:	Print the complex numbers entered by the user.

Step 4:	Perform the addition of the two complex numbers using + operator.

Step 5:	Print the sum of the two complex numbers.

Step 6:	Terminate the program.

### PROGRAM
```
A = eval(input())
B = eval(input())

print(f"A is {A}")
print(f"B is {B}")

sum_complex = A + B

print(f"Sum is {sum_complex}")
```
### OUTPUT

 ![image](https://github.com/user-attachments/assets/a1c12175-0dee-4aa1-885f-9e7dc870f2dd)

### RESULT
Thus the python program for  adding two complex numbers has been implemented and executed successfully.


Exp.No:1(d)	CONDITIONAL STATEMENTS- CHECKING VOWEL OR NOT

### AIM
To Write a Python program to check whether the given character is a vowel or not using if..else statement
### ALGORITHM
Step 1:	 Begin the program.

Step 2:	 Take a character input from the user

Step 3:	 Convert the character to lowercase

Step 4:	 Check if the lowercase character is one of the vowels: 'a', 'e', 'i', 'o', 'u'

Step 5:	 If it is a vowel, display "The given character is a vowel"

Step 6:	 Otherwise, display "The given character is NOT a vowel"

Step 7:	 Terminate the program.

### PROGRAM
```char = input("Enter a character: ")
char_lower = char.lower()
if char_lower in ['a', 'e', 'i', 'o', 'u']:
    print("The given character is a vowel")
else:
    print("The given character is NOT a vowel")
```
### OUTPUT 
![image](https://github.com/user-attachments/assets/c8b79e3c-6d44-4da2-b72a-461b3e03cfee)


### RESULT
Thus the python program to check whether the given character is a vowel or not using if..else statement  has been implemented and executed successfully.





Exp.No:1(e)	SEB- MINIMUM OF THREE NUMBERS

### AIM
To write a program to find a minimum between three integer numbers using conditional Expression(Ternary).
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Read the three numbers: num1, num2, and num3 from the user.

Step 3:	 Compare num1, num2, and num3 to find the smallest number:

Step 4:	If num1 is less than or equal to both num2 and num3, then num1 is the minimum.

Step 5:	Else, if num2 is less than or equal to both num1 and num3, then num2 is the minimum.

Step 6:	 Otherwise, num3 is the minimum.

Step 7:	 Print the minimum value along with the input numbers in the format: "The minimum of num1, num2, num3 is min_num."

Step 8:	 Terminate the program.
### PROGRAM
```
num1=int(input())
num2=int(input())
num3=int(input())
min_num=num1 if(num1<=num2 and num1<=num3) else num2 if(num2<=num1 and num2<=num3) else(num3)
print(f"The minimum of {num1}, {num2}, {num3} is {min_num}")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/64e607d4-916a-4df8-b2f4-450f68295884)

 
### RESULT
Thus the python program for finding a minimum of three numbers has been implemented and executed successfully.

