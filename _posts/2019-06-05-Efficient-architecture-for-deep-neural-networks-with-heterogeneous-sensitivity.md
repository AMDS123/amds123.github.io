---
layout: post
title: "Efficient architecture for deep neural networks with heterogeneous sensitivity"
date: 2019-06-05 02:40:15
categories: arXiv_CV
tags: arXiv_CV Regularization Object_Detection Optimization Detection Recognition
author: Hyunjoong Cho, Jinhyeok Jang, Chanhyeok Lee, Seungjoon Yang
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents a neural network that consists of nodes with heterogeneous sensitivity. Each node in a network is assigned a variable that determines the sensitivity with which it learns to perform a given task. The network is trained by a constrained optimization that maximizes the sparsity of the sensitivity variables while ensuring the network's performance. As a result, the network learns to perform a given task using only a small number of sensitive nodes. Insensitive nodes, the nodes with zero sensitivity, can be removed from a trained network to obtain a computationally efficient network. Removing zero-sensitivity nodes has no effect on the network's performance because the network has already been trained to perform the task without them. The regularization parameter used to solve the optimization problem is found simultaneously during the training of networks. To validate our approach, we design networks with computationally efficient architectures for various tasks such as autoregression, object recognition, facial expression recognition, and object detection using various datasets. In our experiments, the networks designed by the proposed method provide the same or higher performance but with far less computational complexity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.05358](http://arxiv.org/abs/1810.05358)

##### PDF
[http://arxiv.org/pdf/1810.05358](http://arxiv.org/pdf/1810.05358)

