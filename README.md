# Python_assingment

Q1. Why do we call Python as a general purpose and high-level programming language? 
ANS:
>It provides rich data types and easier to read syntax than any other programming languages. 
>It is a platform independent scripted language with full access to operating system API's.
>Compared to other programming languages, it allows more run-time flexibility.
>For building large applications, Python can be compiled to byte-code.
>Python supports functional and structured programming as well as OOP.
>In Python, since there is no compilation step, editing, debugging and testing is fast.
>Easy-to-learn − Python has few keywords, simple structure, and a clearly defined syntax. This allows the student to pick up the language quickly.
>Easy-to-read − Python code is more clearly defined and visible to the eyes.
>Easy-to-maintain − Python's source code is fairly easy-to-maintain.
>A broad standard library − Python's bulk of the library is very portable and cross-platform compatible on UNIX, Windows, and Macintosh.
>Python is a powerful language that you can use to create games, write GUIs, and develop web applications.
>It is a high-level language. Reading and writing codes in Python is much like reading and writing regular English statements. Because they are not written in machine-readable language, Python programs need to be processed before machines can run them.
>Python is an interpreted language. This means that every time a program is run, its interpreter runs through the code and translates it into machine-readable byte code.


Q2. Why is Python called a dynamically typed language?
ANS: Python is a dynamically typed language. It doesn’t know about the type of the variable until the code is run. So declaration is of no use. What it does is, It stores that value at some memory location and then binds that variable name to that memory container. And makes the contents of the container accessible through that variable name. So the data type does not matter. As it will get to know the type of the value at run-time.


Q3. List some pros and cons of Python programming language?
ANS: Pros.
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
ANS: We can use input () junction.
input("Enter username:") print("Username is: " + username)


Q7. What is the default datatype of the value that has been taken as an input using input() function?
ANS:  The input() function by default returns the value as string data type.


Q8. What is type casting?
ANS: The conversion of one data type into the other data type is known as type casting in python or type conversion in python.
> Python supports a wide variety of functions or methods like: int(), float(), str(), ord(), hex(), oct(), tuple(), set(), list(), dict(), etc. for the type casting in python.


Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
ANS: YES ,You can take multiple inputs in one single line by using the raw_input function several times as shown below.
> multiple inputs in Python using input
x, y = input("Enter First Name: "), input("Enter Last Name: ") 
print("First Name is: ", x) 
print("Second Name is: ", y)

# Output:
Enter First Name: KUMAR
Enter Last Name: SHUBHAM
First Name is: KUMAR
Second Name is: SHUBHAM


Q10. What are keywords?
ANS: Reserved words are present in every programming language. Be it Java or Python, each programming language has a set of reserved keywords. These words are also known as keywords. They convey a specific message.
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
ANS: Indentation refers to the spaces at the beginning of a code line.
> Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important.
> Python uses indentation to indicate a block of code.
eg:
if 5 > 2:
  print("Five is greater than two!")
> Python will give you an error if you skip the indentation:
eg:
Syntax Error:
if 5 > 2:
print("Five is greater than two!")


Q13. How can we throw some output in Python?
ANS: 
The basic way to do output is the print statement. To end the printed line with a newline, add a print statement without any objects. This will print to any object that implements write(), which includes file objects.


Q14. What are operators in Python?
ANS: Python divides the operators in the following groups:
eg:
Arithmetic operators
Assignment operators
Comparison operators
Logical operators
Identity operators
Membership operators
Bitwise operators


Q15. What is difference between / and // operators?
ANS: '/ '='Division '   	x / y
x = 12
y = 3
print(x / y)
4

> '//	'='Floor division'  	x // y
x = 15
y = 2
print(x // y)
7
> the floor division // rounds the result down to the nearest whole number


Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
ANS: str = "iNeuron"
> print(str*4)


Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
ANS:
num = int(input("Enter a number: "))
mod = num % 2
if mod > 0:
    print("This is an odd number.")
else:
    print("This is an even number.")



Q18. What are boolean operator?
ANS: The logical operators and, or and not are boolean operators.


Q19. What will the output of the following?
```
1 or 0 >>  True

0 and 0 >>  False

True and False and True >>   False

1 or 0 or 0 >>   1
```

Q20. What are conditional statements in Python?

ANS: A conditional statement as the name suggests itself, is used to handle conditions in your program. These statements guide the program while making decisions based on the conditions encountered by the program.
Python has 3 key Conditional Statements:
if
else
elif


Q21. What is use of 'if', 'elif' and 'else' keywords?

ANS: if… elif…else are conditional statements that provide you with the decision making that is required when you want to execute code based on a particular condition. The if… elif…else statement used in Python helps automate that decision making process.


Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
ANS:
your_age = int(input("Enter your age: "))
if your_age >= 18:
    print("I can vote.")

else:
    print("I can't vote.")
    

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
ANS: o/p
numbers = [12, 75, 150, 180, 145, 525, 50]
result = 0
for i in numbers:
    if not i % 2:
        result += i
print(result)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
ANS:
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
Ans:
numbers = [12, 75, 150, 180, 145, 525, 50]

for number in numbers:
    if number > 500:
        # Stop the loop if the number is greater than 500
        break
    elif number > 150:
        # Skip the number if it is greater than 150
        continue
    elif number % 5 == 0:
        # Print the number if it is divisible by 5
        print(number)
        
        
Q26. What is a string? How can we declare string in Python?

ANS: strings in Python are arrays of bytes representing unicode characters. However, Python does not have a character data type, a single character is simply a string with a length of 1.To create a string, put the sequence of characters inside either single quotes, double quotes, or triple quotes and then assign it to a variable.

Q27. How can we access the string using its index?

ANS:  Individual characters in a string can be accessed by specifying the string name followed by a number in square brackets ( [] ). String indexing in Python is zero-based: the first character in the string has index 0 , the next has index 1 , and so on.

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
Ans:
string = "Big Data iNeuron"
print(string[:-8:-1])


Q30. Resverse the string given in the above question.
# o/p
str = "Big Data iNeuron"[::-1]
print(str)


Q31. How can you delete entire string at once?
ANS: 
To clear or remove a string, you assign an empty string or use the del statement.
eg....
string = "Big Data iNeuron"
del string
print(string)


Q32. What is escape sequence?
Ans:
An escape sequence is a sequence of characters that, when used inside a character or string, does not represent itself but is converted into another character or series of characters. So escape sequences are formed using two things: the first is a backslash (\\), and the second is the set of one or more characters following that backslash (\\).


Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```
ANS:
string = str("'iNeuron's Big Data Course'")
print(string)


Q34. What is a list in Python?
Ans:
In Python, a list is created by placing elements inside square brackets [] , separated by commas. A list can have any number of items and they may be of different types (integer, float, string, etc.). A list can also have another list as an item. This is called a nested list.


Q35. How can you create a list in Python?
Ans:
To create a list in Python, we use square brackets ( [] ). Here's what a list looks like: ListName = [ListItem, ListItem1, ListItem2, ListItem3, ...]
eg:
List1 = ["Welcome", "to", "Data",1,5,9]


Q36. How can we access the elements in a list?
Ans:
We can access the list by giving the Index.
Index starts from 0.


Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
Ans:
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
temp = lst[4]
print(temp[2])

Q38. Take a list as an input from the user and find the length of the list.
Ans:
# creating an empty list
lst1 = []
# number of elements as input
n = int(input("Enter number of elements : "))
  
# iterating till the range
for i in range(0, n):
    ele = int(input())
  
    lst1.append(ele) # adding the element
      
print(lst1)
#for number of length

print(len(lst1))



Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
Ans:
lst = ["Welcome", "to", "Data", "course"]
lst.insert(3,"Big")
print(lst)


Q40. What is a tuple? How is it different from list?
Ans:
A tuple is a collection of objects which ordered and immutable. Tuples are sequences, just like lists.
The differences between tuples and lists are, the tuples cannot be changed unlike lists and tuples use parentheses, whereas lists use square brackets.
Tuple is where use when data doesn't require any change in future.


Q41. How can you create a tuple in Python?
Ans:
A tuple in Python can be created by enclosing all the comma-separated elements inside the parenthesis ().
eg:
coordinates = (4,5)

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
ans:
coordinates = (4,5)
coordinates[1] = "shubham"
print(coordinates[1])

# o/p 
TypeError: 'tuple' object does not support item assignment.
we are not able to do it because 'tuple' object does not support item assignment.


Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
Ans:
# Define the two tuples
tuple1 = (1, 2, 3)
tuple2 = (4, 5, 6)

# Append the two tuples
tuple3 = tuple1 + tuple2

# Print the resulting tuple
print(tuple3)


Q44. Take a tuple as an input and print the count of elements in it.
Ans:
# Take the tuple as input
my_tuple = tuple(input("Enter a tuple: "))

# Print the count of the elements in the tuple
print("The tuple has", len(my_tuple), "elements.")


Q45. What are sets in Python?
Ans:
set() method is used to convert any of the iterable to sequence of iterable elements with distinct elements, commonly called Set. Parameters.
Sets are used to store multiple items in a single variable.


Q46. How can you create a set?
Ans:
A set is created by placing all the items (elements) inside curly braces {} , separated by comma, or by using the built-in set() function. It can have any number of items and they may be of different types (integer, float, tuple, string etc.).


Q47. Create a set and add "iNeuron" in your set.
Ans:
# Create an empty set
my_set = set()

# Add an element to the set
my_set.add("iNeuron")

# Print the set
print(my_set)


Q48. Try to add multiple values using add() function.
Ans:
# Create an empty set
my_set = set()

# Use the add() method to add a single value to the set
my_set.add("iNeuron","python","Data science")

# Print the set
print(my_set)



Q49. How is update() different from add()?
Ans:
We use add() method to add single value to a set. We use update() method to add sequence values to a set. Here Sequences are any iterables including list , tuple , string , dict etc

Q50. What is clear() in sets?
Ans:
The clear() method removes all elements in a set.

Q51. What is frozen set?
Ans:
Python frozenset() Method creates an immutable Set object from an iterable. It is a built-in Python function. As it is a set object therefore we cannot have duplicate values in the frozenset.


Q52. How is frozen set different from set?
Ans:
Frozenset is similar to set in Python, except that frozensets are immutable, which implies that once generated, elements from the frozenset cannot be added or removed. This function accepts any iterable object as input and transforms it into an immutable object.


Q53. What is union() in sets? Explain via code.
Ans:
In Python, the union() method is used to compute the union of two sets. The union of two sets is a new set that contains all of the elements from both sets, without any duplicates. This means that the resulting set will only contain unique elements that are present in either or both of the input sets.
#code:
# Define two sets
set1 = {"iNeuron", "Python", "Data Science"}
set2 = {"Machine Learning", "Deep Learning", "Python"}

# Compute the union of the two sets
union_set = set1.union(set2)

# Print the union set
print(union_set)


Q54. What is intersection() in sets? Explain via code.
Ans:
In Python, the intersection() method is used to compute the intersection of two sets. The intersection of two sets is a new set that contains only the elements that are present in both of the input sets. This means that the resulting set will only contain the elements that are common to both of the input sets.
#code
# Define two sets
set1 = {"iNeuron", "Python", "Data Science"}
set2 = {"Machine Learning", "Deep Learning", "Python"}

# Compute the intersection of the two sets
intersection_set = set1.intersection(set2)

# Print the intersection set
print(intersection_set)


Q55. What is dictionary in Python?
Ans:
In Python, a dictionary is a data structure that stores a collection of key-value pairs. Each key in a dictionary maps to a corresponding value, which can be any type of data (such as a string, a number, or a list). Dictionaries are often used to store data that needs to be accessed by a unique identifier (the key), such as a user ID or a product SKU.


Q56. How is dictionary different from all other data structures.
Ans:
In Python, dictionaries are different from other data structures in several ways. The
main difference is that dictionaries store a collection of key-value pairs, whereas
other data structures (such as lists, sets, and tuples) store a collection of values.
This means that each element in a dictionary has a corresponding key, which can be used
to access the element, whereas elements in other data structures do not have keys and
must be accessed using their position in the collection.


Another difference between dictionaries and other data structures is that dictionaries
are mutable, whereas other data structures (such as tuples) are immutable. This means
that you can add, remove, and modify elements in a dictionary, whereas you cannot
modify the elements in an immutable data structure.

Q57. How can we declare a dictionary in Python?
ans:
In Python, you can declare a dictionary using the dict() constructor or by using curly braces {}.
# Declare an empty dictionary using the dict() constructor
my_dict = dict()

# Declare an empty dictionary using curly braces
my_dict = {}

# Declare a dictionary with some initial key-value pairs
my_dict = {"name": "Kumar Shubham", "age": 25, "email": "kshubham775@gmail.com"}


Q58. What will the output of the following?
```
var = {}
print(type(var))
```
# o/p
<class 'dict'>


Q59. How can we add an element in a dictionary?
Ans:
 By the help of append() , or insert() method we can use to add an item to a
 dictionary 
 in Python.
 
 
Q60. Create a dictionary and access all the values in that dictionary.
Ans:
# Create a dictionary
my_dict = {"name": "Kumar Shubham", "age": 25, "email": "kshubham775@gmail.com"}

# Access the values in the dictionary using the keys
print(my_dict["name"])  # Output: "Kumar Shubham"
print(my_dict["age"])  # Output: 25
print(my_dict["email"])  # Output: "kshubham775@gmail.com"


Q61. Create a nested dictionary and access all the element in the inner dictionary.
Ans:
In Python, a dictionary can contain another dictionary as one of its values. This is called a nested dictionary, and it allows you to store and access data in a hierarchical structure.

# Create a nested dictionary
my_dict = {"name": "Kumar Shubham", "age": 25, "email": "kshubham775@gmail.com", "contact": {"phone": "1234567890", "address": "123 market St, Anytown INDIA"}}

# Access an element in the inner dictionary using the keys
print(my_dict["contact"]["phone"])  # Output: "1234567890"
print(my_dict["contact"]["address"])  # Output: "123 market St, Anytown INDIA"


Q62. What is the use of get() function?
Ans:
In Python, the get() method is used to access the value associated with a key in a dictionary. This method takes two arguments: the key and a default value to return if the key is not found in the dictionary. If the key is present in the dictionary, the get() method will return the associated value, otherwise it will return the default value that you specified.

# Create a dictionary
my_dict = {"name": "Kumar Shubham", "age": 32, "email": "kshubham775@gmail.com"}

# Use the get() method to access a value in the dictionary
print(my_dict.get("name", "Unknown"))  # Output: "Kumar Shubham"
print(my_dict.get("phone", "Unknown"))  # Output: "Unknown"


Q63. What is the use of items() function?
Ans:
The items() method returns a view object. The view object contains the key-value pairs of the dictionary, as tuples in a list.

The view object will reflect any changes done to the dictionary.


Q64. What is the use of pop() function?
Ans:
The pop() function will remove the last element of the list.

Q65. What is the use of popitems() function?
Ans:
Python dictionary popitem() method removes the last inserted key-value pair from the dictionary and returns it as a tuple.


Q66. What is the use of keys() function?
Ans:
The keys() method returns a view object. The view object contains the keys of the
dictionary, as a list.
The view object will reflect any changes done to the dictionary.

Q67. What is the use of values() function?
Ans:
values() is an inbuilt method in Python programming language that returns a view object. The view object contains the values of the dictionary.

Q68. What are loops in Python?
Ans:
Looping means repeating something over and over until a particular condition is
satisfied. A for loop in Python is a control flow statement that is used to repeatedly
execute a group of statements as long as the condition is satisfied. Such a type of 
statement is also known as an iterative statement.


Q69. How many type of loop are there in Python?
Ans:
There are two types of loops in Python, for and while.


Q70. What is the difference between for and while loops?
Ans:
For loop is used when the number of iterations is already known.
While loop is used when the number of iterations is Unknown.In the while loop, it can be repeated at every iteration. To iterate, the range or xrange function is used.


Q71. What is the use of continue statement?
Ans:
The continue keyword is used to end the current iteration in a for loop (or a while loop), and continues to the next iteration.


Q72. What is the use of break statement?
Ans:
'Break' in Python is a loop control statement. It is used to control the sequence of the loop. Suppose you want to terminate a loop and skip to the next code after the loop; break will help you do that.


Q73. What is the use of pass statement?
Ans:
In Python programming, the pass statement is a null statement which can be used as a placeholder for future code.
Suppose we have a loop or a function that is not implemented yet, but we want to implement it in the future. In such cases, we can use the pass statement.


Q74. What is the use of range() function?
Ans:
The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.


Q75. How can you loop over a dictionary?
Ans:
In Python, you can loop over a dictionary using a for loop and the items() method. The items() method returns a list of tuples, where each tuple contains a key-value pair from the dictionary.


### Coding problems
Q76. Write a Python program to find the factorial of a given number.
Ans:
def factorial(n):
  if n == 0:
    return 1
  else:
    return n * factorial(n-1)

num = int(input("Enter a number: "))
print("The factorial of", num, "is", factorial(num))


Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100
Ans:
def simple_interest(p, r, t):
  si = (p * r * t) / 100
  return si

principal = float(input("Enter the principal amount: "))
rate = float(input("Enter the rate of interest: "))
time = float(input("Enter the time in years: "))

si = simple_interest(principal, rate, time)

print("The simple interest is", si)



Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.
Ans:
def compound_interest(p, r, t):
  a = p * (1 + r / 100) ** t
  return a

principal = float(input("Enter the principal amount: "))
rate = float(input("Enter the rate of interest: "))
time = float(input("Enter the time in years: "))

a = compound_interest(principal, rate, time)

print("The compound interest is", a)



Q79. Write a Python program to check if a number is prime or not.
Ans:
def is_prime(n):
  if n <= 1:
    return False
  for i in range(2, n):
    if n % i == 0:
      return False
  return True

num = int(input("Enter a number: "))

if is_prime(num):
  print(num, "is a prime number")
else:
  print(num, "is not a prime number")



Q80. Write a Python program to check Armstrong Number.
Ans:
def is_armstrong_number(n):
  num_digits = len(str(n))
  sum = 0
  for digit in str(n):
    sum += int(digit) ** num_digits
  return sum == n

num = int(input("Enter a number: "))

if is_armstrong_number(num):
  print(num, "is an Armstrong number")
else:
  print(num, "is not an Armstrong number")



Q81. Write a Python program to find the n-th Fibonacci Number.
Ans:
def fibonacci(n):
  if n == 0:
    return 0
  elif n == 1:
    return 1
  else:
    return fibonacci(n-1) + fibonacci(n-2)

num = int(input("Enter a number: "))

print("The", num, "th Fibonacci number is", fibonacci(num))



Q82. Write a Python program to interchange the first and last element in a list.
Ans:
def interchange(lst):
  first = lst[0]
  last = lst[-1]
  lst[0] = last
  lst[-1] = first
  return lst

lst = [1, 2, 3, 4, 5]

print("Original list:", lst)
print("Modified list:", interchange(lst))


Q83. Write a Python program to swap two elements in a list.
Ans:
def swap(lst, i, j):
  temp = lst[i]
  lst[i] = lst[j]
  lst[j] = temp
  return lst

lst = [1, 2, 3, 4, 5]
i = 0
j = 4

print("Original list:", lst)
print("Modified list:", swap(lst, i, j))



Q84. Write a Python program to find N largest element from a list.
Ans:
def largest_n(lst, n):
  sorted_lst = sorted(lst, reverse=True)
  return sorted_lst[:n]

lst = [10, 25, 30, 45, 50, 60]
n = 3

print("Original list:", lst)
print("Largest", n, "elements:", largest_n(lst, n))



Q85. Write a Python program to find cumulative sum of a list.
Ans:
def cumulative_sum(lst):
  cum_sum = []
  sum = 0
  for num in lst:
    sum += num
    cum_sum.append(sum)
  return cum_sum

lst = [10, 20, 30, 40]

print("Original list:", lst)
print("Cumulative sum:", cumulative_sum(lst))


Q86. Write a Python program to check if a string is palindrome or not.
Ans:
def is_palindrome(s):
  return s == s[::-1]

s = "madam"

if is_palindrome(s):
  print(s, "is a palindrome")
else:
  print(s, "is not a palindrome")


Q87. Write a Python program to remove i'th element from a string.
Ans:
def remove_ith_element(s, i):
  return s[:i] + s[i+1:]

s = "Hello Bigg Data Engineer!"
i = 9

print("Original string:", s)
print("Modified string:", remove_ith_element(s, i))


Q88. Write a Python program to check if a substring is present in a given string.
Ans:
def is_substring(s, sub):
  return sub in s

s = "Hello World!"
sub = "World"

if is_substring(s, sub):
  print(sub, "is a substring of", s)
else:
  print(sub, "is not a substring of", s)


Q89. Write a Python program to find words which are greater than given length k.
Ans:
def find_words(s, k):
  words = s.split()
  return [word for word in words if len(word) > k]

s = "Hello World! This is a sample sentence."
k = 5

print("Words in '" + s + "' that are greater than length " + str(k) + ":", find_words(s, k))


Q90. Write a Python program to extract unquire dictionary values.
Ans:
def extract_unique_values(d):
  values = d.values()
  return list(set(values))

d = {
  "a": 1,
  "b": 2,
  "c": 3,
  "d": 1
}

print("Original dictionary:", d)
print("Unique values:", extract_unique_values(d))


Q91. Write a Python program to merge two dictionary.
Ans:
def merge_dictionaries(d1, d2):
  return {**d1, **d2}

d1 = {
  "a": 1,
  "b": 2,
  "c": 3
}

d2 = {
  "d": 4,
  "e": 5,
  "f": 6
}

print("Original dictionaries:", d1, d2)
print("Merged dictionary:", merge_dictionaries(d1, d2))


Q92. Write a Python program to convert a list of tuples into dictionary.
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```
Ans:
def tuples_to_dict(lst):
  return [{t[0]: t[1]} for t in lst]

lst = [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]

print("Original list:", lst)
print("Converted dictionaries:", tuples_to_dict(lst))


Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```
Ans:
def create_tuples(lst):
  return [(num, num**3) for num in lst]

lst = [9, 5, 6]

print("Original list:", lst)
print("List of tuples:", create_tuples(lst))


Q94. Write a Python program to get all combinations of 2 tuples.
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```
Ans:
# Import the itertools module
import itertools

# Define the two tuples
test_tuple1 = (7, 2)
test_tuple2 = (7, 8)

# Get all combinations of the two tuples
combinations = itertools.product(test_tuple1, test_tuple2)

# Print the combinations
for combination in combinations:
    print(combination)


Q95. Write a Python program to sort a list of tuples by second item.
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
Ans:
def sort_by_second_item(lst):
  return sorted(lst, key=lambda x: x[1])

lst = [('for', 24), ('Geeks', 8), ('Geeks', 30)]

print("Original list:", lst)
print("Sorted list:", sort_by_second_item(lst))


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
