# 411_LinearRegression
Author: Alex Tkaczyk 
Course: CS 411 
Instructor: Bing Liu 
Project: Linear Regression Model
Program input being 2 files. First file being a training dataset, which is parsed using parseData() and the data is stored in a list of lists. Using the parsed training data, (called “parsedData”) the program then computers the linear regression function, using a loss function and batch gradient descent. Once the equation is found, the points and function are all plotted on a graph.
The second file being a test dataset, which is parsed through using parseData() and gets stored in a list of list (called “parsedTestData”. The program then iterates through parsedTestData and computes the predicted y-value, given the x-vals. Then all the new predicted points are plotted.
