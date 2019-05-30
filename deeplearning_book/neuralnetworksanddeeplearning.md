neuralnetworksanddeeplearning

IDLE: c:\Python27\pythonw.exe c:\Python27\Lib\idlelib\idle.py

import os
os.getcwd()
os.chdir('C:\\Users\\Kris Johnson\\Desktop\\gitrepos\\neural-networks-and-deep-learning\\src')
os.listdir()

C:\python27
	pip comes installed with python
	to do version specific pip installs, run the pip script from the python folder
	E.g., in cmd prompt $> C:\python27\Scripts\pip.exe install numpy

hyperparameters - epochs, mini-batch size (batch to run over, aka data to use per loop per epoch), learning rate
parameters - weights and biases

	art of debugging hyperparameters
		- which way to move learning rate
		- # of epochs
		- initialized weights and biases right
		- enough training data
		- correct architecture

support vector machine (SVM), scikit-learn library, LIBSVM
	SVM code: https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/src/mnist_svm.py

backprop paper from 86: https://www.nature.com/articles/323533a0
	sci-hub

wjk is weight connection from neuron k in previous layer to neuron j in next layer
	aka, what neuron in the previous layer is this neuron connected to (so j,l are the present place, k is previous layer)


we've learnt that a weight will learn slowly if either the input neuron is low-activation, or if the output neuron has saturated, i.e., is either high- or low-activation. 

http://neuralnetworksanddeeplearning.com/images/tikz21.png


Cross entropy is a specific cost function
Cross-entropy cost fn: 
	C=−1n∑x[yln(a) + (1−y)ln(1−a)]
		because `0<a<1, ln(a) and ln(1-a)` are both negative

exercise: compute sigma'(z) = sigma(z)(1-sigma(z))
	`(1+e^-z)^-1
	-1(1+e^-z)^-2(-z)(e^-z)`
		trick is to add and subtract 1 to the numerator after integrating


The obvious way to detect overfitting is to use the approach above, keeping track of accuracy on the test data as our network trains. If we see that the accuracy on the test data is no longer improving, then we should stop training. Of course, strictly speaking, this is not necessarily a sign of overfitting. It might be that accuracy on the test data and the training data both stop improving at the same time. 

set hyperparameters using validation data so we odn't overfit to test_data

Nowadays use almost entirely RELUs: y=max(X,0) (aka replace negatives w/ 0)

jupyter notebook, hitting tab will list all methods that start with that letter (learn.p press tab)
	hitting shift tab will tell all you all the arguments you need for that method
	ex: np.exp() pressing shift+tab
		pressing shift+tab+tab will show documentation
		?.np.exp() will bring up the documentation in a window (shift+tab+tab+tab will do the same)
	??.np.exp() will pop up the source code
	h in jupyter notebook brings up keyboard shortcuts!
	