# Machine Learning Curriculum
A curriculum to guide people into understanding the fundamentals of Machine Learning and prepare them for Reinforcement Learning

## Introduction - Python: - Todo See if this has any inspiration: https://github.com/Akuli/python-tutorial
To do any machine learning work, you will need a basic understanding of Python. 

If you are familiar with Python then you should skip this section.

Learning a coding language is not as daunting as it sounds, as understanding the absolute basics makes everything easier. All a program is, is a set of instructions. If you read from the top of the program to the bottom and ask what each line means, you can translate a program back to an english set of instructions.

Learning a coding language is a time commitment, but here is a time efficient tutorial: [Python in 1 hour](https://www.youtube.com/watch?v=kqtD5dpn9C8&ab_channel=ProgrammingwithMosh). There are other resources out there but this is an overview of the basics.

The important parts of python we will use are, in order:

Variables, Assignment, and Printing - Containers, and storing numbers in the containers - [Tutorial](https://www.pythontutorial.net/python-basics/python-variables/)

Operators - How Python does math for you - [Tutorial](https://www.tutorialspoint.com/python/python_basic_operators.htm)

Arrays - How to store many numbers

Loops - How Python can repeat a task for you

Conditions - How Python can make decisions

Functions - How to repeat yourself less


Some more advanced topics you may find helpful:
Pass by value vs. Pass by reference
Pip
Numpy and Scikit Learn

## Section 1 - The Basics:
Episodes 1 & 2 of Grant Sanderson's series on neural networks is a thorough and concise introduction to what the purpose of machine learning is, how it works, and most importantly, how to understand it.

[![Gradient descent, how neural networks learn](https://img.youtube.com/vi/aircAruvnKk/0.jpg)](https://www.youtube.com/watch?v=aircAruvnKk)
[![But what is a neural network?](https://img.youtube.com/vi/IHZwWFHWa-w/0.jpg)](https://www.youtube.com/watch?v=IHZwWFHWa-w)

If you would like to go more in depth than that then go ahead and complete the series, but in my opinion, these are the best videos for the time commitment. That will be my philosophy though this tutorial, but if you want more materials for a better understanding, we will have those available too: [Complete Playlist](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)

### Examples: 
 * See the [section 1 folder](https://github.com/nickrallison/Machine_Learning_Curriculum/tree/main/Section%201%20-%20The%20Basics) for your first hands on example


## Section 2 - Types of Math used in Artificial Intelligence (Can always move stuff around like putting this in Section 5 for advanced materials):

Machine learning like everything you learn in university, is a tool. It is a very powerful tool, but a tool nonetheless. You wouldn't use a sledgehammer when you need a saw, or even a smaller hand tool.

You will likely encounter problem where you think: "Can this be solved by machine learning?" and the answer is often yes... but. Another question you should ask is *should* you use machine learning?

Here are some statistical tool you can use not only instead of machine learning, but also in addition to it:

### Techniques:

 * [Regression Analysis](https://www.youtube.com/watch?v=vPde9bYrr80) - A tool most often used to find the equation relating many **linearly** related variables. For those of you who may find this interesting, I suggest watching a video about non-linear regressions. A powerful too to fit data to a *Non-Linear* Function

 * [Singular Value Decomposition](https://www.youtube.com/watch?v=gXbThCXjZFM&ab_channel=SteveBrunton) - This is a personal favorite of mine. The singular value decomposition (or SVD) is a tool often used with very *very* large datasets. It finds the "Principle Components" of that data from which every other component is made, much like the Fourier Transform finds underlying frequencies in a signal.

 * [Principle Component Analysis](https://www.youtube.com/watch?v=HMOI_lkzW08&ab_channel=StatQuestwithJoshStarmer) - PCA is very similar to the above SVD in that it finds the most commmon components in the data you give it. Much like giving it macy recipes and classifying them into your fundamental recipes, of a baked good, a caserole, or a steak dinner. 

 * SVMs...
 
 * Naive Bayes...

 * Logistic Regression...
 
 * K-Nearest Neighbor...
 
 * Random Forest...
 
 * TBD


### Tools:

 * MATLAB: Very commonly used in statistical learning, I personally find it useful to see if there is an analytical solution to a problem before trying an inetrative approach. (This is often a long process, and sometimes a longer formula. This is the reason I appreciate MATLAB)

 * Python / Numpy / Tensorflow: Python is a very commonly used language in machine learning and you will see it in use while training on AWS' deepracer. There is a large collection of frameworks and support for python in addition to it being a very user-friendly language.

 * C++ / Eigen: A favorite of mine, while not beginner friendly, C++ and Eigen are a powerful combination of tools for linear algebra analysis. Out of the above languages, this is the lightest and can even run on an Arduino.


### Examples: 
 * TBD


## Section 3 - Intro to Machine Learning:
Now lets take our first step into the wonderful world of machine learning. There are many catagories to machine learning, but the most common you will hear about are:
 * Supervised - Where data is given with labels so the model knows what to expect.
 * Unsupervised - Data is given without labels and the model decides how to catagorize the data itsself.
 * Reinforcement - Data decides for itself how to procede based on a user defined reward function. We will go more in depth on this is a later chapter.

**Supervised vs. Unsupervised Learning**

[![Supervised vs. Unsupervised Learning](https://img.youtube.com/vi/rHeaoaiBM6Y/0.jpg)](https://www.youtube.com/watch?v=rHeaoaiBM6Y&list=WL&index=1&ab_channel=EyeonTech)

### Examples:
In my opinion, the best way to learn the hardest topics is to get hands on experience. See the repositories below, clone them to your computer, and follow the instructions, best of luck!
 * TBD


## Section 4 - Reinforcement learning
Finally to the goal. Now, if you are a little rusty on the basics, you may want to revise before jumping into the deep end. If you are feeling comfortable or adventureous then read on. 


Thorough and dense resources for a better understanding of reinforcement learning and it's challenges: [Reinforcement Learning Playlist](https://www.youtube.com/playlist?list=PLMrJAkhIeNNQe1JXNvaFvURxGY4gE9k74)



## Section 5 - Advanced Topics
This section will contain more complex and interesting topics, and is largely more broad than past sections
