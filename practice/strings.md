**1. Simple Greeting Program: Write a Python program that asks the user for their name and age, then prints a personalized greeting message. Use both the + operator and f-strings.**

**Program:**

name = input("Enter you name: ") 

age = input("Enter your age: ") 

print("My name is "+ name + "My age is " + age) 

print(f"My name is {name}. My age is {age}") 

**Output:**

Enter you name: Harsha 

Enter your age: 26 

My name is HarshaMy age is 26 

My name is Harsha. My age is 26 


**2. String Manipulation Exercise: Write a Python program that:**

Takes a sentence as input from the user.

Prints the sentence in all uppercase and lowercase.

Replaces all spaces with underscores.

Removes leading and trailing whitespace

**Program**

s = input("Express yourself: ")

print(s)

print(s.upper())

print(s.lower())

print(s.strip())

print(s.replace(" " , "_"))

print(s.replace("Learning" , "Deploying"))

**Output**

Express yourself:  I am Learning Python 

 I am Learning Python 
 
 I AM LEARNING PYTHON 
 
 i am learning python 
 
I am Learning Python

_I_am_Learning_Python_

 I am Deploying Python 
