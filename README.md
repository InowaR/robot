# Autonomous robot

## Why do we need matrices? 

  Think of the discrete and analog magnitude of an electrical signal, a handful of sand consisting of millions of grains of sand that cannot be counted. Volumes of water containing an unimaginable amount of divisible and indivisible particles. Gears and gears of various sizes that convert rotational speeds. Numbers are used to evaluate, compare, number, and calculate the value. In artificial intelligence, numbers are used to transform data.  

## What is a perceptron? 

  A neural network transforms an X matrix into a Y matrix using one or more W-matrices. The matrix X is the input data, for example, an image. The Y matrix is the output data, for example, the class of the object in the image.
The input matrix X is a training set, each sample can be a number, vector, matrix, and so on. The matrix Y can be a number, a vector, a matrix, depending on the task that the perceptron solves. The matrix W is filled with random numbers. 
  The input matrix X is completely sent to the function along with the matrix W. Further, depending on the configuration of the neural network, the result of the previous function is sent along with the new matrix W to the new function, or the result is final. 
To train neural networks, the derivative of the function and the error between the output matrix and the actual result obtained during calculations using W matrices given by random values are used. 
  An important difference between the learning stage and the direct passage is the reversal of the matrix and the application of the calculated deviation of the actual result from the reference to the derivative of the function.
Subsequent layers in the opposite direction take the already calculated deviations and derivatives and apply them to the previous matrix of inverted weights. The matrix rotates like a book if you rotate it diagonally around its axis. After performing the reverse pass, the correction matrices are added with some coefficient A to the weight matrices W in order. The output layer correction matrices are added to the output layer matrices W and so on.
After a certain number of updates of the matrix W, the network remembers the connection of the input matrix X with the matrix Y. In addition, the new intermediate values of the input matrix can be interpreted as intermediate values of the output matrix. This way you can train a neural network. 

## How to train a neural network? 

  A neural network can accurately transform input data into output and navigate unfamiliar data. For adequate training of the neural network, it is necessary to select the training matrices X, Y in such a way that they do not contain unnecessary data. Depending on the training task, it may be necessary to change the size of the intermediate layers, change the value of the coefficient A and the number of training cycles.
