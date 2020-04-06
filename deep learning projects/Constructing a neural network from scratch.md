          Nueral network from scratch

I have used various websites and explored to construct a neural network without any use of packages except numpy
	This project consists of implementing a neural network with mini-batch structure. The neural network consists of 1 hidden layer and 1 output layer. The number of neurons in the hidden layer, batch size and number of epochs can be provided by the user. The number of neurons for the output layer is 10. 
	The input is obtained from keras mnist dataset. The dataset is in 60,000 x 28 x 28 format. The dataset is normalized using sklearn.preprocessing function and keras is used for loading the mnist dataset. The loss function in this network is cross-entropy and activation function is taken as sigmoid in the first hidden layer and softmax for the output layer. The libraries used in this program are keras for dataset, sklearn for preprocessing, numpy for math and matrix functions and matlplotlib for graphs.
