---
layout: post
title: "Learning Activation Functions: A new paradigm for understanding Neural Networks"
date: 2019-07-08 14:56:10
categories: arXiv_CV
tags: arXiv_CV Optimization Deep_Learning
author: Mohit Goyal, Rajan Goyal, Brejesh Lall
mathjax: true
---

* content
{:toc}

##### Abstract
The scope of research in the domain of activation functions remains limited and centered around improving the ease of optimization or generalization quality of neural networks (NNs). However, to develop a deeper understanding of deep learning, it becomes important to look at the non linear component of NNs more carefully. In this paper, we aim to provide a generic form of activation function along with appropriate mathematical grounding so as to allow for insights into the working of NNs in future. We propose ``Self-Learnable Activation Functions'' (SLAF), which are learned during training and are capable of approximating most of the existing activation functions. SLAF is given as a weighted sum of pre-defined basis elements which can serve for a good approximation of the optimal activation function. The coefficients for these basis elements allow a search in the entire space of continuous functions (consisting of all the conventional activations). We propose various training routines which can be used to achieve performance with SLAF equipped neural networks (SLNNs). We prove that SLNNs can approximate any neural network with lipschitz continuous activations, to any arbitrary error highlighting their capacity and possible equivalence with standard NNs. Also, SLNNs can be completely represented as a collections of finite degree polynomial upto the very last layer obviating several hyper parameters like width and depth. Since the optimization of SLNNs is still a challenge, we show that using SLAF along with standard activations (like ReLU) can provide performance improvements with only a small increase in number of parameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09529](http://arxiv.org/abs/1906.09529)

##### PDF
[http://arxiv.org/pdf/1906.09529](http://arxiv.org/pdf/1906.09529)

