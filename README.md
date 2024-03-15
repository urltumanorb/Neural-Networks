# Neural-Networks
## What is the project?
This project is a lab that helpping you to learn technologies related to use neural networks to recognize handwritten digit. It also introduced ReLU Activation and Softmax Function and helped you do the Neural Networks tasks step by step.

## Concepts
### ReLU Activation
ReLU is a piecewise linear function that will output the input directly if it is positive, otherwise, it will output zero.
<img width="264" alt="image" src="https://github.com/urltumanorb/Neural-Networks/assets/24932621/582c7132-4269-46a3-98a4-21e77da20c40">

<img width="396" alt="image" src="https://github.com/urltumanorb/Neural-Networks/assets/24932621/f1e830a7-a513-4649-9242-dcdeb8cc715f">

### Softmax Function
The softmax function converts a vector of K real numbers into a probability distribution of K possible outcomes. It is a generalization of the logistic function to multiple dimensions, and used in multinomial logistic regression.
<img width="604" alt="image" src="https://github.com/urltumanorb/Neural-Networks/assets/24932621/9b3ab906-2769-438c-93a9-eb979bfa9ad9">

## Which programing language and packages did I use?
### Language
Python - It is a high-level, general-purpose language. It has concise and expressive syntax, as well as a powerful standard library. It is suitable for various application development domains, including web development, data science, artificial intelligence, and more. In this procject, I used python to accomplish some mechine learning work.

### Packages
numpy - It is the fundamental package for scientific computing with Python.
matplotlib - It is a popular library to plot graphs in Python.
tensorflow - It is a popular platform for machine learning.
```
import numpy as np
import tensorflow as tf
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Dense
from tensorflow.keras.activations import linear, relu, sigmoid
import matplotlib.pyplot as plt
```

## Dataset
In this lab, we use two array(x and y) to do the Neural Networks task.

x: <img width="785" alt="image" src="https://github.com/urltumanorb/Neural-Networks/assets/24932621/9952b28b-f029-4cfe-ba0a-c19e7c1167b4">

y: <img width="145" alt="image" src="https://github.com/urltumanorb/Neural-Networks/assets/24932621/7b6b69c6-68b2-42aa-a939-dc7b45cea6c4">


