---
layout: post
title: "Connectivity Learning in Multi-Branch Networks"
date: 2017-12-07 16:57:45
categories: arXiv_CV
tags: arXiv_CV CNN
author: Karim Ahmed, Lorenzo Torresani
mathjax: true
---

* content
{:toc}

##### Abstract
While much of the work in the design of convolutional networks over the last five years has revolved around the empirical investigation of the importance of depth, filter sizes, and number of feature channels, recent studies have shown that branching, i.e., splitting the computation along parallel but distinct threads and then aggregating their outputs, represents a new promising dimension for significant improvements in performance. To combat the complexity of design choices in multi-branch architectures, prior work has adopted simple strategies, such as a fixed branching factor, the same input being fed to all parallel branches, and an additive combination of the outputs produced by all branches at aggregation points. 
 In this work we remove these predefined choices and propose an algorithm to learn the connections between branches in the network. Instead of being chosen a priori by the human designer, the multi-branch connectivity is learned simultaneously with the weights of the network by optimizing a single loss function defined with respect to the end task. We demonstrate our approach on the problem of multi-class image classification using three different datasets where it yields consistently higher accuracy compared to the state-of-the-art "ResNeXt" multi-branch network given the same learning capacity.

##### Abstract (translated by Google)
虽然过去五年中卷积网络设计的许多工作围绕着对深度，滤波器大小和特征信道数目的重要性的实证研究，最近的研究表明分支，即将计算分开并行但不同的线程，然后汇总它们的输出，代表了显着提高性能的新的有希望的维度。为了克服多分支体系结构中设计选择的复杂性，以前的工作采用了简单的策略，例如固定的分支因子，向所有并行分支输入相同的输入，以及由所有分支产生的输出点。
 在这项工作中，我们删除这些预定义的选择，并提出一个算法来学习网络中分支之间的连接。通过优化相对于结束任务定义的单个损失函数，而不是由人类设计者先验地选择，多支路连接性与网络的权重同时学习。我们证明了我们在多类图像分类问题上的方法，使用三个不同的数据集，在给定相同学习能力的情况下，与最先进的“ResNeXt”多分支网络相比，它可以产生始终如一的高精度。

##### URL
[http://arxiv.org/abs/1709.09582](http://arxiv.org/abs/1709.09582)

##### PDF
[http://arxiv.org/pdf/1709.09582](http://arxiv.org/pdf/1709.09582)

