# MNIST-Image-Classification
## Task - Handwritten Digit Classification

## No. Of Classes → 10

## Type of Problem → Multi Class Classification

## Algorithms
1. Logistic Regression 
2. Random Forest Classifier
3. Deep Learning - 3 Layered Feed Forward Neural Network

### Resources used

- pyTorch documentation
- [Jovian.ai](http://Jovian.ai) - ml course
- kaggle notebooks

# About The Dataset :

This dataset is a built in dataset in the torchvision library and is very handy to work with for beginners. It has 60000 images of handwritten digits in grayscale , and 10000 separate images for test set.

# Approach:

So, how do we start ? You should take your time planning this out before you start solving the problem.

1. Download the dataset, both test and train
2. (This is only because  I am using pyTorch) Transform the dataset into tensors
3. Load the data into batches using DataLoader function
4. Load the data on a GPU device ***if*** you have one.
5. Build The Model
6. Train The Model 
7. Optimise the Parameters
8. Summarise → Very Important Step that most people forget

