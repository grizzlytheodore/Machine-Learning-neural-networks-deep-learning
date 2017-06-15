# Machine-Learning-neural-networks-deep-learning

In depth documentation in ex4.pdf

In this exercise, I implement the neural netowrks and apply it to the task of hand-written digit recognition.
First I implement the feed forward regularized cost function. Then I implement and use the backpropagation algorithm to improve the cost.
The intuition behind it is to measure how much each node was responsible for any error in the output. Then the learning function minimizes the cost. 
After the training completes, the accuracy comes out to 95.3%.



I contributed to the following files: 
sigmoidGradient.m - compute the gadient of the sigmoid function
randInitializeWeights.m - randomly initialize weights
nnCostFunction.m - neural network cost function
predict.m - neural network prediction fuction (previous exercise)
