## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
ANSWER:
Python is an object-oriented, high-level programming language. Object-oriented means this language is based around objects (such as data) rather than functions, and high-level means it's easy for humans to understand.

Q2. Why is Python called a dynamically typed language?
ANSWER:
Python don't have any problem even if we don't declare the type of variable. It states the kind of variable in the runtime of the program. Python also take cares of the memory management which is crucial in programming. So, Python is a dynamically typed language


Q3. List some pros and cons of Python programming language?
ANSWER: PROS - Python has a wide selection of libraries and frameworks.
CONS - Speed Limitations, Weak in Mobile Computing and Browsers.


Q4. In what all domains can we use Python?
ANSWER: 
Python is extensively used in developing Cross-Platform GUI Applications.

Q5. What are variable and how can we declare them?
ANSWER: 
Variables are the basic unit of storage in a programming language. These variables consist of a data type, the variable name, and the value to be assigned to the variable. Unless and until the variables are declared and initialized, they cannot be used in the program

Q6. How can we take an input from the user in Python?
ANSWER:
Using the input() function, we take input from a user, and using the print() function, we display output on the screen.


Q7. What is the default datatype of the value that has been taken as an input using input() function?
ANSWER:
A string


Q8. What is type casting?
ANSWER:
Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
ANSWER:
Using split() method : This function helps in getting multiple inputs from users.

Q10. What are keywords?
ANSWER:
Python keywords are special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes.

Q11. Can we use keywords as a variable? Support your answer with reason.
ANSWER:
We cannot use a keyword as a variable name, function name, or any other identifier. They are used to define the syntax and structure of the Python language. All the keywords except True , False and None are in lowercase and they must be written as they are.

Q12. What is indentation? What's the use of indentaion in Python?
ANSWER:
Indentation refers to the spaces at the beginning of a code line. Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important. Python uses indentation to indicate a block of code.


Q13. How can we throw some output in Python?
ANSWER:
As a Python developer you can choose to throw an exception if a condition occurs. To throw (or raise) an exception, use the raise keyword.

Q14. What are operators in Python?
ANSWER:
In Python, operators are special symbols that designate that some sort of computation should be performed. The values that an operator acts on are called operands.

Q15. What is difference between / and // operators?
ANSWER:
The first one is Float Division("/") and the second is Integer Division("//").

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
ANSWER:
multiply_str = "ineuron"*4
print("multiply_str =",multiply_str)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
ANSWER:
num = int (input (“Enter any number to test whether it is odd or even: “)

if (num % 2) == 0:

              print (“The number is even”)

else:

              print (“The provided number is odd”)

Output:

Enter any number to test whether it is odd or even:

Q18. What are boolean operator?
ANSWER:
Boolean Operators are simple words (AND, OR, NOT or AND NOT) used as conjunctions to combine or exclude keywords in a search, resulting in more focused and productive results.

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
ANSWER:
FALSE

Q20. What are conditional statements in Python?
ANSWER:
A conditional statement as the name suggests itself, is used to handle conditions in your program. These statements guide the program while making decisions based on the conditions encountered by the program.
if.
if..else.
Nested if.

Q21. What is use of 'if', 'elif' and 'else' keywords?
ANSWER:
if… elif…else are conditional statements that provide you with the decision making that is required when you want to execute code based on a particular condition.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
ANSWER:
AGE = 18
if age >= 18:
print("I can vote")
else:
print("i cant vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```

numbers = [12, 75, 150, 180, 145, 525, 50]
```
ANSWER:
Num = [ 12, 75, 150, 180, 145, 525, 50 ]
print(" addition of num ", num )



Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
ANSWER:


num1 = 10
num2 = 14
num3 = 12

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
num3 = float(input("Enter third number: "))

if (num1 >= num2) and (num1 >= num3):
   greatest = num1
elif (num2 >= num1) and (num2 >= num3):
    greatest = num2
else:
    greatest = num3

print("The  greatest number is",  greatest)




Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
ANSWER:

a = [12, 75, 150, 180, 145, 525, 50]
b = []
for i in a:
    if i > 150:
        if i > 500:
            break
        continue
    if i % 5 == 0:
        b.append(i)
        
print(b)