# Machine Learning Engineer Nanodegree 2019
## Grocery item image recognition using a custom dataset

This repository contains the materials accompanying my Capstone project for the Machine Learning Engineer Nanodegree.

## Summary

### Software and libraries 
OS: Windows `10` <br>
Language: Python `3.7.3` <br>
Libraries: Pytorch `0.4.1`, Matplotlib `3.1.1` Numpy `1.16.4` <br>
Framework: Jupyter Notebook <br>

### Motivation
Automation is one of the largest growing applications in AI, with the goal of replacing tedious jobs and reducing time and energy devoted to mundane daily tasks.  Spam filters for email, warehouse sorting robots, and even more ambitious projects such as data analytics or self-driving cars are all examples of how we are increasingly relying more heavily on automation in our personal lives and as a society.  Using machine learning makes it possible for these tools to navigate through dynamic and ambiguous situations by identifying patterns among each unique scenario that is encountered.   

One area that is deeply entrenched in an average person’s daily life is grocery shopping and food preparation.  While there have been advances in making this process easier and more efficient – online food shopping, food delivery, and millions of recipes available online – there is a lot of room for making the process easier.  For example, using computer vision techniques in AI could automate item inventory and shelfing through image recognition of grocery items.  Another possibility is using consumer purchase history to make food recommendations to buyers, to help them find desired items more easily.  

### Project Outline
In this project, I step through several steps of the machine learning workflow:
- Obtain customized dataset of images by merging datasets and augmenting images 
- Clean, load, and preprocess images 
- Train the classifier using pre-trained models
- Predict image classification with trained model

## Content

### Notebooks folder
- `Code`: entire codeset, as well as output
- `Augment` : code to augment images to increase dataset size 
- `Merge`: code to combine and clean datasets
- `Transform`: code to process custom dataset and transform images
- `Train`: code to build and train model
- `Test`: code to test accuracy of entire model, and of each class
    
### Datasets folder
- Fruits 360 dataset: [https://github.com/Horea94/Fruit-Images-Dataset](https://github.com/Horea94/Fruit-Images-Dataset)
- Freiberg Grocery dataset: [https://github.com/PhilJd/freiburg_groceries_dataset](https://github.com/PhilJd/freiburg_groceries_dataset)

### Report folder
- Technical write-up of the project 
- README file with helpful resources
