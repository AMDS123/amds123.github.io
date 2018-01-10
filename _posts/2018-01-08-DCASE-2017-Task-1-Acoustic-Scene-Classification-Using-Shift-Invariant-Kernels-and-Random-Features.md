---
layout: post
title: "DCASE 2017 Task 1: Acoustic Scene Classification Using Shift-Invariant Kernels and Random Features"
date: 2018-01-08 21:12:49
categories: arXiv_SD
tags: arXiv_SD Classification
author: Abelino Jimenez, Benjamin Elizalde, Bhiksha Raj
mathjax: true
---

* content
{:toc}

##### Abstract
Acoustic scene recordings are represented by different types of handcrafted or Neural Network-derived features. These features, typically of thousands of dimensions, are classified in state of the art approaches using kernel machines, such as the Support Vector Machines (SVM). However, the complexity of training these methods increases with the dimensionality of these input features and the size of the dataset. A solution is to map the input features to a randomized lower-dimensional feature space. The resulting random features can approximate non-linear kernels with faster linear kernel computation. In this work, we computed a set of 6,553 input features and used them to compute random features to approximate three types of kernels, Gaussian, Laplacian and Cauchy. We compared their performance using an SVM in the context of the DCASE Task 1 - Acoustic Scene Classification. Experiments show that both, input and random features outperformed the DCASE baseline by an absolute 4%. Moreover, the random features reduced the dimensionality of the input by more than three times with minimal loss of performance and by more than six times and still outperformed the baseline. Hence, random features could be employed by state of the art approaches to compute low-storage features and perform faster kernel computations.

##### Abstract (translated by Google)
声场记录由不同类型的手工或神经网络派生特征表示。典型地具有数千维度的这些特征被分类为使用诸如支持向量机（SVM）的核心机器的现有技术方法。然而，训练这些方法的复杂性随着这些输入特征的维度和数据集的大小而增加。一种解决方案是将输入特征映射到随机化的低维特征空间。由此产生的随机特征可以用更快的线性内核计算来近似非线性内核。在这项工作中，我们计算了一组6,553个输入特征，并用它们来计算随机特征来近似三种类型的内核，高斯，拉普拉斯和柯西。在DCASE任务1  - 声场景分类的背景下，我们使用SVM比较了他们的性能。实验表明，输入和随机特征均优于DCASE基线绝对4％。此外，随机特征将输入的维度降低了三倍以上，性能损失最小，超过六倍，仍然超过了基线。因此，现有技术方法可以采用随机特征来计算低存储特征并执行更快的内核计算。

##### URL
[http://arxiv.org/abs/1801.02690](http://arxiv.org/abs/1801.02690)

##### PDF
[http://arxiv.org/pdf/1801.02690](http://arxiv.org/pdf/1801.02690)

