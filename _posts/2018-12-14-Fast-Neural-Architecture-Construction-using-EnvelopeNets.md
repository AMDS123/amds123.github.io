---
layout: post
title: "Fast Neural Architecture Construction using EnvelopeNets"
date: 2018-12-14 00:34:40
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning CNN Image_Classification Classification
author: Purushotham Kamath, Abhishek Singh, Debo Dutta
mathjax: true
---

* content
{:toc}

##### Abstract
Fast Neural Architecture Construction (NAC) is a method to construct deep network architectures by pruning and expansion of a base network. In recent years, several automated search methods for neural network architectures have been proposed using methods such as evolutionary algorithms and reinforcement learning. These methods use a single scalar objective function (usually accuracy) that is evaluated after a full training and evaluation cycle. In contrast NAC directly compares the utility of different filters using statistics derived from filter featuremaps reach a state where the utility of different filters within a network can be compared and hence can be used to construct networks. The training epochs needed for filters within a network to reach this state is much less than the training epochs needed for the accuracy of a network to stabilize. NAC exploits this finding to construct convolutional neural nets (CNNs) with close to state of the art accuracy, in &lt; 1 GPU day, faster than most of the current neural architecture search methods. The constructed networks show close to state of the art performance on the image classification problem on well known datasets (CIFAR-10, ImageNet) and consistently show better performance than hand constructed and randomly generated networks of the same depth, operators and approximately the same number of parameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.06744](http://arxiv.org/abs/1803.06744)

##### PDF
[http://arxiv.org/pdf/1803.06744](http://arxiv.org/pdf/1803.06744)

