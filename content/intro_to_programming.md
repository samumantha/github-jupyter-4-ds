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
  ::::{tabs}
  :::{group-tab} Python
  ```python
  price = 9.99
  ```
  :::

  :::{group-tab} R
  ```R
  price <- 9.99
  ```
  :::

  :::{group-tab} Julia
  ```julia
  price = 9.99
  ```
  :::
::::

- **String**: Text or characters
  ::::{tabs}
  :::{group-tab} Python
  ```python
  greeting = "Hello World"
  ```
  :::

  :::{group-tab} R
  ```R
  greeting <- "Hello World"
  ```
  :::

  :::{group-tab} Julia
  ```julia
  greeting = "Hello World"
  ```
  :::
::::

- **Boolean**: True or False values
  ::::{tabs}
  :::{group-tab} Python
  ```python
  is_student = True
  ```
  :::

  :::{group-tab} R
  ```R
  is_student <- TRUE
  ```
  :::

  :::{group-tab} Julia
  ```julia
  is_student = true
  ```
  :::
::::


## Operators

Operators are used to perform operations on variables and values.

Common types of operators:

- **Arithmetic Operators**: `+`, `-`, `*`, `/`, `%`
  ::::{tabs}
  :::{group-tab} Python
  ```python
  sum = 5 + 3
  ```
  :::

  :::{group-tab} R
  ```R
  sum <- 5 + 3
  ```
  :::

  :::{group-tab} Julia
  ```julia
  sum = 5 + 3
  ```
  :::
::::

- **Assignment Operators**: `=`, `+=`, `-=`
  ::::{tabs}
  :::{group-tab} Python
  ```python
  x = 10
  x += 5
  ```
  :::

  :::{group-tab} R
  ```R
  x <- 10
  x <- x + 5
  ```
  :::

  :::{group-tab} Julia
  ```julia
  x = 10
  x += 5
  ```
  :::
::::

- **Comparison Operators**: `==`, `!=`, `<`, `>`
  ::::{tabs}
  :::{group-tab} Python
  ```python
  print(10 > 5)
  ```
  :::

  :::{group-tab} R
  ```R
  print(10 > 5)
  ```
  :::

  :::{group-tab} Julia
  ```julia
  println(10 > 5)
  ```
  :::
::::

- **Logical Operators**: `and`, `or`, `not`
  ::::{tabs}
  :::{group-tab} Python
  ```python
  print(10 > 5 and 5 < 10)
  ```
  :::

  :::{group-tab} R
  ```R
  print(10 > 5 & 5 < 10)
  ```
  :::

  :::{group-tab} Julia
  ```julia
  println(10 > 5 && 5 < 10)
  ```
  :::
::::


## Conditional Statements

Conditional statements perform different actions based on conditions. The `if` statement is the most common:

::::{tabs}
  :::{group-tab} Python
  ```python
  age = 18

  if age >= 18:
      print("You are an adult.")
  else:
      print("You are not an adult.")
  ```
  :::

  :::{group-tab} R
  ```R
  age <- 18

  if (age >= 18) {
      print("You are an adult.")
  } else {
      print("You are not an adult.")
  }
  ```
  :::

  :::{group-tab} Julia
  ```julia
  age = 18

  if age >= 18
      println("You are an adult.")
  else
      println("You are not an adult.")
  end
  ```
  :::
::::


## Arrays

Arrays (or lists in Python) store multiple values in a single variable:

::::{tabs}
  :::{group-tab} Python
  ```python
  colors = ["red", "green", "blue"]

  print(colors[0])  # Output: red
  ```
  :::

  :::{group-tab} R
  ```R
  colors <- c("red", "green", "blue")

  print(colors[1])  # R is 1-indexed
  ```
  :::

  :::{group-tab} Julia
  ```julia
  colors = ["red", "green", "blue"]

  println(colors[1])  # Julia is 1-indexed
  ```
  :::
::::

Arrays are useful for:
- Storing multiple related values
- Iterating through values
- Sorting and modifying collections


## Loops

Loops are used to repeat actions multiple times.

**For loop:**
::::{tabs}
  :::{group-tab} Python
  ```python
  colors = ["red", "green", "blue"]

  for color in colors:
      print(color)
  ```
  :::

  :::{group-tab} R
  ```R
  colors <- c("red", "green", "blue")

  for (color in colors) {
      print(color)
  }
  ```
  :::

  :::{group-tab} Julia
  ```julia
  colors = ["red", "green", "blue"]

  for color in colors
      println(color)
  end
  ```
  :::
::::

**While loop:**
::::{tabs}
  :::{group-tab} Python
  ```python
  count = 0

  while count < 3:
      print(count)
      count += 1
  ```
  :::

  :::{group-tab} R
  ```R
  count <- 0

  while (count < 3) {
      print(count)
      count <- count + 1
  }
  ```
  :::

  :::{group-tab} Julia
  ```julia
  count = 0

  while count < 3
      println(count)
      count += 1
  end
  ```
  :::
::::

Loops help in iterating over collections and automating repetitive tasks.


## Functions

Functions are reusable blocks of code that perform specific tasks:

::::{tabs}
  :::{group-tab} Python
  ```python
  def greet(name):
      print("Hello, " + name + "!")

  greet("Alice")
  ```
  :::

  :::{group-tab} R
  ```R
  greet <- function(name) {
      print(paste("Hello,", name, "!"))
  }

  greet("Alice")
  ```
  :::

  :::{group-tab} Julia
  ```julia
  function greet(name)
      println("Hello, " * name * "!")
  end

  greet("Alice")
  ```
  :::
::::

Functions:
- Improve readability
- Promote code reuse
- Simplify debugging


## Learn More

Explore these resources for further learning:
- [W3Schools Programming Tutorials](https://www.w3schools.com/programming/)

**Python:**
- [W3Schools Python Tutorial](https://www.w3schools.com/python/)
- [Python Documentation](https://docs.python.org/3/)
- [Learn Python](https://www.learnpython.org/)

**R:**
- [R for Data Science (Book)](https://r4ds.hadley.nz/)
- [RStudio Cheatsheets](https://posit.co/resources/cheatsheets/)
- [Swirl - Learn R in R](https://swirlstats.com/)

**Julia:**
- [Julia Documentation](https://docs.julialang.org/)
- [JuliaAcademy Courses](https://juliaacademy.com/)
- [Learn Julia in Y Minutes](https://learnxinyminutes.com/docs/julia/)


:::{keypoints}
- Programming means instructing computers to perform tasks.
- Variables store data, and each variable has a data type.
- Conditional statements allow programs to make decisions.
- Arrays and lists store collections of data.
- Loops repeat actions efficiently.
- Functions encapsulate reusable code.
- Operators manipulate data.
:::

