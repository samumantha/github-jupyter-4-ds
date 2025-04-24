# Basics of Programming

:::{objectives}
- Understand what programming is
- Learn about variables and data types
- Understand conditional statements (`if` statements)
- Explore arrays and collections
- Understand loops and iteration
- Learn about functions
- Familiarize with basic operators
:::


## What is Programming?

Programming is the process of writing instructions for a computer to execute. These instructions are written in programming languages, which computers interpret and perform specific tasks. Programming languages allow us to create software, applications, and websites.

Programming involves tasks such as:
- Creating algorithms (step-by-step instructions)
- Managing data
- Automating tasks


## Variables

Variables are containers used to store data values. They have names, and values can change during program execution.

**Example:**

::::{tabs}
  :::{group-tab} Python
  ```python
  name = "Alice"
  age = 30
  print(name)
  print(age)
  ```
  :::

  :::{group-tab} R
  ```R
  name <- "Alice"
  age <- 30
  print(name)
  print(age)
  ```
  :::

  :::{group-tab} Julia
  ```julia
  name = "Alice"
  age = 30
  println(name)
  println(age)
  ```
  :::
::::

Variable names:
- Should be descriptive
- Can include letters, numbers, and underscores (`_`)
- Cannot begin with a number


## Data Types

Data types define the type of data stored in variables. Common data types include:

- **Integer**: Whole numbers
  ::::{tabs}
  :::{group-tab} Python
  ```python
  age = 30
  ```
  :::

  :::{group-tab} R
  ```R
  age <- 30
  ```
  :::

  :::{group-tab} Julia
  ```julia
  age = 30
  ```
  :::
::::

- **Float**: Numbers with decimal points
  ```python
  price = 9.99
  ```

- **String**: Text or characters
  ```python
  greeting = "Hello World"
  ```

- **Boolean**: True or False values
  ```python
  is_student = True
  ```


## Operators

Operators are used to perform operations on variables and values.

Common types of operators:

- **Arithmetic Operators**: `+`, `-`, `*`, `/`, `%`
  ```python
  sum = 5 + 3
  ```

- **Assignment Operators**: `=`, `+=`, `-=`
  ```python
  x = 10
  x += 5
  ```

- **Comparison Operators**: `==`, `!=`, `<`, `>`
  ```python
  print(10 > 5)
  ```

- **Logical Operators**: `and`, `or`, `not`
  ```python
  print(10 > 5 and 5 < 10)
  ```


## Conditional Statements

Conditional statements perform different actions based on conditions. The `if` statement is the most common:

```python
age = 18

if age >= 18:
    print("You are an adult.")
else:
    print("You are not an adult.")
```


## Arrays

Arrays (or lists in Python) store multiple values in a single variable:

```python
colors = ["red", "green", "blue"]

print(colors[0])  # Output: red
```

Arrays are useful for:
- Storing multiple related values
- Iterating through values
- Sorting and modifying collections


## Loops

Loops are used to repeat actions multiple times.

**For loop:**
```python
colors = ["red", "green", "blue"]

for color in colors:
    print(color)
```

**While loop:**
```python
count = 0

while count < 3:
    print(count)
    count += 1
```

Loops help in iterating over collections and automating repetitive tasks.


## Functions

Functions are reusable blocks of code that perform specific tasks:

```python
def greet(name):
    print("Hello, " + name + "!")

greet("Alice")
```

Functions:
- Improve readability
- Promote code reuse
- Simplify debugging


## Learn More

Explore these resources for further learning:
- [W3Schools Programming Tutorials](https://www.w3schools.com/programming/)
- [Python Documentation](https://docs.python.org/3/)
- [Learn Python](https://www.learnpython.org/)


:::{keypoints}
- Programming means instructing computers to perform tasks.
- Variables store data, and each variable has a data type.
- Conditional statements allow programs to make decisions.
- Arrays and lists store collections of data.
- Loops repeat actions efficiently.
- Functions encapsulate reusable code.
- Operators manipulate data.
::: 

