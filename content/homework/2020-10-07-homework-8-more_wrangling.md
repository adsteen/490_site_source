---
title: "Homework 8: More Data Wrangling"
author: ~
date: '2020-10-07'
slug: homework-8
categories: [homework]
tags: [week08]
draft: no
---

Homework 8 is due Wednesday, October 14.

<!--more-->

This week we are learning about the difference between the tidyverse approach to handling data and the base R approach.

# Base R

## Lists, data frames, and vectors

1. Create a list using the `list()` function with at least 3 named elements. 
    * Access the first element by name
    * Access the second element using the `[[` syntax
    * Access the third element *as a list* using the `[` syntax
2. Using the `mtcars` dataframe that is built into base R, access the `mpg` column in two different ways.
3. Use base R reate a new column in `mtcars` for "displacement per cylinder", that contains the engine displacement (`disp`) divided by the number of cylinders (`cyl`)
3. Create a single-column data frame (tibble) using the tidyverse `mutate()` function. What is the difference between this and the vector?

# Exploratory data analysis

1. Take either your own data, the data in the `nycflights` dataset, or the `babynames` dataset (from the **babynames** package), and do some exploratory data analysis. Explain what you're doing, and what you figured out. Be sure to have clearly-written text and well-formed code.

