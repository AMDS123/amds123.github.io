---
layout: post
title: "The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks"
date: 2018-11-27 20:03:01
categories: arXiv_AI
tags: arXiv_AI Sparse CNN Inference
author: Jonathan Frankle, Michael Carbin
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network pruning techniques can reduce the parameter counts of trained networks by over 90%, decreasing storage requirements and improving computational performance of inference without compromising accuracy. However, contemporary experience is that the sparse architectures produced by pruning are difficult to train from the start, which would similarly improve training performance. 
 We find that a standard technique for pruning weights naturally uncovers subnetworks whose initializations made them capable of training effectively. Based on these results, we articulate the "lottery ticket hypothesis": dense, randomly-initialized feed-forward networks contain subnetworks ("winning tickets") that - when trained in isolation - arrive at comparable test accuracy in a comparable number of iterations. The winning tickets we find have won the initialization lottery: their connections have initial weights that make training particularly effective. 
 We present an algorithm to identify winning tickets and a series of experiments that support the lottery ticket hypothesis and the importance of these fortuitous initializations. We consistently find winning tickets that are less than 10-20% of the size of several fully-connected and convolutional feed-forward architectures for MNIST and CIFAR10. Furthermore, the winning tickets we find above that size learn faster than the original network and exhibit higher test accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.03635](http://arxiv.org/abs/1803.03635)

##### PDF
[http://arxiv.org/pdf/1803.03635](http://arxiv.org/pdf/1803.03635)

