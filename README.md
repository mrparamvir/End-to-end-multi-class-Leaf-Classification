# End-to-end-multi-class-Leaf-Classification.
Using binary leaf images and extracted features, including shape, margin and texture, to accurately identify 99 species of plants. Due to their volume, prevalence, and unique characteristics, are an effective means of differentiating plant species. They also provide a fun introduction to applying techniques that involve image-based features.

#  🍂🍁 End-to-end Multi-class Leaf Classification
This notebook builds an end-to-end multi class image classifier using TensorFlow 2.0 and TensorFlow Hub.

## 1. Problem

Identifying the species of plants given an image of a leaf. 


## 2. Data

The data we're using is from Kaggle's Leaf Classification competition.

https://www.kaggle.com/c/leaf-classification/data

## 3. Evaluation

The evaluation is a file with prediction probabilities for each leaf species of each test image.

https://www.kaggle.com/c/leaf-classification/overview/evaluation

## 4. Features

Some information about the data:
* We're dealing with images (unstructured data) so it's probably best we use deep learning/transfer learning.
* There are 99 species of plants (this means there are 99 different classes).
* There are around 900+ images in the training set (these images have species).
* There are around 500+ images in the test set (these images have no species, because we'll want to predict them).

