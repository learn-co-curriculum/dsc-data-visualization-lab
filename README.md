
# Data Visualization - Lab

## Introduction
This lab will give you some structured practice performing data visualization!

## Objectives

You will be able to:
* Use Matplotlib to create a scatter plot
* Use Matplotlb to create a bar plot
* Use Matplotlib to create a histogram


## Bar plots

Make a vertical bar graph using `plt.bar()` for the following set of data. _Hint_: create two lists.

>Jim's Video Library contains 40 crime/mystery, 30 science fiction, 10 drama, 50 comedy, 25 action and 5 documentary movies.

Make sure your image has the following properties:

* Make sure it has a size of 8 x 6 inches
* Set x-axis (genres) and y-axis (number of movies)
* Plot and label the bar graph
* Provide a suitable title
* Label the x and y-axis



```python
# import the required libraries
import matplotlib.pyplot as plt
%matplotlib inline

genres = None
number_of_movies = None

# Create a new figure object

# Plot vertical bars of fixed width by passing x and y values to .bar() function 

# Give a title to the bar graph

# Output the final plot

```

## Scatter Plots

The table shows the data collected by a Consumer Products Group on the relationship between the weight of a car and its average gas mileage.

      Car Type  Weight	miles per gallon
        A	    2750	   29
        B	    3125	   23
        C	    2100	   33
        D	    4082	   18
        E	    2690	   20
        F	    3640	   21
        G	    4380	   14
        H	    2241	   25
        I	    2895	   31
        J	    3659	   17
        
* Use a scatter plot to show the relationship between mpg and weight of a car
* Set an appropriate figure size, labels for axes and the plot
* Give a title to the plot


```python
weight = [2750, 3125, 2100, 4082, 2690, 3640, 4380, 2241, 2895, 3659]
mpg = [29, 23, 33, 28, 20, 21, 14, 25, 31, 17]

# Set the figure size in inches

# Plot with scatter()

# Set x and y axes labels and a title

```

## Exercise 3

Joe is the branch manager at a bank. Recently, Joe been receiving customer feedback saying that the waiting times for a client to be served by a customer service representative are too long. Joe decides to observe and write down the time spent by each customer on waiting. Here are his findings from observing and writing down the wait times (in seconds), spent by 20 customers:

43.1, 35.6, 37.5, 36.5, 45.3, 43.4, 40.3, 50.2, 47.3, 31.2, 42.2, 45.5, 30.3, 31.4, 35.6, 45.2, 54.1, 45.6, 36.5, 43.1

* Build a histogram of these values using the `hist()` function
* Plot, label and give a title as above. Use  `bins=7`
* Briefly describe the output in terms of waiting times


```python
Customers = [43.1, 35.6, 37.5, 36.5, 45.3, 43.4, 
     40.3, 50.2, 47.3, 31.2, 42.2, 45.5, 
     30.3, 31.4, 35.6, 45.2, 54.1, 45.6, 
     36.5, 43.1]

# Plot the distogram with hist() function

# Label, give title and show the plot

```

## Summary

In this lab, you got some good practice working with creating and interpreting plots in Python using Matplotlib.
