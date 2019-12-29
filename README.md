# MNIST Handwritten Digits Recognition Using 2-layer CNN

Handwritten digit recognition (HWDR) is a classic machine learning (ML) problem as its
is used in varied fields of work. The model should be able to understand and recognize 
different digits in an accurate and efficient manner and be validated with unseen test data. This
model 7 layer nural network model was able to achieve an accuracy of 0.9839 with a val_accuracy 0.9876.

This model uses 7 layers total:
Layer (type)                 Output Shape              Param #   
=================================================================
conv2d_1 (Conv2D)            (None, 26, 26, 32)        320       
_________________________________________________________________
max_pooling2d_1 (MaxPooling2 (None, 13, 13, 32)        0         
_________________________________________________________________
flatten_1 (Flatten)          (None, 5408)              0         
_________________________________________________________________
dropout_1 (Dropout)          (None, 5408)              0         
_________________________________________________________________
dense_1 (Dense)              (None, 100)               540900    
_________________________________________________________________
dropout_2 (Dropout)          (None, 100)               0         
_________________________________________________________________
dense_2 (Dense)              (None, 10)                1010  





## Acknowledgments
Weights and Biases
