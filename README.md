# Python_assingment

Q1. Why do we call Python as a general purpose and high-level programming language?
# It provides rich data types and easier to read syntax than any other programming languages. 
# It is a platform independent scripted language with full access to operating system API's.
# Compared to other programming languages, it allows more run-time flexibility.
# For building large applications, Python can be compiled to byte-code.
# Python supports functional and structured programming as well as OOP.
# In Python, since there is no compilation step, editing, debugging and testing is fast.
# Easy-to-learn − Python has few keywords, simple structure, and a clearly defined syntax. This allows the student to pick up the language quickly.
# Easy-to-read − Python code is more clearly defined and visible to the eyes.
# Easy-to-maintain − Python's source code is fairly easy-to-maintain.
# A broad standard library − Python's bulk of the library is very portable and cross-platform compatible on UNIX, Windows, and Macintosh.
# Python is a powerful language that you can use to create games, write GUIs, and develop web applications.
# It is a high-level language. Reading and writing codes in Python is much like reading and writing regular English statements. Because they are not written in machine-readable language, Python programs need to be processed before machines can run them.
# Python is an interpreted language. This means that every time a program is run, its interpreter runs through the code and translates it into machine-readable byte code.


Q2. Why is Python called a dynamically typed language?
# Python is a dynamically typed language. It doesn’t know about the type of the variable until the code is run. So declaration is of no use. What it does is, It stores that value at some memory location and then binds that variable name to that memory container. And makes the contents of the container accessible through that variable name. So the data type does not matter. As it will get to know the type of the value at run-time.


Q3. List some pros and cons of Python programming language?
# Pros.
Python is easy to learn and read.
Python enhances productivity.
Python has a vast collection of libraries.
Python is free, open-source, and has a vibrant community.
Python is a portable programming language.
Python is an interpreted language.
# Cons.
Slow Speed·
Not Memory Efficient.
Weak in Mobile Computing.
Database Access·
Runtime Errors.


Q4. In what all domains can we use Python?
# Machine learning / Artificial intelligence
# Desktop GUI
# Data analytics and data visualization 
# Web development
# Game development
# Mobile app development
# Embedded systems



Q5. What are variable and how can we declare them?
# Following variables are use in python
Integer, Long Integer, Float, and String.
# To create a string, put the sequence of characters inside either single quotes, double quotes, or triple quotes and then assign it to a variable.
eg: (ab_123)



Q6. How can we take an input from the user in Python?
# We can use input () junction.
# input("Enter username:") print("Username is: " + username)


Q7. What is the default datatype of the value that has been taken as an input using input() function?
# The input() function by default returns the value as string data type.


Q8. What is type casting?
# The conversion of one data type into the other data type is known as type casting in python or type conversion in python.
# Python supports a wide variety of functions or methods like: int(), float(), str(), ord(), hex(), oct(), tuple(), set(), list(), dict(), etc. for the type casting in python.


Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
# YES ,You can take multiple inputs in one single line by using the raw_input function several times as shown below.
# multiple inputs in Python using input
x, y = input("Enter First Name: "), input("Enter Last Name: ") 
print("First Name is: ", x) 
print("Second Name is: ", y)

# Output:
Enter First Name: KUMAR
Enter Last Name: SHUBHAM
First Name is: KUMAR
Second Name is: SHUBHAM


Q10. What are keywords?
# Reserved words are present in every programming language. Be it Java or Python, each programming language has a set of reserved keywords. These words are also known as keywords. They convey a specific message.
eg:
# False               def                 if                  raise
# None                del                 import              return
# True                elif                in                  try
# and                 else                is                  while
# as                  except              lambda              with
# assert              finally             nonlocal            yield
# break               for                 not                 
# class               from                or                  
# continue            global              pass


Q11. Can we use keywords as a variable? Support your answer with reason.
# Keywords are the reserved words in Python. We cannot use a keyword as a variable name, function name or any other identifier. They are used to define the syntax and structure of the Python language. In Python, keywords are case sensitive. All the keywords in python are written in lower case except True and False.


Q12. What is indentation? What's the use of indentaion in Python?
# Indentation refers to the spaces at the beginning of a code line.
# Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important.
# Python uses indentation to indicate a block of code.
eg:
if 5 > 2:
  print("Five is greater than two!")
# Python will give you an error if you skip the indentation:
eg:
Syntax Error:
if 5 > 2:
print("Five is greater than two!")


Q13. How can we throw some output in Python?
# The basic way to do output is the print statement. To end the printed line with a newline, add a print statement without any objects. This will print to any object that implements write(), which includes file objects.


Q14. What are operators in Python?
# Python divides the operators in the following groups:
eg:
Arithmetic operators
Assignment operators
Comparison operators
Logical operators
Identity operators
Membership operators
Bitwise operators


Q15. What is difference between / and // operators?
# '/ '='Division '   	x / y
x = 12
y = 3
print(x / y)
4

# '//	'='Floor division'  	x // y
x = 15
y = 2
print(x // y)
7
# the floor division // rounds the result down to the nearest whole number


Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
# str = "iNeuron"
# print(str*4)


Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
#
num = int(input("Enter a number: "))
mod = num % 2
if mod > 0:
    print("This is an odd number.")
else:
    print("This is an even number.")



Q18. What are boolean operator?
# The logical operators and, or and not are boolean operators.


Q19. What will the output of the following?
```
1 or 0 >> True

0 and 0 >> False

True and False and True >> False

1 or 0 or 0 >> 1
```

Q20. What are conditional statements in Python?

# A conditional statement as the name suggests itself, is used to handle conditions in your program. These statements guide the program while making decisions based on the conditions encountered by the program.
Python has 3 key Conditional Statements:
if
else
elif


Q21. What is use of 'if', 'elif' and 'else' keywords?

# if… elif…else are conditional statements that provide you with the decision making that is required when you want to execute code based on a particular condition. The if… elif…else statement used in Python helps automate that decision making process.


Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
#
your_age = int(input("Enter your age: "))
if your_age >= 18:
    print("I can vote.")

else:
    print("I can't vote.")
    

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
# o/p
numbers = [12, 75, 150, 180, 145, 525, 50]
result = 0
for i in numbers:
    if not i % 2:
        result += i

print(result)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
#
num1 = input("Enter 1st number:")
num2 = input("Enter 2nd number:")
num3 = input("Enter 3rd number:")
result = int(max(num1, num2, num3))
print(result)



Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Q26. What is a string? How can we declare string in Python?

# strings in Python are arrays of bytes representing unicode characters. However, Python does not have a character data type, a single character is simply a string with a length of 1.To create a string, put the sequence of characters inside either single quotes, double quotes, or triple quotes and then assign it to a variable.

Q27. How can we access the string using its index?

#  Individual characters in a string can be accessed by specifying the string name followed by a number in square brackets ( [] ). String indexing in Python is zero-based: the first character in the string has index 0 , the next has index 1 , and so on.

Q28. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "iNeuron"
```
# o/p
str = "Big Data iNeuron"
print(str[8:])

Q29. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "norueNi"
```

Q30. Resverse the string given in the above question.
# o/p
str = "Big Data iNeuron"[::-1]
print(str)


Q31. How can you delete entire string at once?

# To clear or remove a string, you assign an empty string or use the del statement,


Q32. What is escape sequence?

Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```
#
string = str("'iNeuron's Big Data Course'")
print(string)


Q34. What is a list in Python?

Q35. How can you create a list in Python?

Q36. How can we access the elements in a list?

Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
``` 

Q38. Take a list as an input from the user and find the length of the list.

Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
```

Q40. What is a tuple? How is it different from list?

Q41. How can you create a tuple in Python?

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?

Q44. Take a tuple as an input and print the count of elements in it.

Q45. What are sets in Python?

Q46. How can you create a set?

Q47. Create a set and add "iNeuron" in your set.

Q48. Try to add multiple values using add() function.

Q49. How is update() different from add()?

Q50. What is clear() in sets?

Q51. What is frozen set?

Q52. How is frozen set different from set?

Q53. What is union() in sets? Explain via code.

Q54. What is intersection() in sets? Explain via code.

Q55. What is dictionary ibn Python?

Q56. How is dictionary different from all other data structures.

Q57. How can we declare a dictionary in Python?

Q58. What will the output of the following?
```
var = {}
print(type(var))
```

Q59. How can we add an element in a dictionary?

Q60. Create a dictionary and access all the values in that dictionary.

Q61. Create a nested dictionary and access all the element in the inner dictionary.

Q62. What is the use of get() function?

Q63. What is the use of items() function?

Q64. What is the use of pop() function?

Q65. What is the use of popitems() function?

Q66. What is the use of keys() function?

Q67. What is the use of values() function?

Q68. What are loops in Python?

Q69. How many type of loop are there in Python?

Q70. What is the difference between for and while loops?

Q71. What is the use of continue statement?

Q72. What is the use of break statement?

Q73. What is the use of pass statement?

Q74. What is the use of range() function?

Q75. How can you loop over a dictionary?


### Coding problems
Q76. Write a Python program to find the factorial of a given number.

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

Q79. Write a Python program to check if a number is prime or not.

Q80. Write a Python program to check Armstrong Number.

Q81. Write a Python program to find the n-th Fibonacci Number.

Q82. Write a Python program to interchange the first and last element in a list.

Q83. Write a Python program to swap two elements in a list.

Q84. Write a Python program to find N largest element from a list.

Q85. Write a Python program to find cumulative sum of a list.

Q86. Write a Python program to check if a string is palindrome or not.

Q87. Write a Python program to remove i'th element from a string.

Q88. Write a Python program to check if a substring is present in a given string.

Q89. Write a Python program to find words which are greater than given length k.

Q90. Write a Python program to extract unquire dictionary values.

Q91. Write a Python program to merge two dictionary.

Q92. Write a Python program to convert a list of tuples into dictionary.
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```

Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```

Q94. Write a Python program to get all combinations of 2 tuples.
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```

Q95. Write a Python program to sort a list of tuples by second item.
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
```

Q96. Write a python program to print below pattern.
```
* 
* * 
* * * 
* * * * 
* * * * * 
```
# O/P
print("*")
print("* *")
print("* * *")
print("* * * *")
print("* * * * *")

Q97. Write a python program to print below pattern.
```
    *
   **
  ***
 ****
*****
```
# O/P
print("    *")
print("   **")
print("  ***")
print(" ****")
print("*****")

Q98. Write a python program to print below pattern.
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```
# O/P
print("    *")
print("   * *")
print("  * * *")
print(" * * * *")
print("* * * * *")

Q99. Write a python program to print below pattern.
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```
# O/P
print("1")
print("1 2")
print("1 2 3")
print("1 2 3 4")
print("1 2 3 4 5")

Q100. Write a python program to print below pattern.
```
A 
B B 
C C C 
D D D D 
E E E E E 

# O/P
print("A")
print("B B")
print("C C C")
print("D D D D")
print("E E E E E")
