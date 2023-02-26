# datafun-07-ml-predictive

# Christine Martinez Module 7 Project

Task 1
Read and work through Chapter 10 - Object-Oriented Programming - and understand the examples. 

10.1 Introduction
10.2 Custom Class Account
10.3 Controlling Access to Attributes
10.4 Properties for Data Access
10.5 Simulating “Private” Attributes
10.6 Case Study: Card Shuffling and Dealing Simulation
10.7 Inheritance: Base Classes and Subclasses
10.8 Building an Inheritance Hierarchy; Introducing Polymorphism
10.9 Duck Typing and Polymorphism
10.10 Operator Overloading
10.11 Exception Class Hierarchy and Custom Exceptions
10.12 Named Tuples
10.13 A Brief Intro to Python 3.7’s New Data Classes
10.14 Unit Testing with Docstrings and doctest
10.15 Namespaces and Scopes
10.16 ★ Intro to Data Science: Time Series and Simple Linear Regression
Task 2
Read and work through Chapter 15 - Machine Learning - and understand the examples. 

15.1 Introduction to Machine Learning
15.1.1 ★ Scikit-Learn
15.1.2 ★ Types of Machine Learning
15.1.3 Datasets Bundled with Scikit-Learn
15.1.4 Steps in a Typical Data Science Study
15.2 Case Study: Classification with k-Nearest Neighbors and the Digits Dataset, Part 1
15.3 Case Study: Classification with k-Nearest Neighbors and the Digits Dataset, Part 2
15.4 ★ Case Study: Time Series and Simple Linear Regression
Suggestion: Specify data file paths as Python raw strings. See FAQ for more.

 

Task 3 (from 10.16 above)
Follow the process provided in the text. 

Follow the instructions from 10.16 (starting page 414).
Note: The data is for the average (daily) high temperature in January over many years.
For example, in 1895, the average high temperature in January was 34.2.
We only care about this one series of data: the "average high temp in Jan".
There's a lot of stats in the title, and it has confused students. Just think of each value as "the temperature" for that year.
We'll use all of the data available to build a best-fit line (supervised learning). 
We'll use the slope and intercept of the best-fit line to estimate a point out in the future.
Use a notebook (rather than interactive mode). 
Use pandas DataFrames to plot Celsius vs Fahrenheit 
Refresh your understanding of the equation for a line (y=mx +b)
Follow the instructions to load NY City January high temperature from a csv file into a DataFrame.
Follow the instructions to view head and tail of the file. 
Follow the instructions to clean the data.
Use describe() to calculate basic descriptive statistics for the dataset. 
Use the SciPy stats module linregress function to calculate slope and intercept for the best fit line through the data.
Use your results to predict the "average high temp in Jan" for the year 2026. 
Follow the instructions and use Seaborn to generate a scatter plot with a best fit line. Set the axes and y limit as instructed.
In the same notebook, continue with 15.4 (staring page 620). 
This time, we'll use scikit-learn estimator, and we'll practice splitting data for training (to build a model) and testing (testing our model against known values). 
Follow the instructions all the way though charting it again with the specified axes.
At the end of your notebook add some remarks comparing the two methods. 
By now, you know to include the title, your name, and section headings (always!) and to tell an engaging story with data, so we won't remind you.
Excellent analytical skills need professional communication skills to be of maximum benefit. 

Task 3 Output
Document your results.

execute the completed notebook before you commit and push to GitHub. 
Task 4. Push to GitHub
Push to GitHub.

Optional Task 5. Bonus
Practice more machine learning skills by working through 15.5 with the California Housing Dataset.
Follow the instructions all the way though loading the data, training and testing the data, visualizing the data, and choosing the best model from the 4 listed. 
Customize your presentation and include helpful remarks to "tell a story with data".
Execute the notebook.
Add/commit/push your changes up to your GitHub repo.
