# Exp.No:4B DICTIONARY - SIZE OF DICTIONARY
# AIM
To write a Python program to print the size of a dictionary using getsizeof() from the sys module.

# ALGORITHM
1. Begin the program. I
2. mport the sys module to use the getsizeof() function.
3. Define the dictionaries with key-value pairs (dic1, dic2, dic3).
4. Use sys.getsizeof() to calculate the memory size of each dictionary. Print the size of each dictionary in bytes.
5. Terminate the program.

# PROGRAM
REG No: 212223060113 NAME: Karnatam Bindu
```
import sys
dic1 = {"A": 1, "B": 2, "C": 3} 

dic2 = {"Geek1": "Raju", "Geek2": "Nikhil", "Geek3": "Deepanshu"}

dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}

size_dic1=sys. getsizeof(dic1)
size_dic2=sys. getsizeof(dic2)
size_dic3=sys. getsizeof(dic3)

print("Size of dic1: "+str(size_dic1) +"bytes")
print("Size of dic2: "+str(size_dic2) +"bytes")
print("Size of dic3: "+str(size_dic3) +"bytes")
```
# OUTPUT
<img width="934" height="242" alt="image" src="https://github.com/user-attachments/assets/4de0f7b6-0238-43ce-a128-c2f40da1d05d" />


# RESULT
Thus, the Python program to print the size of a dictionary using getsizeof() from the sys module is successfully done.
