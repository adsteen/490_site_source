---
title: "Homework 9 options"
author: ~
date: '2020-10-14'
slug: homework-9
categories: [homework]
tags: [week09]
draft: no
---

Homework 9 is due Wednesday, October 21.

<!--more-->

# Option 1: final project prospectus

See the description of the final project prospectus assignment in the Final Project folder. 

# Option 2: Functions and programming

1. Following *R for Data Science* exercise 19.2.1.4, write a function to calculate the variance of a numeric vector.  Be sure that the function auto-prints the result if the result is not assigned to a variable.
2. Write `both_na()`, a function that takes two vectors of the same length and returns the number of positions that have an NA in both vectors.
3. Write a function to create a specific kind of plot, with useful labels, etc., that can take a data frame as an argument. This is useful when you want to make multiple, similar plots from different data.
4. Write a function that takes one argument and does the following:
    * if the argument is a numeric vector, multiplies every number in the vector by 2
    * if the argument is a character vector, sorts the vector into alphabetical order
    * if the argument is anything else, issues an informative warning and returns the argument unchanged
5. Write a function that tries to calculate the mean of a vector using `mean()`. If that is successful, it returns the mean of the vector. If `mean()` throws an error, it issues an informative message and returns the input intact.
6. Use `system.time()` (or, if you want to be more advanced about it, the **bench** or **microbenchmark** packages) to compare how long it takes to add two, 1-million-element random vectors and store the result in a third vector:
        a. Using the vectorized `sum()` operation
        b. Using a for loop with a pre-allocated vector to store the results
        c. Using a for loop without pre-allocating a vector to store the results