---
layout: post
title: "Compression of Fully-Connected Layer in Neural Network by Kronecker Product"
date: 2015-07-22 11:59:08
categories: arXiv_CV
tags: arXiv_CV Prediction Recognition
author: Shuchang Zhou, Jia-Nan Wu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose and study a technique to reduce the number of parameters and computation time in fully-connected layers of neural networks using Kronecker product, at a mild cost of the prediction quality. The technique proceeds by replacing Fully-Connected layers with so-called Kronecker Fully-Connected layers, where the weight matrices of the FC layers are approximated by linear combinations of multiple Kronecker products of smaller matrices. In particular, given a model trained on SVHN dataset, we are able to construct a new KFC model with 73\% reduction in total number of parameters, while the error only rises mildly. In contrast, using low-rank method can only achieve 35\% reduction in total number of parameters given similar quality degradation allowance. If we only compare the KFC layer with its counterpart fully-connected layer, the reduction in the number of parameters exceeds 99\%. The amount of computation is also reduced as we replace matrix product of the large matrices in FC layers with matrix products of a few smaller matrices in KFC layers. Further experiments on MNIST, SVHN and some Chinese Character recognition models also demonstrate effectiveness of our technique.

##### Abstract (translated by Google)
在本文中，我们提出并研究了一种技术，以预测质量的温和代价，使用Kronecker乘积来减少神经网络的全连接层中的参数数量和计算时间。该技术通过用所谓的克罗内克全连接层代替完全连接层来实现，其中FC层的权重矩阵通过较小矩阵的多克罗内克积的线性组合近似。特别是，对于SVHN数据集的训练模型，我们可以构建一个新的KFC模型，参数总数减少73％，而误差只是轻微上升。相比之下，使用低秩方法只能达到相似的质量退化允许的参数总数的35％的减少。如果我们只比较KFC层与其对应的完全连接层，则参数数目的减少超过99％。由于我们用KFC层中几个较小矩阵的矩阵积代替FC层中的大矩阵的矩阵积，所以计算量也减少了。在MNIST，SVHN和一些汉字识别模型上的进一步实验也证明了我们的技术的有效性。

##### URL
[https://arxiv.org/abs/1507.05775](https://arxiv.org/abs/1507.05775)

##### PDF
[https://arxiv.org/pdf/1507.05775](https://arxiv.org/pdf/1507.05775)

