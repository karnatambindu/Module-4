# Exp.No:4C EXCEPTION HANDLING
# AIM
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

# ALGORITHM
1. Begin the program.
2. Read a string input_str from the user using input().
3. Split the input string using commas (,) to create a list of grades. Use a try block to attempt converting each item in the grades list to an integer and store the result in l1.
4. If the conversion is successful, print the list l1 containing the integer values.
5. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: "The grades you entered were in an invalid format." along with the original grades list.
6. Terminate the program.

# PROGRAM
REG No: 212223060113 NAME: Karnatam Bindu
```
grades = input().split(",")

try:
	grades = [int(grade) for grade in grades]
  
except ValueError:
	print("The grades you entered were in an invalid format.")
print(grades)
```
# OUTPUT
<img width="1332" height="312" alt="image" src="https://github.com/user-attachments/assets/3f783ba2-cb79-4fc9-9a97-46db7abf99d2" />


# RESULT
Thus the Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers is successfully verified.
