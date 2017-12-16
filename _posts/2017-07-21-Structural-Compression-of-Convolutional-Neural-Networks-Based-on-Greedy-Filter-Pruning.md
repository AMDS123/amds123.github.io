---
layout: post
title: "Structural Compression of Convolutional Neural Networks Based on Greedy Filter Pruning"
date: 2017-07-21 22:32:20
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Classification
author: Reza Abbasi-Asl, Bin Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have state-of-the-art performance on many problems in machine vision. However, networks with superior performance often have millions of weights so that it is difficult or impossible to use CNNs on computationally limited devices or to humanly interpret them. A myriad of CNN compression approaches have been proposed and they involve pruning and compressing the weights and filters. In this article, we introduce a greedy structural compression scheme that prunes filters in a trained CNN. We define a filter importance index equal to the classification accuracy reduction (CAR) of the network after pruning that filter (similarly defined as RAR for regression). We then iteratively prune filters based on the CAR index. This algorithm achieves substantially higher classification accuracy in AlexNet compared to other structural compression schemes that prune filters. Pruning half of the filters in the first or second layer of AlexNet, our CAR algorithm achieves 26% and 20% higher classification accuracies respectively, compared to the best benchmark filter pruning scheme. Our CAR algorithm, combined with further weight pruning and compressing, reduces the size of first or second convolutional layer in AlexNet by a factor of 42, while achieving close to original classification accuracy through retraining (or fine-tuning) network. Finally, we demonstrate the interpretability of CAR-compressed CNNs by showing that our algorithm prunes filters with visually redundant functionalities. In fact, out of top 20 CAR-pruned filters in AlexNet, 17 of them in the first layer and 14 of them in the second layer are color-selective filters as opposed to shape-selective filters. To our knowledge, this is the first reported result on the connection between compression and interpretability of CNNs.

##### Abstract (translated by Google)
卷积神经网络（CNN）在机器视觉的许多问题上具有最先进的性能。然而，性能优越的网络往往具有数百万的权重，因此在计算受限的设备上使用CNN是困难的或不可能的，或者是人为地解释它们。已经提出了无数的CNN压缩方法，它们涉及修剪和压缩权重和滤波器。在这篇文章中，我们介绍一个贪婪的结构压缩方案，在训练有素的CNN中修剪过滤器。我们定义一个滤波器重要性指数，等于网络的分类准确性降低（CAR）后，修剪该滤波器（类似地定义为回归的RAR）。然后，我们基于CAR索引迭代地修剪过滤器。与其他结构压缩方案相比，该算法在AlexNet中实现了更高的分类精度。在第一层或第二层AlexNet中修剪一半的滤波器，与最好的基准滤波器修剪方案相比，我们的CAR算法分别实现了26％和20％的分类精度。我们的CAR算法结合进一步的权重修剪和压缩，将AlexNet中第一个或第二个卷积层的大小减小了42倍，同时通过重新训练（或微调）网络实现了接近原始分类精度。最后，我们通过显示我们的算法修剪过滤器的视觉冗余功能来演示CAR压缩的CNN的可解释性。事实上，在AlexNet中，前20个CAR-pruned过滤器中，其中第一层中的17个和第二层中的14个是颜色选择性过滤器，而不是形状选择性过滤器。据我们所知，这是有关CNN压缩和解释性之间关系的第一个报告结果。

##### URL
[https://arxiv.org/abs/1705.07356](https://arxiv.org/abs/1705.07356)

##### PDF
[https://arxiv.org/pdf/1705.07356](https://arxiv.org/pdf/1705.07356)

