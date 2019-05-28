# [Chapter 1][dl1] - Introduction

## 1.2.2 - Increasing Dataset Sizes
Big data revolution allows for handling more data and "has made machine learning much easier because the key burden of statistical estimation - generalizing well to new data after observing only a small amount of data - has been considerably lightened" [dl1][pg 20]. This increase in data allows for less skill required on the part of the modeler. The algorithms achieving success today were very similar to the algos from the 80s that couldn't handle toy problems.

## 1.2.3 - Increasing Model Sizes
After introducing hidden layers, Artificial Neural Nets (ANNs) have doubled in size every few years in step with faster computing, more computational memory, and larger datasets. "In retrospect, it's not particularly surprising that neural networks with fewer neurons than a leech were unable to solve sophisticated artiﬁcial intelligence problems." [dl1][pg21]. 2016's NN sizes are still smaller than the nervous system of frogs. 

For some perspective, humans and cats have \~10,000 connections per neuron, mice 1000, and fruit flies 100. Human neural networks have \~10^11 neurons, frogs 10^7, and ants 10^5 (pg 23).

## 1.2.4 - Increasing Accuracy, Complexity, and Real-World Impact
CNNs burst on the scene by dramatically increasing the accuracy for the ILSVRC challenge in 2012, and since have brought the error rate down to 1.3% (correct category in the first 5 entries of list all but 1.3% of test examples).

Reinforcement Learning - "an autonomous agent must learn to perform a task by trial and error, without any guidance from the human operator," significantly improved performance of RL for robotics.

# Summary
Deep learning is a subset of Machine Learning. It has many useful applications in _soft programming_ as I'll call it. _Soft programming_ being the opposite of hard-coded rules in traditional programming. Where before you'd have to explicitly declare everything you wanted your program to do, and image detection would involve very convoluted ways of defining edge cases of say a cat, now you can train a computer to detect cat images without having to go into the nitty gritty.

How to represent data is very important for pulling out the important features. Deep learning chains simple concepts together, from visible input layer through hidden layers back out to a visible output layer, and with recursion trains them to accurately perform complex tasks. Similar to a euclidean estimator.


[dl1]: https://www.deeplearningbook.org/contents/intro.html 'chapter 1'