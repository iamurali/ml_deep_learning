# Convolution

In Convolution neural network there are 4 basic steps that are involed. 
1. Convolution
2. SubSampling
3. Activation
4. Fully connected

Writing my understandings about Convolution. 

### Convolution:

The first layer of CNN is Convolution where it receives input signal and try to identify/label the input by referring what it has learned in the process. 

Convolution is works irrespective of postion of the object. Output strength is not dependent on where the feature is present but simply whether the feature is present or not. 

So it will be able to identify the object irrspective of how it's presented in the image. 

##### Example: 

Below is a running demo of Convolution layer. It's 5 * 5 * 3 
we have two filters of size 3 * 3 which results in 3 * 3 * 2



![Alt Test](https://jifflenow-qa.s3-us-west-1.amazonaws.com/2cd085bf-94e8-4bdd-83e5-5ce67f7a04ec/company/logo.png?t=1524591100591 "Example Gif")




### Activation Function


It's used to determine the output of neural network like yes or no. It's resulting in b/w 0 to 1. 

Activation functions can be 2 types 
1. Linear Activation
2. Non-Linear Activation functions.

there are different types of action funtioncs that are avaliable. 

1. Sigmoid ---> Predicts output b/w o to 1 as a probability.
2. ReLU ---> x if x > 0 otherwise 0 
3. Tanh — Hyperbolic tangent