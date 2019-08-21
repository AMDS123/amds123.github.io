---
layout: post
title: "A Unified Approximation Framework for Compressing and Accelerating Deep Neural Networks"
date: 2019-08-20 03:06:00
categories: arXiv_AI
tags: arXiv_AI Sparse CNN Image_Classification Optimization Inference Classification
author: Yuzhe Ma, Ran Chen, Wei Li, Fanhua Shang, Wenjian Yu, Minsik Cho, Bei Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) have achieved significant success in a variety of real world applications, i.e., image classification. However, tons of parameters in the networks restrict the efficiency of neural networks due to the large model size and the intensive computation. To address this issue, various approximation techniques have been investigated, which seek for a light weighted network with little performance degradation in exchange of smaller model size or faster inference. Both low-rankness and sparsity are appealing properties for the network approximation. In this paper we propose a unified framework to compress the convolutional neural networks (CNNs) by combining these two properties, while taking the nonlinear activation into consideration. Each layer in the network is approximated by the sum of a structured sparse component and a low-rank component, which is formulated as an optimization problem. Then, an extended version of alternating direction method of multipliers (ADMM) with guaranteed convergence is presented to solve the relaxed optimization problem. Experiments are carried out on VGG-16, AlexNet and GoogLeNet with large image classification datasets. The results outperform previous work in terms of accuracy degradation, compression rate and speedup ratio. The proposed method is able to remarkably compress the model (with up to 4.9x reduction of parameters) at a cost of little loss or without loss on accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.10119](http://arxiv.org/abs/1807.10119)

##### PDF
[http://arxiv.org/pdf/1807.10119](http://arxiv.org/pdf/1807.10119)

