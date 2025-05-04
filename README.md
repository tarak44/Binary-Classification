Hog or Not?

A PyTorch Image Classifier in Jupyter Notebook

Can a machine tell the difference between a picture of a hog and a completely blank image? With a bit of PyTorch magic, yes it can. This project walks through the full process of training a binary image classifier—right inside a Jupyter notebook.


---

Project Overview

This is a binary image classification task using PyTorch to identify whether an image contains a hog or is just blank. It's a beginner-friendly project built entirely in a Jupyter Notebook, covering:

Data loading and preprocessing

CNN model creation

Training and evaluation

Prediction on new images



---

What You'll Need

Prerequisites

Python 3.7+

Jupyter Notebook

Install the required packages:


pip install torch torchvision matplotlib numpy


---

Dataset Structure

Organize your dataset in this format:

data/
├── hog/
│   ├── hog1.jpg
│   ├── ...
├── blank/
│   ├── blank1.jpg
│   ├── ...


---

How to Run the Notebook

1. Open the notebook:



jupyter notebook hog-or-not.ipynb

2. Follow the steps in order:

Load and visualize the dataset

Preprocess and augment the data

Build and train the CNN

Evaluate performance

Make predictions on new images





---

Example Results


---

Project Files

hog-or-not/
├── data/
│   ├── hog/
│   └── blank/
├── models/
├── hog-or-not.ipynb
├── README.md


---

Why Do This?

This project is great for:

Learning PyTorch through hands-on practice

Building and training CNNs in Jupyter

Understanding the full ML pipeline for image classification



---
