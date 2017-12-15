---
layout: post
title: "Decision Forests, Convolutional Networks and the Models in-Between"
date: 2016-03-03 20:41:47
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Image_Classification Represenation_Learning Classification
author: Yani Ioannou, Duncan Robertson, Darko Zikic, Peter Kontschieder, Jamie Shotton, Matthew Brown, Antonio Criminisi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates the connections between two state of the art classifiers: decision forests (DFs, including decision jungles) and convolutional neural networks (CNNs). Decision forests are computationally efficient thanks to their conditional computation property (computation is confined to only a small region of the tree, the nodes along a single branch). CNNs achieve state of the art accuracy, thanks to their representation learning capabilities. We present a systematic analysis of how to fuse conditional computation with representation learning and achieve a continuum of hybrid models with different ratios of accuracy vs. efficiency. We call this new family of hybrid models conditional networks. Conditional networks can be thought of as: i) decision trees augmented with data transformation operators, or ii) CNNs, with block-diagonal sparse weight matrices, and explicit data routing functions. Experimental validation is performed on the common task of image classification on both the CIFAR and Imagenet datasets. Compared to state of the art CNNs, our hybrid models yield the same accuracy with a fraction of the compute cost and much smaller number of parameters.

##### Abstract (translated by Google)
本文研究两种最先进的分类器之间的联系：决策森林（DFs，包括决策丛林）和卷积神经网络（CNNs）。决策森林由于其条件计算属性而具有计算效率（计算仅限于树的一个小区域，即沿着一个分支的节点）。由于其代表性的学习能力，CNN达到了最先进的精确度。我们提出了一个系统的分析如何融合条件计算与表示学习，并实现了不同比例的准确性与效率的连续混合模型。我们称之为混合模型条件网络的新家族。有条件的网络可以被认为是：i）用数据变换算子增加的决策树，或ii）具有块对角稀疏加权矩阵的CNN，以及明确的数据路由功能。对CIFAR和Imagenet数据集上的图像分类常见任务进行实验验证。与现有技术的CNN相比，我们的混合模型具有相同的准确性，计算成本只有一小部分，参数数量少得多。

##### URL
[https://arxiv.org/abs/1603.01250](https://arxiv.org/abs/1603.01250)

##### PDF
[https://arxiv.org/pdf/1603.01250](https://arxiv.org/pdf/1603.01250)

