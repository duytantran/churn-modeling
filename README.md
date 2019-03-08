# Churn Modeling
A classification problem to find out the highest rate for a customer that wants to leave a bank. Since this problem is non-linear and complex, this is solved by training an artificial neural network with stochastic gradient descent. Coded in both Python and R. 


Based on experiments and research, we choose the rectifier activation function for the hidden layers. As for the output layer, we choose the sigmoid activation function since it allows us to get the probabilities of the different segments, which again will get the probability for the classical one for each of the observations and even the new observations of the test set when we'll make our predictions. In other words, we will get the probability for when the customers decides to leave the bank and when the customers decides to stay.  


Since there is no rule of thumb of choosing the number of nodes in the hidden layer, we decide to choose the hidden layer as the average of the number of nodes in the input layer and the number of nodes in the output layer. Of course, we can experiment with parameter tuning with a tecnique such as K4 cross-validation.

Check out neuralnetworksanddeeplearning.com by Michael Nielsen for more in-depth learning (see what I did there?).
