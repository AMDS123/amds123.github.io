---
layout: post
title: "Improved Bilinear Pooling with CNNs"
date: 2017-07-21 06:49:04
categories: arXiv_CV
tags: arXiv_CV CNN Classification VQA Recognition
author: Tsung-Yu Lin, Subhransu Maji
mathjax: true
---

* content
{:toc}

##### Abstract
Bilinear pooling of Convolutional Neural Network (CNN) features [22, 23], and their compact variants [10], have been shown to be effective at fine-grained recognition, scene categorization, texture recognition, and visual question-answering tasks among others. The resulting representation captures second-order statistics of convolutional features in a translationally invariant manner. In this paper we investigate various ways of normalizing these statistics to improve their representation power. In particular we find that the matrix square-root normalization offers significant improvements and outperforms alternative schemes such as the matrix logarithm normalization when combined with elementwise square-root and l2 normalization. This improves the accuracy by 2-3% on a range of fine-grained recognition datasets leading to a new state of the art. We also investigate how the accuracy of matrix function computations effect network training and evaluation. In particular we compare against a technique for estimating matrix square-root gradients via solving a Lyapunov equation that is more numerically accurate than computing gradients via a Singular Value Decomposition (SVD). We find that while SVD gradients are numerically inaccurate the overall effect on the final accuracy is negligible once boundary cases are handled carefully. We present an alternative scheme for computing gradients that is faster and yet it offers improvements over the baseline model. Finally we show that the matrix square-root computed approximately using a few Newton iterations is just as accurate for the classification task but allows an order-of-magnitude faster GPU implementation compared to SVD decomposition.

##### Abstract (translated by Google)
已经证明卷积神经网络（CNN）特征的双线性汇集[22,23]及其紧凑变体[10]在细粒度识别，场景分类，纹理识别和视觉问题回答任务。所得到的表示以平移不变的方式捕获卷积特征的二阶统计量。在本文中，我们调查了各种统计这些统计数据的方法，以提高他们的代表权。特别地，我们发现矩阵平方根归一化提供了显着的改进，并且优于矩阵对数归一化时的替代方案，其与元素平方根和归一化相结合。这提高了一系列细粒度识别数据集的精度2-3％，导致了最新的技术水平。我们也研究矩阵函数计算的准确性如何影响网络训练和评估。具体而言，我们通过求解比通过奇异值分解（SVD）计算梯度更精确的Lyapunov方程来比较用于估计矩阵平方根梯度的技术。我们发现尽管SVD梯度在数值上是不准确的，但一旦小心处理边界情况，对最终精度的整体影响可以忽略不计。我们提出了一个更快的计算梯度的替代方案，但它提供了比基线模型更好的改进。最后我们展示了近似使用几个牛顿迭代计算的矩阵平方根对于分类任务而言是一样准确的，但是与SVD分解相比，允许GPU实现的数量级更快。

##### URL
[https://arxiv.org/abs/1707.06772](https://arxiv.org/abs/1707.06772)

##### PDF
[https://arxiv.org/pdf/1707.06772](https://arxiv.org/pdf/1707.06772)

