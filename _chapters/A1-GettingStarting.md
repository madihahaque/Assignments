---
title: 'A1-gettingstarting'
permalink: '/chapters/A1-GettingStarting'
previouschapter:
  url: 
  title: ''
nextchapter:
  url: 
  title: ''
redirect_from:
  - '/chapters/a1-gettingstarting'
---

# COGS 18 - Assignment 1: Getting Started

This assignment covers Variables, Operators & Conditionals.

This assignment is out of 6 points, worth 6% of your grade. 

## How to complete assignments

Whenever you see:

YOUR CODE HERE <br>
raise NotImplementedError()

You need to replace this section with some code that answers the questions and meets the specified criteria. Make sure you remove the 'raise' line when you do this (or your notebook will raise an error, regardless of any other code, and thus fail the grading tests).

Any cell with 'assert' statements in it is a test cell. You should not try to change or delete these cells. Note that there might be more than one assert that tests a particular question. 

If a test does fail, reading the error that is printed out should let you know which test failed, which may be useful for fixing it.

## Tips & Tricks

### Printing Variables

A reminder that you can (and should) print and check variables as you go.

This allows you to check what values they hold, and fix things if anything unexpected happens



{:.input_area}
```python
# Define a variable
math_result = 2 * 4

# Print out the value(s) of a variable.
print(math_result)
```


### Restarting the Kernel

TODO: Add note about restarting the kernel.

## Example Question

Define a variable called `my_int` that stores the value 17. 



{:.input_area}
```python
# YOUR CODE HERE
my_int = 17
```




{:.input_area}
```python
assert  my_int                     # This tests that a variable exists
assert  isinstance(my_int, int)    # This tests that a variable is of a particular type
assert  my_int == 17               # This tests that a variable has a specified value
```


## SETUP

Run the following cell before you start working on the assignment. 

TODO: Fill in quick description of what / what. 



{:.input_area}
```python
import os
if not os.path.exists('A1Code'):
    os.mkdir('A1Code')
```


### Part I - Defining Variables

Words, words, words.

#### Q1 - Creating some variables

Words, words, words.



{:.input_area}
```python
# Create the variables

# YOUR CODE HERE
raise NotImplementedError()
```




{:.input_area}
```python
# Check that variable `number` is an int, and has the correct value
assert isinstance(number, int)
assert number == 17

# Check that variable `decimal` is a float, and has the correct value
assert isinstance(decimal, float)
assert decimal == 12.5

# Check that variable `words` is a string, and has the correct value
assert isinstance(word, str)
assert word == "cogs18"
```


#### Q2 - stuff



{:.input_area}
```python
# TODO: Fill in

# YOUR CODE HERE
raise NotImplementedError()
```




{:.input_area}
```python
assert not done
```


### Part II - Operations

#### Q3 - Python as a Calculater



{:.input_area}
```python
#
int_1 = 47
int_2 = 12

float_1 = 22.1
float_2 = 19.0
```




{:.input_area}
```python
# YOUR CODE HERE
raise NotImplementedError()
```




{:.input_area}
```python
assert ans_1 == 1
```




{:.input_area}
```python
assert ans_2 == 1
```


#### Q4 - String Manipulations



{:.input_area}
```python
str_1 = "Python"
str_2 = "is"
str_3 = "fun!"
```




{:.input_area}
```python
# YOUR CODE HERE
raise NotImplementedError()
```




{:.input_area}
```python
assert output == str_1 + ' ' + str_2 + ' ' + str_3
```


#### Q5 - Boolean Comparisons



{:.input_area}
```python
bool_1 = True
bool_2 = False

int_3 = 12
int_4 = 54
```


### Part III - Conditionals

#### Q5 - stuff

#### Q6 - stuff



{:.input_area}
```python
%%writefile A1Code/q6_code.py
# ^ You can ignore this line - it is used to help check your code

# YOUR CODE HERE
raise NotImplementedError()
```




{:.input_area}
```python
# Initialize `thing`, to None
thing = None

# Set subj_age to old 
subj_age = 'old'

# Check that code 
%run -i ./A1Code/q6_code.py
assert thing
assert isinstance(thing, bool)

# Change subj_age and make sure the conditional still works
subj_age = 'young'
%run -i ./A1Code/q6_code.py

assert not thing
assert isinstance(thing, bool)
```


### Part IV - Putting it all together

#### Q7 - stuff

#### Q8 - stuff
