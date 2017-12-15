---
layout: post
title: "A Riemannian Network for SPD Matrix Learning"
date: 2016-12-22 15:43:55
categories: arXiv_CV
tags: arXiv_CV Classification Gradient_Descent
author: Zhiwu Huang, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Symmetric Positive Definite (SPD) matrix learning methods have become popular in many image and video processing tasks, thanks to their ability to learn appropriate statistical representations while respecting Riemannian geometry of underlying SPD manifolds. In this paper we build a Riemannian network architecture to open up a new direction of SPD matrix non-linear learning in a deep model. In particular, we devise bilinear mapping layers to transform input SPD matrices to more desirable SPD matrices, exploit eigenvalue rectification layers to apply a non-linear activation function to the new SPD matrices, and design an eigenvalue logarithm layer to perform Riemannian computing on the resulting SPD matrices for regular output layers. For training the proposed deep network, we exploit a new backpropagation with a variant of stochastic gradient descent on Stiefel manifolds to update the structured connection weights and the involved SPD matrix data. We show through experiments that the proposed SPD matrix network can be simply trained and outperform existing SPD matrix learning and state-of-the-art methods in three typical visual classification tasks.

##### Abstract (translated by Google)
对称正定（SPD）矩阵学习方法已经在许多图像和视频处理任务中变得流行，这归功于其能够学习适当的统计表示，同时尊重底层SPD流形的黎曼几何。在本文中，我们构建了一个黎曼网络体系结构，在深度模型中开创了SPD矩阵非线性学习的新方向。具体来说，我们设计了双线性映射层，将输入SPD矩阵转换为更理想的SPD矩阵，利用特征值整流层将新线性激励函数应用于新的SPD矩阵，并设计特征值对数层对结果进行黎曼计算用于常规输出层的SPD矩阵。为了训练提出的深度网络，我们利用Stiefel流形上随机梯度下降的变体的新反向传播来更新结构化连接权重和所涉及的SPD矩阵数据。我们通过实验表明，所提出的SPD矩阵网络可以被简单地训练并且在三个典型的视觉分类任务中优于现有的SPD矩阵学习和最先进的方法。

##### URL
[https://arxiv.org/abs/1608.04233](https://arxiv.org/abs/1608.04233)

##### PDF
[https://arxiv.org/pdf/1608.04233](https://arxiv.org/pdf/1608.04233)

