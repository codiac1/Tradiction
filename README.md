# Tradiction
STOCK PRICE PREDICTION using Machine Learning

Introduction

Predicting how the stock market will perform is one of the most difficult things to do. There are so many factors involved in the prediction – physical factors vs. psychological, rational and irrational behavior, etc. All these aspects combine to make share prices volatile and very difficult to predict with a high degree of accuracy.

With the help of Machine Learning , we are going to predict the stock prices , machine learning techniques have the potential to unearth patterns and insights we didn’t see before, and these can be used to make unerringly accurate predictions. Now for this we will use Modules such as LSTM , pandas and Numpy.

LTSMs are a type of Recurrent Neural Network for learning long-term dependencies. It is commonly used for processing and predicting time-series data. 

<img width="700" alt="LSTM" src="https://user-images.githubusercontent.com/88943739/166753353-820f9311-dc25-4915-a388-61cb5566ea75.png">

you can see LSTMs have a chain-like structure. General RNNs have a single neural network layer. LSTMs, on the other hand, have four interacting layers communicating extraordinarily.

LSTMs work in a three-step process.

1. The first step in LSTM is to decide which information to be omitted from the cell in that particular time step. It is decided with the help of a sigmoid function. It    looks at the previous state (ht-1) and the current input xt and computes the function.

2. There are two functions in the second layer. The first is the sigmoid function, and the second is the tanh function. The sigmoid function decides which values to let    through (0 or 1). The tanh function gives the weightage to the values passed, deciding their level of importance from -1 to 1.

3. The third step is to decide what will be the final output. First, you need to run a sigmoid layer which determines what parts of the cell state make it to the output.    Then, you must put the cell state through the tanh function to push the values between -1 and 1 and multiply it by the output of the sigmoid gate.
