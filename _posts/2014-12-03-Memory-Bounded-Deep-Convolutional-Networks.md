---
layout: post
title: "Memory Bounded Deep Convolutional Networks"
date: 2014-12-03 19:08:38
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse CNN Gradient_Descent
author: Maxwell D. Collins, Pushmeet Kohli
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we investigate the use of sparsity-inducing regularizers during training of Convolution Neural Networks (CNNs). These regularizers encourage that fewer connections in the convolution and fully connected layers take non-zero values and in effect result in sparse connectivity between hidden units in the deep network. This in turn reduces the memory and runtime cost involved in deploying the learned CNNs. We show that training with such regularization can still be performed using stochastic gradient descent implying that it can be used easily in existing codebases. Experimental evaluation of our approach on MNIST, CIFAR, and ImageNet datasets shows that our regularizers can result in dramatic reductions in memory requirements. For instance, when applied on AlexNet, our method can reduce the memory consumption by a factor of four with minimal loss in accuracy.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1412.1442](https://arxiv.org/abs/1412.1442)

##### PDF
[https://arxiv.org/pdf/1412.1442](https://arxiv.org/pdf/1412.1442)

