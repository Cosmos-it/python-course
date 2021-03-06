## Python Programming With Data Science
From beginner to advance

First and foremost I am dedicating this course material to my sister Kaku Cosmos whom I am teaching how to code.

This tutorial is designed for people that want to learn how to write python code quickly for fun and to building a project they have been dying to build. You will need to be a daily learner or a seasonal learner, otherwise you will "waste" your time. This tutorial will have a 30 second videos (Comming out soon) explaining concepts visually and with longer videos showing you the code in question.

#### ⚠️ Python was designed for simplicity. It might look easy but you can so much with. It also allows developers to solve problems faster cleanly.

The best way for you to learn this material will depend on how curious you are and how much time you spend experimenting with concepts provided here and others NOT included here --take a look at the extra resources in the bottom later after you finish the entire reading. 😊

Writing software is an art of expressing your logical or design thoughts in code. Software today is being used for everything from art, airplanes, cars, computers, healthcare, and search engines etc.. You can choose to become an app developer (Web or Mobile), AI/ML, AR/VR, Data Scientist, Softaware Engineer Researcher etc.

My hope for you is that by the end of this tutorial you will be equipped with knowledge you can use to build things for fun or getting that software engineering job or build your own company. 

#### What to expect
1. Learn the of basics python
2. Learn advance way of processing files
3. Learn how to read and understand code 
4. Learn how to best search for something you are not sure of
5. Learn how to write small programs
6. Learn to build data scrapping tool
7. Learn to build data vizualization 
8. Learn to build a simple web application
9. Learn RESTful APIs
10. Learn rGPC a faster and secure way of RESTful version
11. Blockchain bonus
12. Links to resources


### Lesson 1.0 
## Setting up your computers        
1. [Click this link to setup your mac](https://programwithus.com/learn-to-code/install-python3-mac/)
### Install xcode
* Go here to downloan xcode: Go to App Store search xcode then download it. Follow all the instructions. 

### Install Python
* [To install python, go to this website and click download](https://www.python.org/downloads/)

### Path Setup
* Next, we need to setup the path through terminal. 
* Type terminal in your mac spotlight and open terminal app
* Once you have that open, then you will need to paste this: ```export PATH="$PATH:/usr/local/bin/python"```


### Basic terminal commands: 
Open your terminal and do the following:

Create a directory for your project
```bash
mkdir project 
```
Go into the project directory you just created
```bash 
cd project
```
Open vscode with code . or just look for it in applications

## Hope all went swiftly. 

2. [Click this link to setup your Linux](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-ubuntu-16-04)
3. [Click this link to setup your Windows](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

#### You will some IDE to use for writing your code. 
1. [Click this link to down VSCODE](https://code.visualstudio.com/Download)

### Ipython
If you would like something a little nicer, you can install ipython. No recommded but it is good.
1. [Ipython Installation from codeacademy](https://www.codecademy.com/articles/how-to-use-ipython)

### Lesson 1.1

### Print
Printing things on screen in  python: 
Try this:

Open your terminal and type ipython or type python and press enter to get a shell command and then type the follow code on it.

```py
print('I am a new progrommer')
print('Learninng the dangerous Python Language')
print('Next time you see me,')
print('Say hi')
```

This is what ipython would look like.

```bash
In [1]: print('I am a new progrommer') 
   ...: print('Learninng the dangerous Python Language') 
   ...: print('Next time you see me,') 
   ...: print('Say hi')                                                                                                              
I am a new progrommer
Learninng the dangerous Python Language
Next time you see me,
Say hi

In [2]: 
```


The print() function tells the computer to print something to the screen

### Study Drills
Try printing something on the computer screen
#### Comments

Multi line comments
Try this:
```py 
""" 
    This is a multi-line comments with the three double quotes in the beginning and the end.
"""
```

Sinle line comments
Try this:

```py
# This is how you do a single line with the pound sign on the left
```

### Lession 1.2
#### Symbols using in python
* plus: +
* Multipy: * 
* Minus: - 
* Equal: =
* Greater-than-equal: =>
* less-than-equal: <=
* less-than: <
* greate-than: >
* Percent or Modulo:  %
* Slash/divide: /


### Lesson 1.3
#### Variables
What is a variable?
Variables are the left hand place holder for data representation to allow programmers "lazy" organize things in a readable way. Because as programmers, you going to forget things you wrote last night.

This is what variables looks like

Try this: 
```py
number = 100 
name = "Awesomeness"
```

Ipython
```bash
In [2]: number = 100                                                                                                                 
In [3]: name = "Awesome"
```

### Lesson 1.4
#### Calculation using the math symbols
Try this:

```py
# On the right is a variable
number = 1000 # Use variable whenever you can
print(number * number) # 1000000
print(number == number) # True
print(number - 100) # 
print(number + number) # 
print(number / 10) # 100
print(number > 3) # Returns true if number is greater than 3
print(number < 3) # Return False
print(number % 10) 
""" 
    Returns the reminder of the number 0 or 1: 0 means the number divides evenly but not 1
"""

# Try some of them that I didn't include here
```

Ipython
```bash
In [1]: # On the right is a variable 
   ...: number = 1000 # Use variable whenever you can 
   ...: print(number * number) # 1000000 
   ...: print(number == number) # True 
   ...: print(number - 100) #  
   ...: print(number + number) #  
   ...: print(number / 10) # 100 
   ...: print(number > 3) # Returns true if number is greater than 3 
   ...: print(number < 3) # Return False 
   ...: print(number % 10)  
   ...: """  
   ...:     Returns the reminder of the number 0 or 1: 0 means the number divides evenly but not 1 
   ...: """ 
   ...:  
   ...: # Try some of them that I didn't include here                                                                                
1000000
True
900
2000
100.0
True
False
0
Out[1]: ' \n    Returns the reminder of the number 0 or 1: 0 means the number divides evenly but not 1\n'

In [2]: 
```

#### Study drills
* Comment your code all the time to form a habbit.
* Find numbers to calculate
* Create a file and name whatever (example.py) and write your code on it.
* Research floating point

#### Common questions
How does % sign work?

The % is not the percentage sign you use as in 100% etc. Instead the % is used to get the reminder of a number. 
Lets say in math, that a variable x divided by a variable k gives you j with a reminder of either 0 or numbers greater than 1. 

That is x % k = j 
Lets try this out. 

Try this:

```py
k = 100
x = 1000
reminderOne = x % k
reminderTwo = x % 16
print(reminderOne) # 0
print(reminderTwo) # 8
```
Ipython
```bash
In [2]: k = 100 
   ...: x = 1000 
   ...: reminderOne = x % k 
   ...: reminderTwo = x % 16 
   ...: print(reminderOne) # 0 
   ...: print(reminderTwo) # 8                                                                                                       
0
8
```

Order of operations in math:
In the US we use PEMDAS while the rest of the work uses BODMAS math conventions. Remember this is just to help understand the order of operations. 

What does / sign mean? It is not a round down. The divide sign in python or any programming language basically means divide a number and take the whole number and nothing after the decimal point. Lets say 10.8, the computer will just return 10 and omit the '.8'. There are many reasons for that we don't care about that now. We will explore data types later to explain what type of things python uses to represent data in memory.



### Study Drills
1. Try to use variable and assign values to the right of it. 
2. Print do something with the variables through out your program

What are python data types?
Data types in computer programming it is used to represent data in memory. This is crucial for python to understand how to work with your program in write. 

Example of data types in python

Try this:

1. String: 
```py 
"I am a string"
```
2. int: 
```py 
number = 100
```
3. Float: 
```py
floatNumber = 100.0
```
4. Boolean: 
```py
true_value = True
false_value = False
```

### Escape characters
Try using this characters in your print statements as an exercise

character | Meaning 
----- | ---
\\\\ | single backslash
\f  | fromfeed
\b | backspace
\r | carriage return: used for debugging code
\t | horizontal tab
\v |vertical tab
\\" | double quote
\\' | single quote 


### Regular questions
What is the difference between the '=' and ' == '?
The single equals '=' is for assigning values to variables like seen earlier in the lessons. 

Try this:

```py 
my_name = 'Awesomeness' 
print(my_name) # my_name has the value in the right. 
```
```bash
In [3]: my_name = 'Awesomeness'  
   ...: print(my_name) # my_name has the value in the right.                                                          
Awesomeness
```
The double equals '==' is used to varify if something is the same. 

Try this:
```py 
print(10 == 10) # True
```
Ipython
```bash
In [4]: print(10 == 10)

True
```

How can I write something like I'll or new line? Python has something called escape characters that will allow you to escape some character and achieve what you want. 

Try this:

```py
print("I\'ll come home after I complete \nmy project at 7:00pm ") # \n = means go to next line: Try it yourself.
```

Ipython
```bash
In [5]: print("I\'ll come home after I complete \nmy project at 7:00pm ") 
   ...: f. 
   ...:                                                                                                               
I'll come home after I complete 
my project at 7:00pm 

In [6]:
```


### Summary
In lesson 1 we covered what you need to know to build simple project without bogging your mind with too much details.

We have covered system setup, comments, printing on screen, variables, and math signs. 

If you want to learn more about each topics, you would need to just practice writing a program. Aftwerall you need to write code. 

### Lesson 2.0
#### Input
In this lesson you will learn how to take user input and do something with the data. 

In the example below, we are going to use input() function to get user input and do something with it.

Try this:

```py 
# The input function takes in a variable. Look into the input function later if you ar curious about it. Otherwise this will do.
age = input("How old are you?")
height = input("How tall are you?")
weight = input("What is your weight?")
print("So you're: %s and this tall: %s and this weight: %s "%(age, height, weight))             
``` 

Run the program using Ipython
```bash
In [17]: age = input("How old are you?") 
    ...: height = input("How tall are you?") 
    ...: weight = input("What is your weight?") 
    ...: print("So you're: %s and this tall: %s and this weight: %s "%(age, height, weight))                          
How old are you?31
How tall are you?511
What is your weight?190
So you're: 31 and this tall: 511 and this weight: 190 

In [18]: 
```

### Study Drills
Fun time:
* Now go ahead and look for ways you can improve the code above. Like how can you use the input function to do other things. Such as if you want the value to be 
* Use that make a calculator of some sort. 
* Try to use numbers. Remember that all values that you get from input is a string. You will need to convert the values. For instance, you can do type casting --this means taking a string and making it an int --we discussed what strings and ints are.

Try this:
```py
numberA = input() # The value of the variable is a string
number = int(input()) # The value of the variable is not a string but int which we need
print(number)
```

### Lesson 2.1

#### Control statements (if elif else )

Control statement: This is how you can create logics to do simple or complex desicions

Try this:

```PY
"""
    Using if statements for logics
    if something happens 
    then something else should 
    else nothing should happen
"""
if number > 2 or number < 10:
    print(number)
elif number < 2:
    print("number is less than 2")
else:
    print("number is greater")
```
#### List
List is a data structure that used to store temporary data. 
Example:

Try this:
```py
# Creating a List 
list = [] 
print("Print a blank list ") 
print(list) 
```
Try this:
```py
# Add values to the list
data = ['Mary', 'had', 'a', 'little', 'lamb'] 
print("See the list)
print(data)
```

You can also tuple to the list
Try this:

```py
data = ['Mary', 'had', 'a', 'little', 'lamb'] 
data.apped(data.append((5, 6))
print(data)
```

You the insert method to add a value at specific location in the list
Try this: 

```py
data = ['Mary', 'had', 'a', 'little', 'lamb'] 
data.insert(1, 89) 
data.insert(0, 'Getting better') 
print(data)
```

Access single element from the list using index
To access an element you will need to use the 

Try this:

```py
data = ['Mary', 'had', 'a', 'little', 'lamb'] 
print("The first element using index 0")
print(data[0])
print(data[3])
```

Adding values to list.
When adding a value to a list, you can use the build python append method for lists. 
Append adds the value back of the list

Try this:
```py
data = ['Mary', 'had', 'a', 'little', 'lamb'] 
data.append("and sheep")
print(data)
```

You can use list with numbers
Try this:

```py
numbers = [2, 23,12,24,232]
print(numbers)
```

You can remove items from list this way

Try this: 

```
numbers = [2, 23,12,24,232]
numbers.remove(5) 
print()
```

You can mix your elements
 
Try this:
```py
mixed_data = ["Hey", True, 12, 23.0, 'sss']
print(mixed_data)
```

#### Loops
Try this:

```PY
# Measure some strings:
words = ['Dog', 'Cat', 'Windows']
for w in words:
    print(w, len(w))

for w in words[:]:  # Loop over a slice copy of the entire list.
    if len(w) > 6:
        words.insert(0, w)) # Figure out what this function just did. To know this. you will need to print out words again. print(words)

for i in range(5): # The range function allows you to print values from 0 - 4
    print(i)

data = ['Mary', 'had', 'a', 'little', 'lamb'] 
for i in range(len(data)):
    print(i, data[i]) # What do you think this print before you print it out.

# Try this:
list(range(5))

# pass statement
while True:
    pass # Pass does nothing in a program it allows the python program not cause error when you are thinking of how to implement it. 

```


### Study drills:
* Create your own practice file and write something you would like to print out Or calculate. 
* Type things out. If you get stuck alwasy search online or look at the example here.


### Lesson 2.3
#### Functions
In this part of the lesson we are goong to talk about Function 
Function or functions are used to do specific things

Functions arguments: Functions can also take in arguments that will be used to do whatever in it. Look below:

Default arguments: That is when the argument has assigned value such as below. The default values is just a placeholder incase you didn't give the function the value it needs for he arguments.

```py
# This is Function that takes in two numbers and adds it together
def add(a,b): # takes to arguments a and b
    # Prints out the result
    print(a+b) 

def add(a=0,b=0): # takes to arguments with default values.
    # Prints out the result
    print(a+b) 

# Another way to do the same thing
def add(a,b): 
    c = a + b # variable c holds your answer 
    print(c) # print value in c


# Another way to do the same thing
def add(a,b): 
    return a + b # This returns value but it does not print. :hint put the method in print
    

def subtract(a,b):
    #  Todo: Subtract two numbers and add it to 
    pass # Replace the pass with your code.


def multiply(a,b):
    #  Todo: Multiply two numbers and add it to 
    pass # Replace the pass with your code.

def divide(a,b):
    #  Todo: Divide two numbers and add it to 
    pass # Replace the pass with your code.


# Call and print out the numbers
add(90, 10)

#  Todo
subtract(4,9)
# Do the same for the remaining Function

```

### For practice look into:
1. Fibonacci formula and see if you can write the code out. If not search how it is implemented in python.


### Lesson 2.3
#### Collections and more on list
1. Uses of list
2. Tuple
4. Dictionay

Using lists: 
The list data type has some more methods. Here are all of the methods of list objects:
Make sure you look at python docs to learn more lists and what you can do with them.

Stacks
This allows you to put items in the back and remove it from the back as well. Last In Last Out.

A stack is like a stack of plates. After washing your plates you stack them on to each other. When dinner is ready to remove each plate from the top. 

That is Last in Last out.

Try this: 

Create a new stack list then append a new value to it
```py
stack = [3, 4, 5]
stack.append(6)
stack.append(7)

print(stack) # Print out the stack
print(stack.pop()) # Remove the list you just added.
```

###  Using list as dequeue
Dequeue is used for priority stuff. 
For instance you are in line waiting for your coffee. The First person in line gets served First. First in and First out.

Try this:
```py
# imports a package that has all the things you need to do necessary things with deque package
from collections import deque  
queue = deque(["Eric", "John", "Michael"]) 
queue.append("Terry")           # Terry arrives
queue.append("Graham")          # Graham arrives
queue.popleft() 
```

Try this: 

Add items to an empty list

```py
squares = [] # Create an empty list
for x in range(10): # Loop through 1 9 
    squares.append(x**2) # Square the value
print(squares) # [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]

```

Tuples
A tuple consists of a number of values separated by commas, for instance:

```py
t = 12345, 54321, 'hello!'
print(t)
print(t[0])

# Tuples may be nested:
u = t, (1, 2, 3, 4, 5)
print(u)


# Tuples are immutable: This means that you cannot change any values alread in there
t[0] = 88888

Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'tuple' object does not support item assignment

# but they can contain mutable objects:
v = ([1, 2, 3], [3, 2, 1])
print(v)

```


Sets
A set is an unordered collection with no duplicate elements. Basic uses include membership testing and eliminating duplicate entries. Set objects also support mathematical operations like union, intersection, difference, and symmetric difference.

Try this:
```py
basket = {'apple', 'orange', 'apple', 'pear', 'orange', 'banana'}
print(basket)                            # show that duplicates have been removed
print('orange' in basket )               # fast membership testing
print('crabgrass' in basket)

# Demonstrate set operations on unique letters from two words

a = set('abracadabra')
b = set('alacazam')
print(a)                                # unique letters in a
print(a - b )                           # letters in a but not in b
print(a | b   )                         # letters in a or b or both
print(a & b)                            # letters in both a and b
print(a ^ b )                           # letters in a or b but not both
```
Dictionaries

Now that you have learned some list and sets, it is time to learn something very powerful.

Dictionaries are sometimes found in other languages as “associative memories” or “associative arrays”.
Unlike sequences, which are indexed by a range of numbers, dictionaries are indexed by keys, which can be any immutable type; strings and numbers can always be keys

For more information about dictionaries go to the python docs. However you will learn how to use all of this in real projects.

Try this:

```py

# new dictionary
tel = {'jack': 4098, 'sape': 4139}

# Add new value to the dictionary
tel['guido'] = 4127 
print(tel)

# Print the value associated with the key jack
print(tel['jack'])

# Delete key sape that holds a value
del tel['sape']

# Add a new value
tel['irv'] = 4127
print(tel)
```


Convert dictionary keys into a list

Try this:

```py
list(tel) 

# After converting the dictionary to a list, 
# Now sort it.
# user the sort function used to sort stuff
print(sorted(tel))

# Check if guido exits in tel list
print('guido' in tel) 

# Check if jack exits in tel list
print('jack' not in tel)
```

For instance you can use dictionary to 

### Lesson 3.0 

classes and objects

1. Class: tell python to make something new
2. object: Most basic of thing and any instance of something
3. instance: the thing you get when you told python to create from class
4. def: how to define a function 
5. self: inside a function and also a class variable for the instance/object being accessed
6. inheritance: basically a concept that a class can inherit behaviors from a parent class just like how how some children inherit their parents traits
7. attributes: a property forclass
8. Composition: The concept that classes can be part of another class. Just like how a chair has legs
9. hasa: something is composed of other things  "Tuna has a mouth"
10. is-a: something inherits from another "Tuna is a fish

# Examples ...

Before we dive in too deep, python is an Object Oriented programming. 
Almost everything in python is object with properties and methods

Class: Is a blue print for creating objects.

To create a class you need to have the class keyword.
When creating your class, it must have the build int ``` __init__ ```function which is always executed when the class is being initialized. 
The ``` __init__ ``` function is used to assign values to object properties, or other operations when needed during creation of objects. 

Try this:

```py
# Class 
class Person:
    def __init__(self, name, age): #
        self.name = name
        self.age = age


James = Person("James", 34)
Jamila = Person("Jamila", 28)

print("First name: ", James.name, "Age: ", James.age)

```
You might ask what is the ```self``` parameter: It is a reference to the current instance of the class, and is used to access variables that belongs to the class.
the self word can be anything you want it to be. But it is always good to use self.

A class has methods which is just a function.

Try this:

```py
# Class 
class Person:
    def __init__(self, name, age): #
        self.name = name
        self.age = age
    
    def full_info(self):
        return self.name + " "  + str(self.age)


James = Person("James", 34)
Jamila = Person("Jamila", 28)

print("First name: ", James.name, "Age: ", James.age)
print(James.full_info())
print(Jamila.full_info())

```

Files:
Dealing with files very easy. The python library has a function for files called open(). This will allow you to read files from the computer.

Try this:

```py

# Make sure that your file in the same directory
file = open("test.txt", "r") # Load the file

# Run this then comment it out before you run the below function
print(file.read()) # Use the read() function to read the loaded files in file print it

# You can read lines from a file. 
# Uncomment this line before you can run this. 
print("\n")
print(file.readline())

# It is always good to close the file when done
file.close()

# Projects coming soon....
```
### Project 1 => Implementing your knowledge
Write a library book directory program using data structure called list.
Your program should be able to do this actions:
- Add/Append
- Search
- Delete

_____
Your tasks

1. Store book title in a list
2. Accept user input
3. Add a new book title to the library
4. Make sure that you can delete from the library
5. Search book's title in the library directory
6. Print book not found if there is no book
7. End program when when actions are done print out the lists.
8. Validate input as a string


### Project 2 => Files
Modify your project one code to do use files. Try safe your data to csv and be able to load data from 
from file type csv or json. 
1. Explore the python file library to see what else you can do.

### Project 3 => Code clean up.
Identify any thing that you can group together into a function.

#### ✌️ If you reached this far and are pleased, please star this repo or a feedback to improve this course. ✌️

## Links to resources

1. [Learn more about JSON data format](http://www.json.org/)

### [Next course]()




