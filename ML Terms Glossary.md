# Models

fantastic cheat [sheets](https://stanford.edu/~shervine/teaching/)

List of existing/famous models, and common ML terms:
- CIFAR10
- CKA: Centered Kernel Alignment
- Linear Regression
- CCA: Canonical Correlation Analysis
	- SVCCA: Singular Vector CCA
	- Projection Weighted CCA
- GAN: Generated Adversarial Network
<p>Used to </p>
- CycleGAN
- seq2seq
- LSTM
- non-autoregressive
- Deep Voice 3
- CNN: Convolutional Neural Net
- RNN: 
- WaveNet
- Autoencoder 
- Attention
- RELU: REctified Linear Unit - y=max(x,0), aka replace negative values w/ 0, aka flatten a line to y=0 where y would be negative, aka hockey stick
- sigmoid: squishes to [0,1]
- tanh: squishes to [-1,1]
- binary_crossentropy
- adadelta
- softmax: aka basically `max()`
- RMSProp
- MaxPooling
- Conv2D

### Random Interesting [Repo][gitaditya]
Also has a great example [website][aditya]
Regression Algorithms:
- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tress Regressor
- K-Nearest Neighbors Regressor
- Neural Networks

Classification Algorithms:
- Binary Logistic Regression
- Softmax Regression
- Decision Tree Classifier
- Adaboost Binary Classifier
- K-Nearest Neighbors Classifier
- Neural Network Classifier

Unsupervised Learning:
- K-Means
- Gaussian Mixtur Models
- Variational Autoencoder


Stats terms:
- bias
- accuracy
- error



ML Glossary

Preprocessing:
Callbacks

Layers:
Dense
Flatten
Conv2D
Maxpooling

Optimizers/activation fn:
RMSProp
adadelta
sigmoid
tanh
softmax

Loss terms:
RMSProp
[wiki](https://en.wikipedia.org/wiki/Stochastic_gradient_descent#RMSProp)
binary_crossentropy
SGD
Adam
MSE


For binary class, can you train to create Conv2D's that realize some item in an img that ID's 0 but not 1? As in create Conv that shows up on high % of 0's, then run that conv against 1's and if real low accuracy on 1's then have an overweight/override? To some extent that's what ML is already doing, just with weighting. Seems like you could build rules/interpretations on top, or be able to pull out "features". Ex, horse ears vs human. If you see any conv matching that large pointy ear (in comparison to rest of body and to body location [so you wouldn't mistake a nose])

If loss (concurrently w/ accuracy) increases drastically would you back it out?

[aditya]: https://www.adityavyas17.com 'Example Personal ML Site'
[gitaditya]: https://github.com/aditya1702/Machine-Learning-and-Data-Science/tree/master/Implementation%20of%20Machine%20Learning%20Algorithms 'ML Algos w/ only Numpy and Pandas'