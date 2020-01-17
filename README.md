#       Machine Learning Engineer Nanodegree 2020
[![Certificate.png](https://i.postimg.cc/MH2ys5gp/Certificate.png)](https://postimg.cc/5YgYyBxh)

## Grocery item image recognition using a custom dataset

This repository contains the materials accompanying my Capstone project for the Machine Learning Engineer Nanodegree.

## Summary

### Software and libraries 
OS: Windows `10` <br>
Language: Python `3.7.3` <br>
Libraries: Pytorch `0.4.1`, Matplotlib `3.1.1`, Numpy `1.16.4`, imgaug `0.3.0` <br>
Framework: Jupyter Notebook <br>
Models: ResNet50, DenseNet121 <br>
[Full Report](https://github.com/cassyay/Grocery-Dataset/blob/master/Report/ML-Capstone-report.pdf)

### Motivation
Automation is one of the largest growing applications in AI, with the goal of replacing tedious jobs and reducing time and energy devoted to mundane daily tasks.  Spam filters for email, warehouse sorting robots, and even more ambitious projects such as data analytics or self-driving cars are all examples of how we are increasingly relying more heavily on automation in our personal lives and as a society.  Using machine learning makes it possible for these tools to navigate through dynamic and ambiguous situations by identifying patterns among each unique scenario that is encountered.   

One area that is deeply entrenched in an average person’s daily life is grocery shopping and food preparation.  While there have been advances in making this process easier and more efficient – online food shopping, food delivery, and millions of recipes available online – there is a lot of room for making the process easier.  For example, using computer vision techniques in AI could automate item inventory and shelfing through image recognition of grocery items.  Another possibility is using consumer purchase history to make food recommendations to buyers, to help them find desired items more easily.  

### Project Outline
In this project, I step through several steps of the machine learning workflow:
- Create customized dataset of images by merging existing datasets and augmenting images 
- Clean, load, and preprocess images 
- Train with pre-trained models ResNet50 as benchmark model, and DenseNet121 as comparison
- Predict image classification with pre-trained models

## Content

### Datasets 
- [Fruits 360 dataset](https://github.com/Horea94/Fruit-Images-Dataset)
- [Freiberg Grocery dataset](https://github.com/PhilJd/freiburg_groceries_dataset)

### Notebooks folder
- `ML Nanodegee Capstone-Benchmark.ipnynb`: entire code and results with ResNet50, on Jupyter
- `ML Nanodegree Capstone-DenseNet121.ipnynb`: entire code and results with DenseNet121, on Jupyter

### Report folder
- Technical report of the project 
- README with table of contents and helpful resources
