<!-- If you have previously created this repo for another class, double-check to ensure it follows all guidelines here.

Your site should exist at https://USERNAME.github.io/reading-notes/

The “source” for your site should be a README.md file, written with Markdown
On the main page:

Include a level-1 heading titled Reading Notes

Include a description of what this web site is about

Include a level-2 heading for each course, ie:
Code 102 - Intro to Software Development
Code 201 - Foundations of Software Development
Code 301 - Intermediate Software Development
Code 401 - Advanced Software Development

Utilize at least 5 different features of Markdown to structure your page -->

# Reading Notes #

Here are the current notes i've taken in relation to the course

## Course ##

Code 401 - Advanced Software Development

# Day 1 #

## Pain ##

- That price is pain, the pain of growth
- when being faced with new pains, I need to ask myself various questions such as WHy am I here? What is the goal? 
- Pain is an ally as much as it is an enemy

## Big o ##

Big O notation is used in Computer Science to describe the performance or complexity of an algorithm.

Big O specifically describes the worst-case scenario, and can be used to describe the execution time required or the space used (e.g. in memory or on disk) by an algorithm.

Binary search is a technique used to search sorted data sets. It works by selecting the middle element of the data set, essentially the median, and compares it against a target value. If the values match, it will return success. If the target value is higher than the value of the probe element, it will take the upper half of the data set and perform the same operation against it. Likewise, if the target value is lower than the value of the probe element, it will perform the operation against the lower half. It will continue to halve the data set with each iteration until the value has been found or until it can no longer split the data set.

Many complex operations can be ran using these big 0 syntaxes.

# Day 2 #

# TDD #

Unit tests are some pieces of code to exercise the input, the output and the behaviour of your code. You can write them anytime you want.

The test file name should follow the same name of module name. For instance, if our module is gender.py, our test name should be test_gender.py.

Other thing to care about is the structure. A convention widely used is the AAA: Arrange, Act and Assert.
Arrange: you need to organize the data needed to execute that piece of code (input);
Act: here you will execute the code being tested (exercise the behaviour);
Assert: after executing the code, you will check if the result (output) is the same as you were expecting.
Now you can execute the tests. I suggest the lib pytest to do it. But you are free to choose anything you like.

an important thing about TDD: the cycle.
The cycle is made by three steps:
🆘 Write a unit test and make it fail (it needs to fail because the feature isn’t there, right? If this test passes, call the Ghostbusters, really)
✅ Write the feature and make the test pass! (you can dance after that)
🔵 Refactor the code — the first version doesn’t need to be the beautiful one (don’t be shy)

The greatest advantage about TDD is to craft the software design first
Your code will be more reliable: after a change you can run your tests and be in peace
Beginning may be hard — and that’s fine. You just need to practice!

# Recursion #

What is Recursion?

The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called as recursive function.

In the recursive program, the solution to the base case is provided and the solution of the bigger problem is expressed in terms of smaller problems. 

How a particular problem is solved using recursion? 
The idea is to represent a problem in terms of one or more smaller problems, and add one or more base conditions that stop the recursion. 

