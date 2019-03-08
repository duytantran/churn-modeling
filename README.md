# Churn Modeling
A classification problem to find out the highest rate for a customer that wants to leave a bank. We are given a dataset over 10'000 customer information, and need to predict a classification model. Since this problem is non-linear and complex, this is solved by training an artificial neural network with stochastic gradient descent. Coded in both Python and R. 


Based on experiments and research, we choose the rectifier activation function for the hidden layers. Deep Learning is used to solve non-linear problems, and the rectifier function will break the linearity between the output- and input neurons. As for the output layer, we choose the sigmoid activation function since it allows us to get the probabilities of the different segments, which again will get the probability for the classical one for each of the observations and even the new observations of the test set when we'll make our predictions. In other words, we will get the probability for when the customers decides to leave the bank and when the customers decides to stay. If we deal with a problem with a dependent variable with more than two categories, change sigmoid with softmax function!  


Since there is no rule of thumb of choosing the number of nodes in the hidden layer, we decide to choose the hidden layer as the average of the number of nodes in the input layer and the number of nodes in the output layer. Since we have 11 independent variables and 1 dependent variable, the average is 6. Of course, we can experiment with parameter tuning with a tecnique such as K4 cross-validation.


Check out neuralnetworksanddeeplearning.com by Michael Nielsen for more in-depth learning (see what I did there?).
