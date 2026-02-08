# Fashion-MNIST-Image-Classification
##https://colab.research.google.com/drive/11SS0dz1QFN7iV62Zm1Rb3PEQO7YpQbuw

#Question:
###1. What is the Fashion MNIST dataset?
The fashion MNIST dataset consists of grayscale images of various fashion items, divided into two sets for training and testing.

###2. Why do we normalize image pixel values before training?
We normalize image pixel values to make training faster, more stable, and more accurate. It helps the model learn better by keeping the numbers small and consistent.

###3. List the layers used in the neural network and their functions.

Input layer – receives the data
Hidden layers – learn and process features (convolution, activation, pooling, dense, dropout)
Output layer – gives the final prediction or result

###4. What does an epoch mean in model training?
it is one full cycle of learning from all the training data once. The model usually needs many epochs to improve its accuracy.

###5. Compare the predicted label and actual label for the first test image.
Predicted label- kanang Mao ni ang giingon sa AI/model nga class sa image.
Actual label- unya kaning actual label Mao ni ang tinuod nga class sa image gikan sa dataset.
Comparison- kanang Tan-awon kung sakto ba ang prediction (match sa actual label) o sayop.

###6. What could be done to improve the model’s accuracy?
To improve the model’s accuracy, you can use more and better-quality data, apply data augmentation, balance classes clean labels  use a stronger or pretrained model, tune hyperparameters, and analyze errors to see where the model fails. Regularization, proper training strategies, and evaluating per-class performance also help.


