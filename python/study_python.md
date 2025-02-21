# Python 3 Study

Disclaimer: Python 2 is legacy since 2020 meaning that it is not supported anymore.

*Resources*:
- (Python Full Course for Beginners)[https://www.youtube.com/watch?v=_uQrJ0TkZlc&t=109s]
- (Glossary)[https://www.w3schools.com/python/python_ref_glossary.asp]
- (Intermediate Python)[https://github.com/patrickloeber/python-engineer-notebooks/tree/master/advanced-python]
- (Intermediate Python Programming Course)[https://www.youtube.com/watch?v=HGOBQPFzWKo]
- (Python Tutorial for Beginners)[https://www.youtube.com/watch?v=t8pPdKYpowI]
- (Python API Dev)[https://www.youtube.com/watch?v=0sOvCWFmrtA]
- (REST API Crash Course - Introduction + Full Python API Tutorial)[https://www.youtube.com/watch?v=qbLc5a9jdXo]
- (FastAPI - A python framework | Full Course)[https://www.youtube.com/watch?v=7t2alSnE2-I]
- (FastAPI Tutorial - Building RESTful APIs with Python)[https://www.youtube.com/watch?v=GN6ICac3OXY]
- (How to Use FastAPI: A Detailed Python Tutorial)[https://www.youtube.com/watch?v=SORiTsvnU28]
- (Learn LangChain in 7 Easy Steps - Full Interactive Beginner Tutorial)[https://www.youtube.com/watch?v=8BV9TW490nQ]
- (Learn RAG From Scratch – Python AI Tutorial from a LangChain Engineer)[https://www.youtube.com/watch?v=sVcwVQRHIc8]
- (Python Programming Tutorial)[https://python-programming.quantecon.org/intro.html]

*Recommended courses*:
- (100 Days of Code: The Complete Python Pro Bootcamp
)[https://luxoft.udemy.com/course/100-days-of-code/learn/lecture/23103754#overview]
- (The Complete Python Bootcamp From Zero to Hero in Python)[https://luxoft.udemy.com/course/complete-python-bootcamp/learn/lecture/3421822#overview]

*Project ideas*:
- (How to make money from Python)[https://www.youtube.com/watch?v=r0m-iSnbKvc]

*Roadmap*:
- (Python Roadmap)[https://roadmap.sh/python]

## Table of Content

1. [Cheat sheet](#cheat-sheet)
    - [Python Cheat sheet](#python-cheat-sheet)
    - [FastAPI CheatSheet](#fastapi-cheatsheet)
    - [FastAPI Best practices](#fastapi-best-practices)
2. [Introduction](#introduction)
3. [Python keywords](#python-keywords)
4. [Variables](#variables)
    - [Integer](#integer)
    - [Float](#float)
    - [String](#string)
    - [Boolean](#boolean)
    - [Naming convention in Python](#naming-convention-in-python)
    - [NoneType Datatype](#notetype-datatype)
5. [Receive input from user](#receive-input-from-user)
6. [Built-in functions for type conversion](#built-in-functions-for-type-conversion)
7. [String](#string)
    - [Formatted strings](#formatted-strings)
    - [String methods](#string-methods)
8. [Arithmetic Operations](#arithmetic-operations)
    - [Addition](#addition)
    - [Subtract](#subtract)
    - [Division (float)](#division-float)
    - [Division (integer)](#division-integer)
    - [Mod](#mod)
    - [Multiply](#multiply)
    - [Power (exponentiation)](#power-exponentiation)
    - [Increment (shorter form)](#increment-shorter-form)
9. [Math built-in Functions](#math-built-in-functions)
10. [If statements or conditionals](#if-statements-or-conditionals)
    - [Logical operators for the if statements](#logical-operators-for-the-if-statements)
    - [Comparison operators (boolean expressions)](#comparison-operators-boolean-expressions)
11. [Loops](#loops)
    - [While Loop](#while-loop)
    - [For Loop](#for-loop)
    - [Nested loop](#nested-loop)
12. [Lists](#lists)
    - [List methods](#list-methods)
13. [Tuples](#tuples)
    - [Unpacking](#unpacking)
14. [Dictionaries](#dictionaries)
15. [Sets](#sets)
16. [Collection](#collection)
    - [Counter](#counter)
    - [namedtuple](#namedtuple)
    - [OrderedDict](#ordereddict)
    - [defaultdict](#defaultdict)
    - [deque](#deque)
17. [Itertools](#itertools)
    - [Product (Cartesian Product)](#product-cartesian-product)
    - [Permutations](#permutations)
    - [Combinations](#combinations)
    - [Accumulate](#accumulate)
    - [Groupby](#groupby)
    - [Infinite iterator](#infinite-iterator)
18. [Functions](#functions)
    - [Lambda Functions](#lambda-functions)
    - [Mapping function](#mapping-function)
    - [Filter function](#filter-function)
    - [Reduce function](#reduce-function)
19. [Exceptions](#exceptions)
    - [Raising Exceptions](#raising-exceptions)
    - [Custom Exceptions](#custom-exceptions)
20. [Comments](#comments)
21. [Logging](#logging)
    - [Logging handler](#logging-handler)
22. [Classes](#classes)
    - [Inheritance](#inheritance)
    - [Polymorphism](#polymorphism)
23. [Magic methods](#magic-methods)
24. [JSON in Python](#json-in-python)
    - [Serialization/encoding](#serializationencoding)
    - [Json with classes](#json-with-classes)
25. [Modules](#modules)
26. [Packages](#packages)
    - [Random library/module](#random-librarymodule)
27. [Working with files and directories](#working-with-files-and-directories)
28. [Decorators](#decorators)
29. [Generators](#generators)
30. [Threading, Multithreading & Multiprocessing](#threading-multithreading--multiprocessing)
    - [Process vs Thread](#process-vs-thread)
    - [Multiprocessing](#multiprocessing)
    - [Multitheading](#multitheading)
    - [Sharing data between threads with Lock](#sharing-data-between-threads-with-lock)
    - [Sharing data between threads with queues](#sharing-data-between-threads-with-queues)
    - [Sharing data between processes](#sharing-data-between-processes)
    - [Process Pool](#process-pool)
31. [Shallow vs Deep Copying](#shallow-vs-deep-copying)
32. [Context Managers](#context-managers)
33. [Pypi and Pip](#pypi-and-pip)
    - [Steps to create a Recommendation System](#steps-to-create-a-recommendation-system)
34. [Django](#django)
35. [FastAPI](#fastapi)
36. [LangChain](#langchain)
    - [Chains, Prompts & Loaders](#chains-prompts--loaders)
    - [LangChain Expression Language (LCEL) & Runnables](#langchain-expression-language--lcel--runnables)
    - [Splitters & Retrievers](#splitters--retrievers)
    - [RAG](#rag)
    - [Tools](#tools)
    - [Agents](#agents)
    - [RAG Deep Dive](#rag-deep-dive)
    - [AI Agentic Design Patterns](#ai-agentic-design-patterns)
37. [Troubleshooting](#troubleshooting)
38. [Algorithms and Data Structures](#algorithms-and-data-structures)
39. [Interview Questions (for Junior, Middle and Senior Developers)](#interview-questions-for-junior-middle-and-senior-developers)

## Cheat sheet:

- (Python Cheat sheet)[https://github.com/gto76/python-cheatsheet]
- (FastAPI CheatSheet)[https://studygyaan.com/cheatsheet/fastapi]
- (FastAPI Best practices)[https://dev.to/devasservice/fastapi-best-practices-a-condensed-guide-with-examples-3pa5]

*Note*: You can search on Google for any type of cheat sheets (or for best practices) for each framework.

## Introduction

Python is a high-level, interpreted (dynamically typed), case-sensitive, interactive and object oriented scripting language. It is used in different areas such as: Web Development, Data Science, AI/ML, Automation, Web Scraping, etc.

To print something on the screen:
```
print("a string") # a string
```

## Python keywords

Below is the list of all reserved Python keywords:

(list)[https://www.programiz.com/python-programming/keyword-list]

The list can also be accessed programatically:
```
import keyword
print(keyword.kwlist)
```

##Variables

A variable consist of a identifier and a value.
We can define different types of data:

-integer
```
price = 10
```

-float
```
price = 10.5
```

-string
```
aString = 'Price'
```

-boolean
```
is_added = True
```

*Naming convention in Python*: lowercase letters and underscores

*Note*: It is possible to have a NoneType datatype and the value can be only None (similar to null from Java).

(All variable types)[https://www.w3schools.com/python/python_datatypes.asp]

##Receive input from user

To gather an input from user use the following function:

```
name = input('What is your name? ') # input returns a string value
```

## Built-in functions for type conversion

Example of usage:

```
price = '2000'
int(price)
```

Other built-in functions:
```
float()
string()/str()
bool()
```
(Complete list of built-in functions)[https://www.w3schools.com/python/python_ref_functions.asp]

Retrieve type of variable:
```
type(variable)
```

##String

String is an ordered, immutable, text representation.
You can use 2 type of quotes: '' and "", depending of the scenario. For example:

You can't have:
```
course = 'Python's for beginners'
```

You can have:
```
course = "Python's for beginners"
```

For multiline strings use triple quotes ''':
```
mail = '''
Hello!
Bye!
'''
print(mail)
# Hello!
# Bye!
```

To retrieve character of a certain index:
```
print(course[0]) # P
```

To get the last character:
```
print(course[-1]) # s
//or
print(course[len(course) - 1] # s
```

To print a substring/slice:

```
# This will print the characters from index 0 to index 2
print(course[0:3]) # Pyt
# This will print the whole string (all characters)
print(course[0:]) # Python's for beginners
# This will print the whole string without the first character
print(course[1:]) # ython's for beginners
# This will print the first 5 characters of the string
print(course[:5]) # Pytho
# This will print the whole string
print(course[:]) # Python's for beginners
# This will print the whole string without the last character
print(course[0:-1]) # Python's for beginner
# This will print every second character
print(course[::2]) # Pto' o einr
# This will reverse the string
print(course[::-1]) # rennigeb rof s'nohtyP
```

### Formatted strings

Concatenate (naive):
```
stringA = 'John'
stringB = 'Smith'
message = stringA + '[' + stringB + ']'
print(message) # John[Smith]
```

Concatenate (formatted way):
```
stringA = 'John'
stringB = 'Smith'
msg = f'{stringA} [{stringB]}'
# msg = "{} [{}]".format(stringA, stringB)
# msg = "%s" % stringA
print(msg) # John [Smith]
```

## String (methods)[https://www.w3schools.com/python/python_ref_string.asp]

Lenght of a string:
```
print(len('Something')) # 9
```

*Note*: Function — a set of instructions that perform a task. Method — a set of instructions that are associated with an object.

Convert string to upper case:
```
course = 'Python'
print(course.upper()) # PYTHON
```

Convert string to lower case:
```
course = 'Python'
print(course.lower()) # python
```

Find a character or a sequence of characters:
```
course = 'Python'
print(course.find('P')) # 0
print(course.find('yt')) # 1
```

Replace strings:
```
course = 'Python'
print(course.replace('yth', 'atre')) # Patreon
```

Check if a sequence of characters can be found in a string:
```
course = 'Python'
print('yth' in course) # True
```

## Arithmetic Operations

Addition:

```
print(2 + 2) # 4
```

Substract
```
print(5 - 2) # 3
```

Division (float)
```
print(10 / 3) # 3.3333333333333335
```

Division (integer)
```
print(10 // 3) # 3
```

Mod
```
print(10 % 3) # 1
```

Multiply
```
print(3 * 3) # 9
```

Power (exponentiation)
```
print(10 ** 3) # 1000
```

Increment (shorter form)
```
x = 3
x += 5
print(x) # 8
```

*Note*: We can do the same thing with other operations

## Math built-in Functions

Round function
```
x = 2.9
print(round(x)) # 3
```

Absolute value
```
x = -2.9
print(abs(x)) # 2.9
```

For complex math calculation import math module/package that contains a bunch of reusable functions (such as sin,cosine, etc.):
```
import math
print(math.ceil(2.9)) # 3
print(math.floor(2.9)) # 2

```

## If statements or conditionals

To implement an if statement you need to use the "if" keyword.
Example:
```
is_hot = True
is_cold = False
if is_hot:
   print("It's a hot day")
elif is_cold:
   print("It's a cold day")
else:
   print("It's a lovely day")
print("Enjoy your day")
# It's a hot day
# Enjoy your day
```

### Logical operators for the if staments

- and: both conditions must be true
- not: inverts any boolean value
- or: at least one must be true

### Comparison operators (boolean expressions)

- Greater than ">"
- Greater than or equal to ">="
- Less than "<"
- Smaller than or equal to "<="
- Equal to "=="
- Not equal "!="

(All operators)[https://www.w3schools.com/python/python_operators.asp]

## Loops

While Loop:
```
while condition:
  #instructions
else: # If break is not invoked in the while loop
  #Other instructions
```

For Loop:
```
for item in 'Python':
   print(item)
# P
# y
# t
# h
# o
# n

# You can also loop over lists, dictionaries, etc.

# You can use built-in function range(start, end, step)
for item in range(0, 3):
  print(item)

# 0
# 1
# 2

# Nested loop

for x in range(2):
  for y in range (2):
    print(f'({x}, {y})')

# 0, 0
# 0, 1
# 1, 0
# 1, 1
```

## Lists

List is an ordered, mutable collection of elements.

Example:

```
names = ['John', 'Smith']
print(names) # ['John', 'Smith']
print(names[0]) # John
print(names[1:] # Smith

# 2D List
matrix = [[1,2,3], [4,5,6], [7,8,9]]
print(matrix[0][1]) # 2
```

### List methods

```
numbers = [4, 2, 7, 8, 3]
numbers.append(14)
print(numbers) # [4, 2, 7, 8, 3, 14]
numbers.insert(0, 10)
print(numbers) # [10, 4, 2, 7, 8, 3, 14]
numbers.remove(3)
print(numbers) # [10, 4, 2, 7, 8, 14]
print(numbers.index(4)) # 1
print(23 in numbers) # False
print(numbers.count(10)) # 1
numbers.sort()
print(numbers) # [2, 4, 7, 8, 10, 14]
numbers.reverse()
print(numbers) # [14, 10, 8, 7, 4, 2]
numbers2 = numbers.copy()
print(numbers2) # [14, 10, 8, 7, 4, 2]
```

(All list methods)[https://www.w3schools.com/python/python_ref_list.asp].

## Tuples

Unlike lists, tuples are *immutable*.

Example:
```
numbers = (1,2,3)
print(numbers[0]) # 1
numbers[0] = 42
print(numbers) # Error
```

(List of all tuple methods)[https://www.w3schools.com/python/python_ref_tuple.asp].
### Unpacking

This feature works for both lists and tuples as well.
Example:

```
coordinates = (1,2,3)
x, y, z = coordinates
print(x) # 1
print(y) # 2
print(z) # 3
```

## Dictionaries

A dictionary is an unordered, mutable colection of key-value pairs (similar to Map interface from Java). The key must be unique.

```
customer = {
"name": "John Doe",
"age": 30,
"is_verified": True
}

print(customer["name"]) # John Doe
print(customer.get("age")) # 30
# You can add a default value to get method
print(customer.get("something", "good")) # good
customer["birthday"] = "1 Jan 1980"
print(customer.get("birthday")) # 1 Jan 1980
```

(List of all dictionary methods)[https://www.w3schools.com/python/python_ref_dictionary.asp]

## Sets

Mutable collection of unordered, unique items.

Example:
```
thisset = {"apple", "banana", "cherry", "apple"}

print(thisset)

# using set() built-in function

thisset1 = set("a", "b", "a", "c") # or set(["a", "b", "a", "c"])
print(thisset1)
thisset1.add("d")
print(thisset1)
```

Copy a set:
```
setA = {1, 2, 3}
setB = setA # This will copy only the reference
setB = setA.copy # This will copy the actual set
# setB = set(setA) works too!
```

Immutable set:
```
a = frozenset([1, 2, 3, 4])
print(a)
```

(List of all set methods)[https://www.w3schools.com/python/python_ref_set.asp]

## Collection

### Counter

It is a container that stores the elements as dictionary keys and their counts as dictionary values.

```
from collections import Counter
a = "aaaaabbbcccc"
my_counter = Counter(a)
print(my_counter) # Counter({'a': 5, 'b': 3, 'c': 4})
print(my_counter.items) # dict_items([('a', 5), ('b', 3), ('c', 4)])
print(my_counter.keys())
print(my_counter.values())
print(my_counter.most_common(1)) # [('a', 5)]
print(my_counter.most_common(1)[0][0]) # a
print(list(my_counter.elements()))
```

### namedtuple

It is a way to create lightweight objects similar to struct.

```
from collections import namedtuple

Point = namedtuple('Point', 'x,y')
pt = Point(1, -4)
print(pt) # Point(x=1, y=4)
print(pt.x) # 1
```

### OrderedDict

It is like regular dictionary, but it remembers the order that the items were inserted.

*Note*: Since python 3.7, the normal dictionary can also remember the order.

```
from collections import OrderedDict

ordered_dict = OrderedDict()
ordered_dict['a'] = 1
ordered_dict['b'] = 2
ordered_dict['c'] = 3

print(ordered_dict) # ([('a', 1), ('b', 2), ('c', 3)])

```

### defaultdict

Just like a normal dictionary but it has a default value if the key has not been set yet.

```
from collections import defaultdict

d = defaultdict(int)
d['a'] = 1
d['b'] = 2
print(d)
print(d['c']) # 0
```

### deque

It is a double ended queue to add or remove elements from both ends.

```
from collections import deque

d = deque()
d.append(1)
d.append(2)
print(d) # deque([1,2])
# d.appendLeft(3)
# d.pop()
# d.popleft()
# d.clear()
# d.extend([4,5,6])
# d.extendleft([7,8,9])
# d.rotate(1)
```

## Itertools

Iterables are data types that can be used in a for loop (to iterate through an array/list for example).


### Product (Cartesian Product)

```
from itertools import product

a = [1, 2]
b = [3, 4]

prod = product(a,b)
print(list(prod)) # [(1,3), (1,4), (2,3), (2, 4)]
```

### Permutations

```
from itertools import permutations

a = [1, 2, 3]

perm = permutations(a)
print(list(perm))
```

### Combinations

```
from itertools import combinations

a = [1, 2, 3, 4]

comb = combinations(a, 2)
print(list(comb))
```

### Accumulate

Let's say that we have a binary function as an input. The output will be the result of an operation performed on that function (for example sum). In the context of a list, the accumulator will take 2 elements at a time as a binary function and it will output a result of a specific operation.

```
from intertools import accumulate

a = [1, 2, 3, 4]
acc = accumulate(a) # or accumulate(a, func=max)
print(list(acc)) # [1, 3, 6, 10]
```

### Groupby


```
from intertools import groupby


def smaller_than_3(x):
  return x < 3


a = [1, 2, 3, 4]
group_obj = groupby(a, key=smaller_than_3)
for key, value in group_obj:
  print(key, list(value))
```

### Infinite iterator

```
from intertools import count, cycle, repeat
```

## Functions

Functions are used to break the code in smaller, reusable chunks to better organize the code.

```
def greet_user():
  print('Hi!')
  print('Welcome!')


greet_user()
# Hi!
# Welcome!
```

You can declare functions with parameters and return type:

```
def greet_user(name):
  print(f'Hi {name}!')

def square(number):
  return number * number


greet_user('John') # Hi John!
greet_user(name = 'John') # Hi John
print(square(3)) # 9
```

*Note*: If you don't add a return keyword in a defined function, python function will automatically return None by default.

You can use an invariable number of arguments and keywords arguments.
```
def foo(*args, **kwargs):
  for arg in args:
    print(arg)
  for key in kwargs:
    print(key, kwargs[key])

foo(1, 2, 3, four=4, five=5)
```

To force the use of keyword arguments:
```
def foo(a, b, *, c):
  print(a, b, c)

foo(1, 2, c=3)
```

Arguments unpacking or keyword args unpacking:
```
def foo(a, b, c):
  print(a, b, c)

my_list = [0, 1, 2]
my_dictionary = {'a': 1, 'b': 2, 'c': 3}
foo(*my_list)
foo(**my_dictionary)
```
### Lambda Functions

It is a small one line anonymous function that is defined without a name.

```
# syntax: lambda arguments: expression

add10 = lambda x: x + 10
print(add10(5)) # 15

# same thing as
def add10_funct(x):
  return x + 10
```

*Mapping function*

```
# map(func, seq)

a = [1, 2, 3, 4, 5]
b = map(lambda x: x * 2, a)
print(list(b)) # [2, 4, 6, 8, 10]
# or
c = [x*2 for x in a]
print(c) # [2, 4, 6, 8, 10]
```

*Filter function*

```
# filter(func, seq)
a = [1, 2, 3, 4, 5]
b = filter(lambda x: x%2==0, a)
print(list(b)) # [2, 4]
c  = [x for x in a if x%2==0]
print(c) # [2, 4]
```

*Reduce function*

```
# reduce(func, seq)
from functools import reduce

a = [1, 2, 3, 4]
prod = reduce(lambda x,y: x*y, a)
print(prod) # 24

```
## Exceptions

The difference between an error and exception in Python is that the error would not let you run the program if it finds mistakes (at compile time) while the exception can occur during the runtime.

To handle exceptions you can implement try-except block:

```
try:
  age = int(input('Age: '))
  print(age)
except ValueError:
  print('Invalid value!')
# If you input '30' the output will be '30'
# If you input 'asdf' the output will be 'Invalid value!'
except Exception as e:
  print(e)
else: # It will run if no exception occured
  print('Everything is fine!')
finally: # It will run no matter if there was an exception or not
  print('Cleaning up...')

```

(List of Exceptions)[https://www.w3schools.com/python/python_ref_exceptions.asp]

To raise(or throw) an exception:

```
x = -5
if x < 0:
  raise Exception('x should be positive)
assert (x>=0), 'x is not positive' # It will raise an AssertionError
```

To create custom exceptions:
```
class ValueTooHighError(Exception):
  pass

class ValueTooSmallError(Exception):
  def __init__(self, message, value):
     self.message = message
     self.value = value

def test_value(x):
  if x > 100:
     raise ValueTooHighError('value is too high')
  if x < 5:
     raise ValueTooSmallError('value is too small', x)

try:
  test_value(200)
except ValueTooHighError as e:
  print(e)
except ValueTooSmallError as e:
  print(e.message, e.value)
```

## Comments

Are lines of code that are ignored during runtime that are useful to explain some code fragments.
```
# You can add comments like this
print('Yes')
"""
This is
a multiline
comment
"""
```

## Logging

A way to customize the information that a system will display/print during runtime.

```
# helper.py
logger = logging.getLogger(__name__)
# You can also set propagate to False (By default is set to True
# logger.propagete = False
logger.info('hello from helper')

# main.py
import logging

logging.basicConfig(level=logging.DEBUG, format='%{asctime}s - %{name}s - %{levelname}s - %{message}s', datefmt='%m/%d%Y %H:%M:%S') # more details about config in Python docs
logging.debug('This is a debug message')
logging.info('This is a info message')
logging.warning('This is a warning message')
logging.error('This is a error message')
logging.critical('This is a critical message')
```

Logging handler
```
# main.py
import logging

logger = logging.getLogger(__name__)

# Create Handler
stream_h = logging.StreamHandler()
file_h = logging.FileHandler('file.log')

# Set level and the format
stream_h.setLevel(logging.WARNING)
file_h.setLevel(logging.ERROR)

formatter = logging.Formatter('%{name}s - %{levelname}s - %{message}s')
stream_h.setFormatter(formatter)
file_h.setFormatter(formatter)

logger.addHandler(stream_h)
logger.addHandler(file_h)

logger.warning('this is a warning')
logger.error('this is an error')
```

*Note*: You can config the logging either by using a file called logging.conf, either by using dictionaries. Click (this link)[https://coderzcolumn.com/tutorials/python/logging-config-simple-guide-to-configure-loggers-from-dictionary-and-config-files-in-python] or (the documentation)[https://docs.python.org/3/library/logging.config.html] to see more examples.

For troubleshooting you can also include stack trace in the logs:
```
import logging

try:
  a = [1, 2, 3]
  val = a[4]
except IndexError as e:
  logging.error(e, exc_info=True)
```

For saving logs in separate files:
```
import logging
from logging.handlers import TimedRotatingFileHandler, RotatingFileHandler

logger = logging.getLogger(__name__)
logger.setLevel(logging.INFO)

# roll over after 2KB, an keep backup logs app.log.1, app.log.2, etc.
handler = RotatingFileHandler('app.log', maxBytex=2000, backupCount=5)
logger.addHandler(handler)

for _ in range(10000)
   logger.info('Hello, world!')

# To log based on how much time an application is running
# handler = TimedRotatingFileHandler('timed_test.log', when='m', interval=1, backupCount=5)
```

## Classes

Class is like a blueprint to instatiate/create objects of custom types. Each instance of a class or object is different from other.

```
class Point:
  def move(self):
     print("move")

  def draw(self):
     print("draw")


point1 = Point()
point1.x = 12
print(point1.x) # 12
point1.move() # move
```

Classes are implementing a default constructor with no parameters. However, you can implement custom constructors with parameters/attributes.

```
class Point:
  # This gets called whenever a new object is created
  def __init__(self, x, y):
      self.x = x
      self.y = y

  def move(self):
     print("move")

  def draw(self):
     print("draw")


point1 = Point(10, 20)
print(point1.x) # 10
```

*Note*: **self** is a reference to the current object.

### Inheritance

Inheritance is a fundamental concept in object-oriented programming that allows a new class (child or subclass) to acquire the properties and behaviors of an existing class (parent or superclass). In Python, inheritance enables the creation of a hierarchical relationship between classes, promoting code reusability and organization. The child class inherits attributes and methods from the parent class and can also introduce its own unique attributes and methods or override existing ones to modify behavior.

```
class Animal:
  def walk(self):
     print("Walk")


class Dog(Animal):
  pass # Python interpreter will pass this line


class Cat(Animal):
  pass


dog = Dog()
dog.walk() # Walk
```

### Polymorphism

Polymorphism is often used in Class methods, where we can have multiple classes with the same method name.

```
class Car:
  def __init__(self, brand, model):
    self.brand = brand
    self.model = model

  def move(self):
    print("Drive!")

class Boat:
  def __init__(self, brand, model):
    self.brand = brand
    self.model = model

  def move(self):
    print("Sail!")

class Plane:
  def __init__(self, brand, model):
    self.brand = brand
    self.model = model

  def move(self):
    print("Fly!")

car1 = Car("Ford", "Mustang")       #Create a Car object
boat1 = Boat("Ibiza", "Touring 20") #Create a Boat object
plane1 = Plane("Boeing", "747")     #Create a Plane object

for x in (car1, boat1, plane1):
  x.move()
# Drive!
# Sail!
# Fly!
```

## (Magic methods)[https://realpython.com/python-magic-methods/]

In Python, everything we create is an object.
Magic methods are methods defined in classes that confer custom functionality to instantiated objects. We can somewhat liken them to the methods that Java objects inherit from the Object class.

## JSON in Python

### Serialization/encoding:

```
import json

person = {"name": "John", "age": 30, "city": "London", "married": False, "titles": ["engineer", "programmer"]}

# Serialization/encoding
personJSON = json.dumps(person, indent=4)
print(personJSON)

# To save the converted JSON in a separate file
with open('person.json', 'w') as file:
  json.dump(person, file, indent=4)

# Deserialization/Decoding
person = json.loads(personJSON)
print(person)

# Decode from a json file
with open('person.json', 'r') as file:
  person = json.load(file)
  print(person)
```

### Json with classes
```
import json

class User:

   def __init__(self, name, age):
      self.name = name
      self.age = age


user = User('Max', 27)

def encode_user(o):
   if isinstance(o, User):
     return {'name': o.name, 'age': o.age, o.__class__.__name__: True}
   else:
     raise TypeError('Object of type User is not JSOn serializable')

from json import JSONEncoder
class UserEncoder(JSONEncoder):
   def default(self, o):
      if isinstance(o, User):
         return {'name': o.name, 'age': o.age, o.__class__.__name__: True}
      return JSONEncoder.default(self, o)

def decode_user(dct):
   if User.__name__ in dct:
      return User(name=dct['name'], age=dct['age'])
   return dct

userJSON = json.dumps(user, default=encode_user, indent=4)
# userJSON = json.dumps(user, cls=UserEncoder, indent=4)
# userJSON = UserEncoder().encode(user)
print(userJSON)

# To decode a JSON
user = json.loads(userJSON)
# user = json.loads(userJSON, object_hook=decode_user)
print(user)       
```

More details can be found (here)[https://www.w3schools.com/python/python_json.asp] or (here)[https://realpython.com/python-json/]

## Modules

Python files that help developers to organize their codebase.

```
# example.py

### defined methods
def function():
  print("something")

# app.py

import example
# from example import function

example.function() # something
#function() - This will output 'something' as well
```

## Packages

A container to group multiple modules(files) under the same package(folder).

__init__.py file is a way to tell Python interpreter that a certain folder is a package.

Example of package/module importing:
```
import package.module
# import package
# import package.module as mod
# from package.module import function1, function2
# from package import module
# from package import *
```

(Index of Python Built-in Modules)[https://docs.python.org/3/py-modindex.html]

### Random library/module

```
import random

for i in range(3):
   print(random.randint(10,20)) # This will print 3 random values from 10 to 20
```

## Working with files and directories

First, import Path object from pathlib package:

```
from pathlib import Path
```

Retrieve relative path:
```
path = Path("name_of_a _folder/file")
print(path.exists()) # Output is a boolean value
```

Create a directory:
```
path = Path("name_of_a _folder")
path.mkdir() # It will create a directory with the specified name
```

Remove a directory
```
path = Path("name_of_a _folder")
path.rmdir() # It will delete the directory with the specified name if it exists
```

Search for files and directory in a specified path:
```
path = Path() # current directory (project directory)
print(path.glob('*')) # Search for all files and directories
print(path.glob('*.*') # Search for all files
for file in path.glob('*'):
   print(file) # to retrieve all files and directories
```

## Decorators

They are used to extend some functionality of a function similar to Spring Annotations:

```
import functools
def start_end_decorator1(func):
   def wrapper():
     print('Start')
     func()
     print('End')
   return wrapper


def start_end_decorator2(func):
   @functools.wraps(func)
   def wrapper(*args, **kwargs): # To use as many arguments and keyword arguments you want
     print('Start')
     result = func(*args, **kwargs)
     print('End')
     return result
   return wrapper

@start_end_decorator1
def print_name():
   print('Alex')

@start_end_decorator2
def print_age(x):
   return x

# @debug Decorator can also be used for debugging purposes or Class decorator to check (for example) the time execution of a function
```

More details can be found (here)[https://realpython.com/primer-on-python-decorators/].

## Generators

A Python technique to generate objects (or a list/iterator) in a lazy way, i.e only when we need the specific objects.

```
def mygenerator():
  yield 1
  yield 2

g = mygenerator()

value = next(g)
print(value) # 1
```

More details can be found (here)[https://www.geeksforgeeks.org/generators-in-python/] or (here with some use cases)[https://realpython.com/introduction-to-python-generators/].

## Threading, Multithreading & Multiprocessing

Process vs Thread

- Process(An instance of a program; e.g Python interpreter):
  - It uses multiple CPUs and cores
  - Separate memory space -> Memory is not shared between processe
  - Great for CPU-bound programming
  - New process is started independently from other processes
  - Processes are killable(interruptable)
  - One GIL for each process
  - It is heavyweight
  - Starting a process is slower than starting a thread
  - More memory
  - IPC (inter-process communication) is more complicated

- Thread(is an entity within a process that can be scheduled):
  - A process can spawn multiple threads
  - All threads within a process share the same memory
  - Lightweight
  - Starting a thread is faster
  - Great for I/O-bound tasks
  - Threading is limited by GIL: Only one thread at a time
  - No effect for CPU-bound tasks
  - Not killable
  - Careful with race conditions

- GIL(Global interpreter lock):
  - A lock that allows only one thread at a time to execute in Python
  - Needed in CPython because memory management is not thread-safe
  - To avoid GIL and its' limitations (to do parallel computing) you can use multiprocessing, or use different, free-threaded Python implementation(Jython), or use Python as a wrapper for third-party libraries (C/C++) such as numpy,scipy

Multiprocessing:
```
from multiprocessing import Process
import os
import time

def square_numbers():
  for i in range(100):
    i * i
    time.sleep(0.1)

processes = []
num_processes = os.cpu_count() # number of CPUs on the machine

# create processes and assing a function for each process
for i in range(num_processes):
  p = Process(target=square_numbers) # another parameter is args
  processes.append(p)

# start all processes
for p in processes:
  p.start()

# join: Wait for all the processes to finish before ending the program while blocking the main process
for p in processes:
  p.join()

print('end main')
```

Multitheading:
```
from theading import Thread
import time

def square_numbers():
  for i in range(100):
    i * i
    time.sleep(0.1)

if __name__ == "__main__":
  threads = []
  num_threads = 10

  # create processes
  for i in range(num_threads):
    t = Thread(target=square_numbers) # another parameter is args
    threads.append(t)

  # start
  for t in threads:
    t.start()

  # join: Wait for all the threads to finish before ending the program while blocking the main thread
  for t in threads:
    t.join()

  print('end main')
```

Sharing data between threads with Lock:
```
from threading import Thread, Lock
from queue import Queue
import time

database_value = 0

def increase(lock):
  global database_value

  lock.acquire() # you can also use "with lock:" context manager
  local_copy = database_value

  # processing
  local_copy += 1
  time.sleep(0.1)

  database_value = local_copy
  lock.release()

if __name__ == "__main__":
  lock = Lock()
  print('start value', database_value)


  # We need to use Lock to avoid race condition
  thread1 = Thread(target=increase, args=(lock,))
  thread2 = Thread(target=increase, args=(lock,))

  thread1.start()
  thread2.start()

  thread1.join()
  thread2.join()

  print('end value', database_value)
  print('end main')
```

Sharing data between threads with queues:
```
from threading import Thread, Lock, current_thread
from queue import Queue
import time

def worker(q, lock):
  while True:
    value = q.get()

    # processing...
    with lock:
       print(f'in {current_thread().name} got {value}')
    q.task_done()

if __name__ == "__main__":
  q = Queue()
  lock = Lock()

  num_threads = 10

  for i in range(num_threads):
    thread = Thread(target=worker, args=(q, lock))
    thread.daemon=True # By default, it is set to False
    thread.start()
  print('end main')

  for i in range(1, 21):
     q.put(i)

  q.join()
```

*Note*: Daemon threads are background threads that automatically exit as soon as all non-daemon threads (typically the main program) have completed.

Sharing data between processes(it is a bit different because they don't share the same memory space):
```
from multiprocessing import Process, Value, Array, Lock
import os
import time

# numbers as parameter for shared array example
def add_100(number, lock):
  for i in range(100):
    time.sleep(0.01)
    lock.acquire() # you can context manager "with lock:"
    number.value += 1
    lock.release()
    # with lock:
      # number.value += 1

  # array variant
  # for i in range(100):
  #   time.sleep(0.01)
  #    for i in range(len(numbers)):
  #      with lock:
  #        numbers[i] += 1


if __name__ == "__main__":
  lock = Lock()
  shared_number = Value('i', 0)
  # shared_array = Array('d', [0.0, 100.0, 200.0])
  print('Number at beginning is', shared_number.value)
  # print('Array at beginning is', shared_array[:])

  p1 = Process(target=add_100, args(shared_number, lock))
  p2 = Process(target=add_100, args(shared_number, lock))

  # p1 = Process(target=add_100, args(shared_array, lock))
  # p2 = Process(target=add_100, args(shared_array, lock))

  p1.start()
  p2.start()

  p1.join()
  p2.join()

  print('Number at end is', shared_number.value)
```

*Note*: You can also use queues to shared data between processes

Process Pool (to manage multiple processes):
```
from multiprocessing import Pool

def cube(number):
  return number * number * number

if __name__ == "__main__"

  numbers = range(10)
  pool = Pool()

  # Important pool methods: map, apply, join, close
  result = pool.map(cube, numbers)

  pool.close()
  pool.join()

  print(result)
```

## Shallow vs Deep Copying

A shallow copy is one level deep copy, only references of nested child objects (it doesn't work for matrices for example) while deep copy is a full independent copy

```
import copy

org = [0, 1, 2, 3]
# shallow copy
cpy = copy.copy(org)
# cpy = list(org)
# cpy = org.copy()
# cpy = org will only copy the reference

cpy[0] = -10

print(cpy)
print(org)

# deep copy
org1 = [[1, 2, 3], [5, 6, 7]]
cpy1 = copy.deepcopy(org)
cpy1[0][1] = -10

print(cpy1)
print(org1)
```

We can use shallow copy and deep copy for custom objects:
```
import copy

class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

class Company:
  def __init__(self, boss, employee):
    self.boss = boss
    self.employee = employee

p1 = Person('Alex', 27)
# Shallow copy
p2 = copy.copy(p1)
p3 = Person('Joe', 21)

p2.age = 28

print(p1)
print(p2)

company = Company(p1, p3)
# Deep copy
company_clone = copy.deepcopy(company)

company_clone.boss.age = 56

print(company)
print(company_clone)
```

## Context Managers

Context managers allow you to allocate and release resources precisely when you want to.

It is used for example to write some files:
```
with open('some_file', 'w') as opened_file:
    opened_file.write('Learn Python!')
```

which is equivalent to:
```
file = open('some_file', 'w')
try:
    file.write('Learn Python!')
finally:
    file.close()
```

You can create a custom context manager either with classes:
```
class ManagedFile:
    def __init__(self, filename):
        print('init', filename)
        self.filename = filename

    def __enter__(self):
        print('enter')
        self.file = open(self.filename, 'w')
        return self.file

    def __exit__(self, exc_type, exc_value, exc_traceback):
        if self.file:
            self.file.close()
        # Handle the exceptions
        if exc_type is not None:
            print('Exception has been handled')
        print('exit')
        return True


with ManagedFile('notes.txt') as f:
    print('processing...')
    f.write('Hello, world!')
    f.do_something()
print('continuing...')
```

either with functions:
```
from contextlib import contextmanager

@contextmanager
def open_file(filename):
    f = open(filename, 'w')
    try:
        yield f
    finally:
        f.close()

with open_file('notes.txt') as f:
    f.write('Hello, world!')
```

More details can be found (here)[https://book.pythontips.com/en/latest/context_managers.html].

## Pypi and Pip

Go to (Pypi)[pypi.org] to search for third-party libraries/modules/packages to install in your projects. To install a library run the following command:

```
pip install <library>
```

Important packages for machine learning:

```
import numpy as np # used for data preprocessing
import pandas as pd # used for data cleaning
import matplotlib.pyplot as plt # used for data visualization
import seaborn as sns # used for data visualization
```

*Note*: It is recommended to use (Jupyter Notebook)[https://jupyter.org/try-jupyter/notebooks/?path=notebooks/Intro.ipynb] or (Google Colab)[https://colab.google/] for machine learning projects.

Steps to create a Recommendation System:
 1. Import the data (from (Kaggle)[https://kaggle.com] for example)
```
import pandas as pd
data = pd.read_csv('name_of_the_csv_file')
```
 2. Prepare the data (Clean, Normalize, etc.)
```
from sklearn.preprocessing import StandardScaler

X = data.drop(columns=['name_of_the_column']) # delete a column from the csv file

# Extract numerical features
num_features = ['feature1', 'feature2', 'feature3']
X = data[num_features]

# Normalize data using StandardScaler
scaler = StandardScaler()
X_normalized = scaler.fit_transform(X)
```
 3. Split the data into Training/Test Sets
```
from sklearn.model_selection import train_test_split
y = data[feature]
X_train, X_test, y_train, Y_test = train_test_split(X, y, test_size=0.2)
```
 4. Create a model
```
from sklearn.tree import DecisionTreeClassifier

model = DecisionTreeClassifier()
```
*Note*: Navigate to (sklearn)[https://scikit-learn.org/stable/] to see the list of all algorithms suited for various types of ML tasks.
 5. Train the model
```
model.fit(X_train, y_train)
```
 6. Make Predictions
```
predictions =model.predict(X_test)
print(predictions)
```
 7. Evaluate and improve
```
from sklearn.metrics import accuracy_score

score = accuracy_score(y_test, predictions) # it will return a score within 0 and 1 range (1 meaning 100% accuracy)
score # or print(score)
```

8. Persist the model
```
from sklearn.externals import joblib
joblib.dump(model, 'model.joblib')
# then use it for prediction (wihtout training it each time when you want to use a model)
model = joblib.load('model.joblib')
predictions = model.predict(...)
predictions
```

9. Visualize predictions/data

## Section

## (Django)[https://www.djangoproject.com/]

A Python web framework that help devs to build applications fast. It is suitable for medium-sized or large-sized applications (also used in enterprise).

To create a project from terminal:
```
pip install django
django-admin startproject <project_name> .
```

To run a project:
```
# python on Windows and python3 on Mac
python3 manage.py runserver
```

To create a package/module:
```
python3 manage.py startapp <package_name>
```

To handle a request/ create a route:
```
# in views.py
from django.hpp import HttpResponse
from django.shortcuts import render


def index(httpRequest):
   # return Entity.objects.all() or .save(), etc.
   return HttpResponse('Hello Word')

# in urls.py module/package define paths
from django.urls import path
from . import views


urlpatterns = [
path('', views.index) # We pass a reference to index function so that Djago will take care of calling the function at runtime
]

# in urls.py from application define paths
from django.urls import path, include


patterns = [
path('package/', include('package.urls')) # We pass a reference to package's defined urls
]  
```

To create a model in Django that interacts with Database:

```
# in models.py
from django.db import models


class Product(models.Model):
   name = models.CharField(max_length=255) # represents Text data
   price = models.FloatField() # represents float number data
   stock = models.IntegerField() # represents integer number data
   image = models.CharField(max_length=2083)
```

Command for creating a model ready for integration (or migration) with database:
```
python3 manage.py makemigrations
```

*Note*: Some configurations in settings.py should be done before running the command.

Command for generating a table in database:
```
python3 manage.py migrate
```

## (FastAPI)[https://fastapi.tiangolo.com/]

FastAPI is a modern, fast (high-performance), web framework for building APIs with Python based on standard Python type hints. It is easy to learn, help developers to code faster, it has great support for automatic documentation and it is on par with NodeJS and Go. It also provides support for async/await operations. It is used for complex and scalable applications.

To install FastAPI run the command:
```
pip install fastapi[all]
# or
pip install "uvicorn[standard]"
```

To run a FastAPI app run the command:
```
uvicorn main:app --reload
```
*Note*: Reload flag will make the server to reload each time we do modifications in our codebase.

A simple FastAPI app looks like this:
```
from enum import Enum
from fastapi import FastAPI
from pydantic import BaseModel # pydantic is used to perform data validation

app = FastAPI()


class Category(Enum):
    TOOLS = 'tools'
    CONSUMABLES = 'consumables'


class Item(BaseModel):
    name: str
    price: float
    count: int
    id: int
    category: Category


items = {
    0: Item(name="Hammer", price=9.99, count=20, id=0, category=Category.TOOLS),
    1: Item(name="Pliers", price=5.99, count=20, id=1, category=Category.TOOLS),
    2: Item(name="Nails", price=1.99, count=100, id=2, category=Category.CONSUMABLES),
}


# FastAPI handles JSON serialization and deserialization automatically.
# We can simply use built-in python and Pydantic types, in this case dict[int, Item].
@app.get("/")
def index() -> dict[str, dict[int, Item]]:
    return {"items": items}
```

More details (here)[https://github.com/ArjanCodes/2023-fastapi/tree/main]

To access Swagger docs mode type in the browser `localhost:port/docs` to access API documentation type `localhost:port/redoc`

(HTTP status code guide)[https://developer.mozilla.org/en-US/docs/Web/HTTP/Status]

Other useful FastAPI courses:
- (API integration Course)[https://www.youtube.com/watch?v=rkPIftzu1pQ]
- (FastAPI - A python framework)[https://www.youtube.com/watch?v=7t2alSnE2-I]

## (LangChain)[https://www.langchain.com/]

LangChain is an open source framework for building applications based on large language models (LLMs).
To be able to use LangChain, you will need to fetch the OpenAI key from the LLM service you want to use (Azure, OpenAI, Anthropic, etc.).


```
# To install the libraries and connect to LLMs

!pip install -qU \
 python-dotenv \
 langchain \
 langchain-community \
 openai \
 anthopic \
 langchain-openai \
 langchain-anthropic

# Load the API keys from the .env file
from dotenv import load_dotenv
load_dotenv()

# Connect to OpenAI and Anthropic
from langchain-anthropic import ChatAnthropic
llm_claude3 = ChatAnthropic(model='claude-3-opus-20240229')

from langchain-openai import ChatOpenAI
llm_gpt4 = ChatOpenAI(model="gpt-4o")

# Check if you can use the LLM
request_response = llm_gp4.invoke("What is Langchain?").content

print(request_response)

# Basic request using system and user message

system_prompt="""
You explain things to people like they are 5 years old
"""

user_prompt="""
What is LangChain?
"""

from langchain_core.messages import HumanMessage, SystemMessage
import textwrap

messages = [
   SystemMessage(content=system_prompt)
   HumanMessage(content=user_prompt)
]

response = llm_gpt4.invoke(messages)
answer = textwrap.fill(response.content, width=100)
print(answer)
```


### Chains, Prompts & Loaders
```
from langchain.prompts import PromptTemplate

# Prompt Template
prompt_template ="""
You are a helpful assistant that explains AI topics. Given the following input:
{topic}
Provide an explanation of the given topic.
"""

# Create the prompt from the prompt template
prompt = PromptTemplate(
   input_variables=["topic"]
   template=prompt_template,
)

# Assemble the chain using pipe operator "|" or LangChain Expression Language
chain = prompt | llm_gpt4

response = chain.invoke({"topic": "What is LangChain"}).content
print(response)
```

Another example of chaining:
```
# first install the required dependency
! pip install --upgrade --quiet youtube-transcript-api

from langchain_community.document_loaders import YoutubeLoader

loader = YoutubeLoader.from_youtube_url(
"enter a youtube url", add_video_info=False
)

# Load the video transcript as documents

docs = loader.load()

transcript = docs[0].page_content
print(transcript)

# Use the transcript in the chain
prompt_template = """
You are a helpful assistant that explains YT videos. Given the following video transcript:
{video_transcript}
Give a summary.
"""

# Create the prompt
prompt = PromptTemplate(
  input_variables=["video_transcript"],
  template=prompt_template,
)

chain = prompt | llm_gpt4

# You can feed the chain the docs without extracting the content as text

response = chain.invoke({"video_transcript":docs}).content
print(response)
```

Another example of chaining:
```
from langchain.chain.combine_documents import create_stuff_documents_chain

# create_stuff_documents_chain takes a list of docs and formats them into a prompt

prompt_template ="""
You are a helpful assistant that explains AI concepts. Given the following context:
{context}
Summarize what Llama 3 can do
"""

prompt = PromptTemplate(
  input_variables=["context"],
  template=prompt_template,
)

chain = create_stuff_documents_chain(llm_gpt4, prompt)

print(chain.invoke({"context": docs}))
```

### LangChain Expression Language (LCEL) & Runnables

LCEL simplifies building complex chains from basic components. We can chain multiple chains as well.

Runnables are units of work that can be invoked, batched, transformed and composed. The chains we build and the components of those chains are runnables. Runnable Objects: **RunnableSequence**, **RunnableLambda**, **RunnablePassthrough**, **RunnableParallel**

```
from langchain.prompts import PromptTemplate
from lanchain_core.output_parsers import StrOutputParser


summarize_prompt_template ="""
You are a helpful assistant that explains AI concepts:
{context}
Summarize the context
"""

summarize_prompt = PromptTemplate.from_template(summarize_prompt_template)

output_parser = StrOutputParser()

chain = summarize_prompt | llm_gpt4 | output_parser

response = chain.invoke({"context": "What is Langchain?"})
print(response)
print(type(chain)) # RunnableSequence
```

Using a RunnableLambda
```
from langchain_core.runnables import RunnableLambda

summarize_chain = summarize_prompt | llm_gpt4 | output_parser

length_lambda = RunnableLambda(lambda summary: f"Summary length: {len(summary)} characters")

lambda_chain = summarize_chain | length_lambda

lambda_chain.invoke({"context": "What is LangChain?"})

print(type(lambda_chain.steps[-1]))

# You can use function in chain without converting to RunnableLambda
# chain_with_function = summarize_chain | (lambda summary: f"Summary length: {len(summary)} characters")
# print(type(chain_with_function.steps[-1]))
```

Using a RunnablePassthrough as placeholder
```
from langchain_core.runnables import RunnablePassthrough

summarize_chain = summarize_prompt | llm_gpt4 | output_parser

# Create a RunnablePassthrough instance
passthrough = RunnablePassthrough()

placeholder_chain = summarize_chain | passthrough | length_lambda

print(placeholder_chain.invoke({"context": "What is LangChain?"}))

print(type(placeholder_chain.step[-1]))
print(type(placeholder_chain.step[-2]))
# You can use RunnablePassthrough.assign method for SQL chain
```

Using a RunnableParallel
```
from langchain_core.runnables import RunnableParallel

summarize_chain = summarize_prompt | llm_gpt4 | output_parser

# Create a RunnableParallel instance to handle summary and length in parallel
parallel_runnable = RunnableParallel(
  summary=lambda x: x,
  length=lambda x: len(x)
)

parallel_chain = summarize_chain | parallel_runnable

print(parallel_chain.invoke({"context": "What is LangChain?"}))
print(type(parallel_chain.steps[-1]))
```

### Splitters & Retrievers

A retriever is an interface that returns documents given a query. The backbone of a retriever is the vector store. The retriever doesn't store the documents itself. To load the data in the vector store you have to split the data in chunks.

```
# Install redis for vector store
!pip install --upgrade --quiet redis

from langchain_community.document_loaders import YoutubeLoader

loader = YoutubeLoader.from_youtube_url(
"enter a youtube url", add_video_info=False
)

# Load the video transcript as documents

docs = loader.load()

from langchain_text_splitters import RecursiveCharacterTextSplitter

text_splitter = RecursiveCharacterTextSplitter(
  chunk_size=100,
  chunk_overlap=20,
  length_function=len,
  is_separator_regex=False,
)

docs_split = text_splitter.split_documents(docs)

print(docs_split)

# Add Redis relevant data
# REDIS_URL=""
# REDIS_HOST=""
# REDIS_PASSWORDS=""
# REDIS_PORT=""

import redis

r = redis.Redis(
host=REDIS_HOST,
port=REDIS_PORT,
password=REDIS_PASSWORD)

print(r.ping())
print(r.flushdb())

# install embeddings
# !pip install --upgrade --quiet sentence-transformers

from langchain.embeddings import HuggingFaceEmbeddings
embeddings = HuggingFaceEmbeddings()

from langchain_community.vectorstores.redis import Redis

rds = Redis.from_documents(
  docs_split,
  embeddings,
  redis_url=REDIS_URL,
  index_name="youtube"
)

retriever = rds.as_retriever(search_type="similarity", search_kwargs={"k": 10})

print(retriever.invoke("data analysis"))
```

See more about vector databases (here)[https://www.youtube.com/watch?v=ySus5ZS0b94&pp=ygUPVmVjdG9yIGRhdGFiYXNl].

### RAG

RAG is technique for augmenting LLM knowledge with external data. A RAG can be build in 2 steps: index external data (using chunking data, embeddings, etc.), then retrieve and generate output.

```
from langchain.prompts import PromptTemplate
from lanchain_core.output_parsers import StrOutputParser


template ="""
Answer the question based only on the following context:
{context}
Question: {question}
"""

prompt = PromptTemplate.from_template(template)

output_parser = StrOutputParser()

chain = (
 {"context": (lambda x: x["question"]) | retriever,
  "question": (lambda x: x["question"])}
  | prompt
  | llm_gpt4
  | StrOutputParser()
)

anwser=chain.invoke({"question": "What can you do with LLama3"})
print(answer)
```

### Tools

Tools are interfaces that an agent, chain or LLM can use to interact with the world. Toolkits are collections of tools that are designed to be used together for specific tasks.

```
!pip install --upgrade --quiet youtube_search

from langchain_community.tools import YoutubeSearchTool

results = youtube_tool.run("Rabbitmetrics")
print(results)

# Bind the YouTube tool to the LLM
llm_with_tools = llm_gpt4.bind_tools([youtube_tool])

msg = llm_with_tools.invoke("Rabbitmetrics YT videos")

print(msg)

chain=llm_with_tools | (lambda x: x.tools_calls[0]["args"]["__arg1"]) | youtube_tool

chain.invoke("Find some Rabbitmetrics videos on LangChain")
```

### Agents

An agent is a program capable of reasoning and performing tasks by integrating LLMs with tools.

```
!pip install --upgrade --quiet langchainhub

from langchain import hub
from langchain.agents import AgentExecutor, create_tool_calling_agent

prompt = hub.pull("hwchase17/openai-tools-agent")
prompt.messages

tools=[youtube_tool]
agent = create_tool_calling_agent(llm_gpt4, tools, prompt)
agent_executor = AgentExecutor(agent=agent, tools=tools, verbose=True)

agent_executor.invoke(
{
   "input": "Find some LangChain YT videos"
}
)
```

Other videos (or Youtube channels) to watch:
- (Video #1)[https://www.youtube.com/watch?v=au2WVVGUvc8]
- (Video #2)[https://www.youtube.com/watch?v=RIWbalZ7sTo]
- (Video #3)[https://www.youtube.com/watch?v=2TJxpyO3ei4]
- (Video #4)[https://www.youtube.com/watch?v=dXxQ0LR-3Hg]
- (Video #5)[https://www.youtube.com/watch?v=x0AnCE9SE4A&t=4706s]
- (Video #6 - Create LLM from Scratch)[https://www.youtube.com/watch?v=UU1WVnMk4E8]
- (Video #7 - Embeddings and Vector Databases)[https://www.youtube.com/watch?v=ySus5ZS0b94]

## RAG Deep Dive

RAG components:
1. Indexing
2. Retrieval
3. Generation

Indexing is the numerical representation of the documents (that have a text representation). There are 2 aproaches:
- Bag of Words (statistical method)
- Embedding (Machine Learning method)

We need to split the documents because they have a limited context window (limited by no. of tokens) and those splitted documents are transformed in vectors by embedding the documents(vector/numerical representation of the documents) that capture a semantic meaning.

Retrieval is the component that takes a query, transforms it in a numerical represetation, then searches through the indexed documents (by semantic similarity) to see which document is more relevant to the given query.

*Analogy*: To better understand this imagine that you take a document, split it in some chunks, and then put those chunks in box (3D or embedding space) in different locations (given by the value of the vector representation of each chunk). When we want to send a query, we transform it in a vector representation and add it in the box as well. Then, a search is done (Local Neighborhood Search or K-Nearest Neighbor Algorithm for example) to see which document chunk is closer or more relevant to our query.

Generation is the component that retrives the documents that are relevant to the query, pack them up into the LLM context window, and produces a more precised response.

Chain is part of LCEL (expression language) that makes easy for devs to compose different Langchain components such as parsers, LLMs, prompts, etc.

An example is available (here)[https://github.com/langchain-ai/rag-from-scratch/blob/main/rag_from_scratch_1_to_4.ipynb]

Query translation is a technique that takes a query and translates it in such way that improves a RAG Retrieval. This should solve the problem where users provides an ambiguous query that will get them ambiguous matches (because semantic search on embeddings can't retrieve what the user really meant by that query) resulting in a hallucinated responses from LLMs. The approaches are: multi-query, RAG-Fusion, Step-back prompting, etc.

Multi-query splits a question into 2-3 different related questions with the help of LLM (so that we have different perspectives of the same question that may help RAG to retrieve relevant documents), stores them (as embedded) in the vector stores, then get a proper answer from the union of all those related questions.

RAG-Fusion is similar to multi-query approach. The difference is that it takes the generated questions and provides different results that are combined based of the ranking (top 3 documents for example). It uses the concept of Reciprocical Ranking Fusion.

Decomposition is a technique that takes a query (or problem), decompose it into subqueries (or subproblems), and then solve them sequentially. IR-CoT (Interleave retrieval with Chain of Thought) is another approach that interleaves Chain of Thought (CoT) generation and knowledge retrieval steps in order to guide the retrieval by CoT and vice-versa. This interleaving allows retrieving more relevant information for later reasoning steps, compared to standard retrieval solely using solely the question as the query.
Combining Decomposition and IR-CoT can result in dinamically retrieval that can help solving the subproblems.

Step-back prompting is a technique that uses few show prompting to produce more abstract step-back question. For example, you can have the question: "In what country Napoleon was born?", the step-back prompting will produce the following question: "What is the personal history of Napoleon?".

HyDE is a technique that takes the questions and map them into document space by generating a hypothetical document that will check for similarity with the existing documents from the embedding space.

An example is available (here)[https://github.com/langchain-ai/rag-from-scratch/blob/main/rag_from_scratch_5_to_9.ipynb]

Routing is the technique that takes a question then direct the question to the relevant data source (supposing that we have different kinds of databases). There are 2 ways of doing the routing: logically (works mostly with databases or datasources) or semantically (works mostly with prompts).

### Query Construction

It takes a natural language query and converts it into particular domain specific language (for example text-to-SQL, or text-to-JSON).

An example is available (here)[https://github.com/langchain-ai/rag-from-scratch/blob/main/rag_from_scratch_10_and_11.ipynb]

### Indexing Techniques(most of them are based on docs/chunk summaries)

1. Proposition Indexing
2. Multi-representation Indexing
3. RAPTOR
4. CoIBERT

An example is available (here)[https://github.com/langchain-ai/rag-from-scratch/blob/main/rag_from_scratch_12_to_14.ipynb]

### Active RAG

LLM decides when and what to retrieve based upon retrieval and/or generation. Active RAG can be implemented using State Machines.

An approach is CRAG (Corrective-RAG) which takes a question, retrieve some documents, grade them by relevance, then, if no document is relevant, transform the query and perform web search that will serve as the context window for the LLM, then generate the final answer. If there are relevant docs, then generate the response based on those relevant docs.

Adaptive RAG has 2 main ideas:
1. Query Analysis: Re-writing and Routing
2. Online Testing: Testing some parts from the RAG pipeline or RAG inference (retrieval for example). It is based on structured output.
(Command-R)[https://docs.cohere.com/v2/docs/command-r] from Cohere is a good model for this use case.

An example is available (here)[https://github.com/langchain-ai/rag-from-scratch/blob/main/rag_from_scratch_15_to_18.ipynb]

(Beginners Guide to LangChain)[https://www.freecodecamp.org/news/beginners-guide-to-langchain/]

## AI Agentic Design Patterns

There are currently 4 AI Design Patterns:
- Reflection Pattern
- Tool Use Pattern
- Planning Pattern
- Multi-Agent Pattern

The **Reflection Pattern** empowers agents to introspect and evaluate their actions or decisions. This pattern is about iterative improvement, where agents not only perform tasks but also analyze outcomes to refine their approach. A use case would be a trading bot.
**Key Features**:
- Self-Evaluation: Agents assess their performance using metrics or goals.
- Feedback Loops: They adjust their strategies based on the evaluation.
- Scenario: A recommendation agent reflects on user feedback to improve its suggestions.
**Design Flow**:
1. The Agent performs an action.
2. Collects results or outcomes.
3. Reflects on the outcomes against predefined metrics or goals.
4. Refines strategy or logic based on reflection.

The **Tool Use Pattern** emphasizes equipping agents with external tools or APIs to extend their capabilities. This pattern allows agents to delegate specialized tasks rather than performing everything internally. A use case would be a GenAI support that needs access to external data (database) or external API (JIRA).
**Key Features**:
- Specialized Functionality: Agents call tools for tasks like data retrieval, transformation, or complex computations.
- Interoperability: Seamlessly integrates tools into workflows.
- Scenario: An AI agent uses an external API to fetch stock prices and another tool for sentiment analysis.
**Design Flow**:
1. The Agent identifies a task that requires a tool.
2. Calls the appropriate tool with context or parameters.
3. Receives processed results from the tool.
4. Integrates the results into its workflow.

The **Planning Pattern** is about agents formulating and executing multi-step plans to achieve complex objectives. It enables systems to dynamically adapt their workflows based on goals and constraints. A use case would be automated banking loan approvals.
**Key Features**:
- Dynamic Goal Alignment: Plans are generated in real time based on inputs or changes.
- Sequential Execution: Agents execute plans step-by-step, ensuring dependencies are managed.
- Scenario: A logistics agent plans delivery routes by optimizing for distance, fuel cost, and traffic conditions.
**Design Flow**:
1. Define goals or objectives.
2. Analyze available resources and constraints.
3. Generate a sequence of actions to achieve the goals.
4. Execute the plan while monitoring outcomes.

The **Multi-Agent Pattern** focuses on orchestrating multiple agents to work collaboratively on complex tasks. This pattern leverages agent specialization and parallelism. A use case would be end-to-end task performing (for example end-to-end trading system).
**Key Features**:
- Division of Labor: Agents handle different aspects of a task.
- Coordination: A central orchestrator ensures agents align their actions.
- Scenario: A marketing workflow involves one agent for content generation, another for scheduling, and a third for analytics.
**Design Flow**:
1. Assign tasks to specialized agents.
2. Share context or intermediate results between agents.
3. Orchestrate their actions to achieve the overall objective.

**Resources**:
https://medium.com/@turungkadircan/agentic-design-patterns-how-to-implement-19c881b54dd7
https://medium.com/@bijit211987/agentic-design-patterns-cbd0aae2962f
https://dzone.com/articles/agentic-design-patterns
https://github.com/pdichone/agentic-design-patterns/tree/main

## Troubleshooting

To add some issues that I/you ran into and the best solution to be applied so that you will never have a headache finding a solution on Google :)

## Algorithms and Data Structures

To add all Algorithms and Data Structures implemented in Python

## Interview Questions (for Junior, Middle and Senior Developers)

To add interview questions and answer for all levels (Junior, Middle and Senior Devs).
