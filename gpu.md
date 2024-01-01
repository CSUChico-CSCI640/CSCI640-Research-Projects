# CSCI640 Inquiry Based Project - Code Accelerators

## Goals
This project has the following goals:

* Project sets out to answer a question about code accelerators
* Students find a survey of research work as the starting point of their project
* Students devise a way to test and/or gain understanding about the question they are trying to ask through a hands on implementation of the concept.
    * Should come up with a procedure or method for testing the effectiveness of known solutions or their solutions.
* Students present their findings to the class
* Students write up a document with their findings

## Sample Questions

Recommended questions, you are welcome to propose a different one. If you did an inquiry based project in one of my classes you can not answer the same question. Any new question needs approval first.

* How much of a performance benefit is accerated code vs non-accerated code on a GPU?
    * Should test at least three different types of code to test the performance.
    * Examples of type of problems to test:
        * Matrix Multiplication
        * Image filtering
        * Sum Reduction
        * Convolutions
        * Mandelbrot
        * Numerical Applications (Integrals, etc)
        * Vector math

### Programming Language Choice

As the expectation for some students in this course will only be Python experience, the comparison of native Python to Python GPU accelerated using the [Numba](https://numba.readthedocs.io/en/stable/cuda/index.html) package is the expectation and what will be supported in this class; however, if you want to write native CUDA in C or C++ and compare that to non-accelerated code you are welcome to but I am too rusty to assist should you run into complex issues with that route.

## Teams

This project must be done individually, you are responsible for your own work.

## Evaluation

Your project will be graded based on the following components.

* Papers - You will need to find a minimum of 2 papers that relate to your topic beyond ones from class or try to solve the question you are wanting to answer. These cannot all come from the same research group/team/author. Also need to be in addition to papers provided in class.
* Presentation - You will need to give a short 5 minute presentation to the class on what you were trying to answer, how you tested, and what findings you discovered
* Paper - You will submit a short paper describing what you were trying to answer, how you tested it, the testing results, and what you learned from these results. This will be in the form of a *pdf*.
    * What is your question
    * Your experimental setup (machines, etc)
        * Are there any side effects or artifacts related to your experimental setup that might impact your results?
        * Who you worked with, if anyone, to help setup this environment
    * How you ran your tests to answer your question
    * Test results:
        * How accurate are they?
            * Make sure you run enough tests that your results are accurate enough.
        * Do you have variation in your testing?
    * Your conclusion/answer to the question
    * What you learned from answering the question
* Code - Any code you used for testing in the process of your inquiry used as part of the evaulation in the submitted paper.

Submit any code and your paper to [INGInious](https://inginious.csuchico.edu) as a *tar.gz* file.

