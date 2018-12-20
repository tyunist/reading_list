# reading_list

# NIPS 2018 
## A thoughtful summarization on poster sections
[NIPS/NeurIPS 2018: Best* of the First Two Poster Sessions](https://towardsdatascience.com/neurips-2018-reading-list-from-tue-poster-sessions-a-b-fce561e56be8?fbclid=IwAR0GiEyzd6Dh93_to3K3UCrUzRXFlkX1O8oaQrvMAf5lpPhbLf0fHC3n5tA) 

# Interesting papers 
## [An Intriguing Failing of Convolutional Neural Networks and the CoordConv Solution](https://eng.uber.com/coordconv/) \\ 
[pdf](https://arxiv.org/pdf/1807.03247.pdf)

## [How Does Batch Normalization Help Optimization?](http://papers.nips.cc/paper/7515-how-does-batch-normalization-help-optimization.pdf)
Batch Normalization (BatchNorm) is a widely adopted technique that enables faster and more stable training of deep neural networks (DNNs). Despite its pervasiveness, the exact reasons for BatchNorm’s effectiveness are still poorly understood. The popular belief is that this effectiveness stems from controlling the change of the layers’ input distributions during training to reduce the so-called “internal covariate shift”. In this work, we demonstrate that such distributional stability of layer inputs has little to do with the success of BatchNorm. Instead, we uncover a more fundamental impact of BatchNorm on the training process: it makes the optimization landscape significantly smoother. This smoothness induces a more predictive and stable behavior of the gradients, allowing for faster training.


## [On Neuronal Capacity](http://papers.nips.cc/paper/7999-on-neuronal-capacity.pdf)
We define the capacity of a learning machine to be the logarithm of the number (or volume) of the functions it can implement. We review known results, and derive new results, estimating the capacity of several neuronal models: linear and polynomial threshold gates, linear and polynomial threshold gates with constrained weights (binary weights, positive weights), and ReLU neurons. We also derive capacity estimates and bounds for fully recurrent networks and layered feedforward networks.
