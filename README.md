# Machine Learning Curriculum
A proposed Curriculum to guide people into understanding the fundamentals of Machine Learning and prepare them for Reinforcement Learning


## Section 1 - The Basics:
Episodes 1 & 2 of Grant Sanderson's series on neural networks is a thorough and concise introduction to what the purpose of machine learning is, how it works, and most importantly, how to understand it.

[![But what is a neural network?](https://img.youtube.com/vi/IHZwWFHWa-w/0.jpg)](https://www.youtube.com/watch?v=IHZwWFHWa-w)
[![Gradient descent, how neural networks learn](https://img.youtube.com/vi/aircAruvnKk/0.jpg)](https://www.youtube.com/watch?v=aircAruvnKk)

If you would like to go more in depth than that then go ahead and complete the series, but in my opinion, these are the best videos for the time commitment. That will be my philosophy though this tutorial, but if you want more materials for a better understanding, we will have those too: [Complete Playlist](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)

### Examples: 
 * TBD


## Section 2 - Types of Math used in Artificial Intelligence:

Machine learning like everything you learn in university, is a tool. It is a very powerful tool, but a tool nonetheless. You wouldn't use a sledgehammer when you need a saw, or even a smaller hand tool.

You will likely encounter problem where you think: "Can this be solved by machine learning?" and the answer is often yes... but. Another question you should ask is *should* you use machine learning?

Here are some statistical tool you can use not only instead of machine learning, but also in addition to it:

### Techniques:

 * [Regression Analysis](https://www.youtube.com/watch?v=vPde9bYrr80) - A tool most often used to find the equation relating many **linearly** related variables. For those of you who may find this interesting, I suggest watching a video about non-linear regressions. A powerful too to fit data to a *Non-Linear* Function

 * [Singular Value Decomposition](https://www.youtube.com/watch?v=gXbThCXjZFM&ab_channel=SteveBrunton) - This is a personal favorite of mine. The singular value decomposition (or SVD) is a tool often used with very *very* large datasets. It finds the "Principle Components" of that data from which every other component is made, much like the Fourier Transform finds underlying frequencies in a signal.

 * [Principle Component Analysis](https://www.youtube.com/watch?v=HMOI_lkzW08&ab_channel=StatQuestwithJoshStarmer) - PCA is very similar to the above SVD in that it finds the most commmon components in the data you give it. Much like giving it macy recipes and classifying them into your fundamental recipes, of a baked good, a caserole, or a steak dinner. 

 * SVMs...
 
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
[![Supervised vs. Unsupervised Learning](https://img.youtube.com/vi/rHeaoaiBM6Y&list=WL/0.jpg)](https://www.youtube.com/watch?v=rHeaoaiBM6Y&list=WL&index=1&ab_channel=EyeonTech)
