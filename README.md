# MNIST #

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jofaval/mnist/blob/master/notebook.ipynb)

## Table of contents

1. [📁 Data](#-data)
1. [📓 Description](#-description)
1. [✔️ Objectives](#-objectives)
1. [🧱 Tech stack](#-tech-stack)
1. [💹 Algorithms](#-algorithms)
1. [📊 Visualization](#-visualization)
1. [🤓 Conclusions](#-conclusions)
1. [©️ Credits](#-credits)

## 📁 Data
[↑ Back to the table](#table-of-contents)

The data is available at the `sample_data` folder that is available with every Google Colab Notebook.

## 📓 Description
[↑ Back to the table](#table-of-contents)

This is a beginner notebook about sort of advanced topics, the hello world of computer vision, and a deep exploration into Data Science and Neural Networks, and it's architecture.

My previous project about [California Housing Pricing](https://colab.research.google.com/github/jofaval/california-housing-pricing) was more about Data Analysis and Data Science, in this project I've focused more on the Data Science, MNIST leaves almost no room to real exploratory data analysis, and we could do some analysis about the graphism of the digits and the hand writting, but it is completely out of my domain of knowledge.

So, what is there to expect from this project? A junior approach to computer vision with neural networks using PySpark, Tensorflow and PyTorch.

## ✔️ Objectives
[↑ Back to the table](#table-of-contents)

In no specific order whatsoever:

- Put together the knowledge adquired in a more fashionable way.
- Explore the data correctly in a way that makes sense.
- Upload a starter project to my fill non-existent data science portfolio.
- Define and explore ways to present the conclusions and the process.
- Explore, learn and improve my knowledge on neural networks using simple example such as the MNIST Dataset.
- Improving and polishing my skills as a junior data scientist and data analyst.

The one thing that, for sure, I had in mind before starting this project, is that I wanted to use PySpark, then, I wanted to also use Tensorflow and Keras, since I'm, at the moment being, more comfortable with them, and as the project went on, I encouraged myself to try PyTorch, a library I never picked on, and only seen, briefly, in my academic education.

## 🧱 Tech stack
[↑ Back to the table](#table-of-contents)

Python, that's it! R is a programming language that, as for the moment being, I have no experience with, even though it's powerful and broadly used, but I'd dare to say that no more than Python.

And one of the strongest points, if not the most, about Python, are it's libraries, so... the libraries I've used are:

- Pandas, data manipulation with an ease of use and exploration data analysis.
- Numpy, a really strong linear algebra library, used in the project for it's statistics utilities, SciPy may be an alternative, but I have no experience at all with it.
- Matplotlib and Seaborn, both fantastic libraries for data visualization, and they complement each other.
- PySpark, a powerful implementation of Spark, a parallelization framework based on Java and Scala and widely used for Big Data Architectures.
- Tensorflow and Keras, the industry standard for Deep Learning.
- PyTorch, an opensource Deep Learning library that's object oriented.

## 💹 Algorithms
[↑ Back to the table](#table-of-contents)

Neural networks, my main objective for this project was to only use neural networks, I've used almost exactly the same architecture in different libraries, but only in Tensorflow have I implemented some sort of regularization, which should of been a must to be honest.

My idea while building the architecture, what I grasped was that, having that many inputs (more than 10), having hidden layers with not many inputs was leading to information loss and a really poor performance, so I tried to split the data processing between two hidden layers, not in PySpark, and having half of the inputs as neurons for the first hidden layer, then a fourth for the second hidden layer.

Regularization is a must in this kind of projects, it helps avoiding overfitting so that a better performance can be achieved on never-seen data. It barely increased the performance, but it did!

## 📊 Visualization
[↑ Back to the table](#table-of-contents)

For this project, just a plot grid, and plotting the evolution of the neural networks, so... just plain lineplots and grids of images, which is exactly what was needed for this project, nothing fancier.

## 🤓 Conclusions
[↑ Back to the table](#table-of-contents)

Computer Vision with Deep Learning are really powerful, just 20k images sufficed for a simple neural network to learn to identify handwritter digits, that's awesome!

Unsupervised is the way to go in this project, no need to understand in a deep level how it is getting the results, it just does. Obviously is not magic, the information gets passed from layer to layer and it learns it's patterns. There are weights and biases for each layer.

And, even though it's most likely overfitting, having no score below 95% is a really nice result, but with this project, the fitting started taking it's time, no more almost instantly fitting a model, just a couple of minutes, but still. I'm happy with what was achieved.

## ©️ Credits
[↑ Back to the table](#table-of-contents)

All of the credits for the datasets goes to Yann LeCun, Corinna Cortes and Christopher J.C. Burges. And to Google, but any more details at the official [MNIST's documentation](http://yann.lecun.com/exdb/mnist/).