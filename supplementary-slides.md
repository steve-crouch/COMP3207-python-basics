---
layout: slides
title: COMP3207 - Introduction to Python
subtitle: Why Python?
---

## Live coding status checker

- Gives me an idea of how much time you need!
- When we start a task, enter your name into
     + **http://bit.ly/2dx48W6**
- When you've finished the task, just remove it

## Download some materials

- Use a browser to go the following URL and download the materials to your machine:
**http://bit.ly/2eia34u**
- Copy the file to your home directory
     + Mac OS X, Linux: e.g. /home/user
     + Windows: e.g. C:\\Users\\user

## Extract the materials

- Mac OS X or Linux: type in the following in a shell prompt:
     + **cd /home/user** (your home directory)
     + **unzip COMP3207-materials.zip**
     + **cd code**
- Windows: right click on the zip file, 'Extract All...', enter your home directory, then run a command prompt and type:
     + **cd C:\\Users\\username** (your home directory)
     + **cd code**

## What we'll cover

- Starting the interpreter
- Variables
- Lists
- Loops
- Processing data files
- Making choices
- Creating functions

## Starting the Python Interpreter

- The interpreter provides an interactive environment to play with the language
- Mac/Linux: Open a terminal window and type **python**
- Windows: Open a command prompt and type **python**
- At the prompt type **'hello world!'**
  ![](img/hello.png)

## Control Flow: Repeating actions with loops

-  What a loop does?
-  Writing loops to repeat simple calculations
      + Indexing/ Counting starts from **0**
-  Track changes to a loop variable as the loop runs
-  Track changes to other variables as they are updated by a `for` loop      

## Why indentation?

-  Studies show that's what people actually pay attention to
       + Every textbook on C or Java has examples where indentation and bracing don't match
-  Doesn't matter how much indentation you use, but the whole block must be consistent     
-  Python Style Guide (PEP 8) recommends 4 spaces 
-  And no tab characters
      
## Lists in Python

-  Lists as arrays
-  Indexing  
     + Indexing some single value or even a whole set of values from a given list.
     + Indexing for retrieving single elements works as usual in python and indexing by negative numbers starts counting from the end.
-  Slicing
      + Subset of a list, called a **Slice**, by specifying two indices. The return value is a new list containing all the elements of the list, in order, starting with the first slice index, up to but not including the second slice index.
      + **Difference between upper and lower bound is the number of values in the slice.**
      
## Indexing and Slicing a List Example

![](img/index_list_odd.png)

## Indexing and Slicing a List Example

![](img/index_list_odd2.png)

## Indexing and Slicing a List Example

![](img/slice_list_odd.png)

## Indexing and Slicing a List Example

![](img/slice_list_string.png)    
              
   
## Using Python libraries

-  This introduction to Python is built around an end to end scientific example: data analysis
-  What is a library (module) and its usage
-  Reading data from a file
         
## NumPy Arrays

-  NumPy arrays and operations on arrays of data
   
   ![](img/numpy_array_dims.png)

## NumPy arrays: Indexing and Slicing

-  Ways of selecting individual values and subsets of data
-  One-dimensional arrays are simple; on the surface they act similarly to Python lists.
 
## Indexing in a NumPy 2D array 

- The indices are (row, column) instead of (column, row).
- Example Patient inflammation data who were given treatment for arthritis:
     + **Rows:** Hold information for a single patient
     + **Columns:**  Represent successive days

## Cont..

   ![](img/indexing2darray.png) 
   
## Data visualisation using libraries

*The purpose of computing is insight, not numbers, Richard Hamming.*

-  Best way to develop insight is often to visualise data.
-  Plotting data using `matplotlib` library

## Control Flow: Making choices

-  Write conditional statements including `if`, `elif` and `else` 
-  A few things to note about the syntax:
      + Each if/ else statement must close with a colon (:)
      + Code to be executed as part of any *if/else* statement must be indented by four spaces.
      + Although not explicitly required, every *if* statement must also include an *else* statement - it just makes for a better program.
-  Evaluate expressions containing `and` and `or`
  
## Creating Functions

-  Defining a function, the parameters that it takes, return value
-  Test and debug a function
-  Scope of variables
-  Set default values for function parameters
-  Divide programs into small, single-purpose functions

## Command-line Programs

-  Using values of command-line arguments in a program
-  Handling flags and files separately in a command-line program
-  Reading data from standard input in a program 

## Wrap-up Challenge: Connecting the dots

**Write a python script (function) for Fahrenheit to Celsius temperature conversion and stores the output in a file.**

- Hint (Tools to be used):
     + Unix pipes and filters
     + Python functions
     + Command-line programs
     + Using Fahr_to_kelvin() and Kelvin_to_celsius() functions


##  Thank You!
