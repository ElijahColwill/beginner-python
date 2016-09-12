# Python 101

#### Part 1: _Variables_
What is a variable? Techtarget.com says:
> In programming, a variable is a value that can change, depending on conditions or on information passed to the program.

In order to utilize variables, you need to first assign it, then use it. To assign a variable, first
you need to set the variable name. Then have an equal sign, followed by the value you want the variable to be.

###### Note: Python automatically formats variables into a type, like integers or strings. You don't need to do an formatting on your part.

Here's an example:
```
a = "Hello, World!"
var1 = 1
var2 = 10
```
The first variable was a string, and the last two are integers. The main types of variables are:
* Boolean
  * True or False
* Integer
  * Whole numbers _ONLY_.
* String
  * Text
* Floating Point
  * A number with decimals, like -0.05 or 12.618
* Array
  * A list, or collection of Integers, Floating Points, or Strings.

To use a variable, simply call it with the same name you assigned it as.
Two examples are:
Printing variables:

`print a`

Doing math functions with variables:

`var3 = var1 % 4`

`var4 = var1 * var2 - var3`

#### Part 2: _Conditions_

##### What are conditions?

Conditions are a requirement that the program or a variable must pass before executing a specific portion of code. A conditions evaluates to True or False (written as `True` and `False` in Python), using a Boolean variable. They also use expressions.

##### What are expressions?

Expressions include the following:
* Boolean expressions: Evaluate to True or False
* Integer expressions: whole numbers
* Floating-point expressions: Real numbers, including decimals.
* String expressions: Evaluate to character strings.

> Expressions in programming is a combination of symbols that represent a value. An expression could be _x+6_ or the string _"Hello, World!"_.

##### Operators

These are some operators in Python used for conditions:

Boolean operators: "And" and "Or" operators allow you to build more complex boolean expressions.

```
if a == 1 and b == 2 or a == 2 and b == 1:
  return True
```

The "is" operator checks to see if the instances themselves are equal, not the values of the instances.

```
a = "hi"
b = "hi"

print a == b # True
print a is b # False

```

And finally, the "not" operator switches the return from True to False, or vise versa.

##### Branches

In python, the basic type of branch is the if or if-else statement. The if statement is what your program uses to decide whether or not to execute a piece of code. You can use an `if` statement, `elif` statement, which means else if, or `else:` statement. Here's what the syntax would look like:

```
a = 2

def if_a(a):
  if a == 1:
    return "Yes!"
  elif a == 2:
    return "Maybe..."
  else:
    return "No."
```

You can also have if statements within if statements, like this:

```
a = 2
b = 1

def if_a_and_b(a):
  if a == 1:
    if b == 1:
      return "Yes!"
  elif a == 2
    if b == 1:
      return "Yes!"
  else: return "No."
```

#### Part 3: _Functions_

Functions are the bits of code that you use to store lines of code and call them. You can assign variables or arguments to a function by putting them into parenthesis.
You can do math, set variables, return values, and print statements with functions. You can also have if-then statements within functions.
The syntax looks much like what you saw before, like this:
```
def function_1(a, b):
  c = a + b
  if a == b:
    return "Nope"
  else: return c

```

To call a function:

```
function_1(2, 3)
```

You can also call a function with different variable names:

```
x = 2
y = 3

function_1(x, y)
```

#### Want to learn more? Go to [learnpythonthehardway.org/book](learnpythonthehardway.org/book)
