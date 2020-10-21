---
title: "Homework 10"
author: ~
date: '2020-10-21'
slug: homework-10
categories: [homework]
tags: [week10]
draft: no
---

Homework 10 is due Wednesday, October 28.

<!--more-->

# Linear models

* Using the **diamonds** dataset, create a linear model of `price` as a function of the weight of the diamond (`carat`). According to that model, what price would you expect for a 1-carat diamond?
* Now create a linear model of `price` as a function of `carat` and `color`. 
    - What difference does it make if you convert `color` to a character vector before you make the model? Note that this is probably what you want to do in general, unless you really know what you're doing.
* Make some plots of the raw data, and of the model fits, to make an argument as to which model is more useful.
    - Bonus: Should the data have been pre-processed before making these models?

# Objects and methods

* Write a function that returns some kind of structured result, which you define as a new S3 class. Your class doesn't need to be anything fancy, but it should be different from existing classes.
* Write `print` and `summarise` methods for this class. These methods don't need to be particularly useful, but they should be different from the default methods.
