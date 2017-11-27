# coursera_deep_learning_hmwk

## Course 1
#### Neural Network and Deep Learning. They are based on numpy. 
#### hmwk 1-5 belong to coursera deep learning specialization course 1
* hmwk 1 (optional) is used to let student have some basic understanding on numpy.
  - build sigmoid fuction / gradient of sigmoid
  - reshape(np.reshape), vector normalization (np.linalg.norm)
  - boardcasting and softmax
  - L1 L2 norm
  
* hmwk2 built a logistic regression on a 209 (m) * 64*64*3 image data set 
  - initialization (zeros init because of logistic reg)
  - basic forward and backward prop
  - Gradient descent
  - structure/shape of the feeding data. Each col contains a pic,rather than row.
  - Viz of cost changing
  
- hmwk3 buit a **shallow neural net** to do binary classification.
  - Two layers
  - Loop, forward/ backward chain, parameter update function
  - Hidden layer number of unit tunning.
- hmwk4 & hmwk5 buit a **'deep' neural net** to cat/non-cat calssification.
  - automatically do loop, forward, backward, cache of A_prev, W, b, grads, parameter update. (based on number of layers)
  - relu vs. sigmoid
  - homework 5 compared performance between two layers and 5 layers NN.
  
## Course 2
#### Improving Deep Neural Net
#### hmwk 6-? belong to coursera deep learning specialization course 1
* hmwk6 implemented zero, random, he's initialization methods.  Kaiming He's method shows awesome output

* hmwk7 implemented L2 normalization and dropout methods. The backward prop with dropout has some tricky parts. You need to save the D2 amd D1 for A2 and A1 which did dropout, and apply D2 D1 to dA1 and dA2.

* hmwk8 implemented gradient check which is meaningless in pytorch LOL. But it still a good practice
