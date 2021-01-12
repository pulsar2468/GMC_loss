# GMC Loss
Our intuition is based on the idea that data might follow a multimodal distribution.
In this repository, we propose a loss function called Gaussian Mixture’s Centers loss (GMC) leveraging on the idea that data follow multiple unimodal distributions and try to reduce variances considering many centers per class.
It increases the discrimination capability to identify class similarity structures.
Using jointly Cross-Entropy and GMC loss we improve the learning generalization model overcoming the performance of the baseline in several use cases.
We demonstrate by experiments our method's effectiveness on well-known CIFAR10/100 and Imagenet (ILSVRC-2012) datasets.
