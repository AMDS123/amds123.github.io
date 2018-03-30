---
layout: post
title: "Feed-forward Uncertainty Propagation in Belief and Neural Networks"
date: 2018-03-28 13:26:47
categories: arXiv_CV
tags: arXiv_CV Knowledge Inference
author: Alexander Shekhovtsov, Boris Flach, Michal Busta
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a feed-forward inference method applicable to belief and neural networks. In a belief network, the method estimates an approximate factorized posterior of all hidden units given the input. In neural networks the method propagates uncertainty of the input through all the layers. In neural networks with injected noise, the method analytically takes into account uncertainties resulting from this noise. Such feed-forward analytic propagation is differentiable in parameters and can be trained end-to-end. Compared to standard NN, which can be viewed as propagating only the means, we propagate the mean and variance. The method can be useful in all scenarios that require knowledge of the neuron statistics, e.g. when dealing with uncertain inputs, considering sigmoid activations as probabilities of Bernoulli units, training the models regularized by injected noise (dropout) or estimating activation statistics over the dataset (as needed for normalization methods). In the experiments we show the possible utility of the method in all these tasks as well as its current limitations.

##### Abstract (translated by Google)
我们提出了一种适用于信念和神经网络的前馈推理方法。在信念网络中，该方法估计给定输入的所有隐藏单元的近似因式分解后验。在神经网络中，该方法传播通过所有层的输入的不确定性。在具有注入噪声的神经网络中，该方法以分析方式考虑到由该噪声导致的不确定性。这种前馈分析传播的参数是可区分的，可以进行端对端培训。与标准NN相比，它可以被看作只传播手段，我们传播均值和方差。该方法可用于需要神经元统计学知识的所有场景，例如，当处理不确定的输入时，考虑S形激活作为伯努利单位的概率，训练通过注入噪声（丢失）规则化的模型或估计数据集上的激活统计量（根据归一化方法的需要）。在实验中，我们展示了该方法在所有这些任务中的可能效用以及目前的局限性。

##### URL
[https://arxiv.org/abs/1803.10590](https://arxiv.org/abs/1803.10590)

##### PDF
[https://arxiv.org/pdf/1803.10590](https://arxiv.org/pdf/1803.10590)

