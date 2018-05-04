# Understanding Linear Regression

Maximum learning is achived by pratical expirementation. Theory helps get a grasp, but nothing is more satisfying as coding the theory in your favorite language and see it work. That magician feeling. In this blog I will go through a simple concept of Regression and to be specific disuss about Simple linear regression. 

There are several packages in every possible programming languages and productive appplications which abstact the concept and get straight to the result. These packages and plugins do such a good job sometimes it is hard to get a full grasp of the algorithms that does the magic under the hood.

This blog is an attempt to uncover the working of the linear regression. We will conider the simplest dumbest data and produce a simple linear regression model and in the process decode its inner working.

We will consider the kaggle data set found here. 
https://www.kaggle.com/andonians/random-linear-regression

Using this dataset we will now implement the simple linear regression algorithm from scratch in Python.

## The Plan

Lets find a new relation, I mean a linear realtionship between our beloved X and Y. We want to find a straight line relationship between the X (independent variable) and Y (depenent variable). This is called simple linear regression where we are tyring to find what linear combination of X (input) will produce Y (output) 

## Lieutenant Commander Data

No not that Data. Here is our data from kaggle.


Our aim is to find a straight line that connects all the data point.

Straight line you say?

Well intuitly you can see that it is mission impossbile to find a straight line that goes throught all the points. We will find a approximate line that is respresentative of all the points hugging the line.

Lets begin with the equation of a straight line.
