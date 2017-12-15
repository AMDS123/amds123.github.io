---
layout: post
title: "Semi-supervised learning of local structured output predictors"
date: 2016-04-11 15:53:04
categories: arXiv_CV
tags: arXiv_CV Prediction Gradient_Descent
author: Xin Du
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study the problem of semi-supervised structured output prediction, which aims to learn predictors for structured outputs, such as sequences, tree nodes, vectors, etc., from a set of data points of both input-output pairs and single inputs without outputs. The traditional methods to solve this problem usually learns one single predictor for all the data points, and ignores the variety of the different data points. Different parts of the data set may have different local distributions, and requires different optimal local predictors. To overcome this disadvantage of existing methods, we propose to learn different local predictors for neighborhoods of different data points, and the missing structured outputs simultaneously. In the neighborhood of each data point, we proposed to learn a linear predictor by minimizing both the complexity of the predictor and the upper bound of the structured prediction loss. The minimization is conducted by gradient descent algorithms. Experiments over four benchmark data sets, including DDSM mammography medical images, SUN natural image data set, Cora research paper data set, and Spanish news wire article sentence data set, show the advantages of the proposed method.

##### Abstract (translated by Google)
在本文中，我们研究半监督结构化输出预测的问题，其目的是从输入输出对的一组数据点学习结构化输出的预测结果，如序列，树节点，向量等。单输入无输出。解决这个问题的传统方法通常是对所有数据点学习一个单独的预测器，忽略不同数据点的多样性。数据集的不同部分可能有不同的局部分布，需要不同的最优局部预测。为了克服现有方法的这个缺点，我们建议学习不同数据点邻域的不同局部预测因子，同时学习缺失的结构化输出。在每个数据点附近，我们提出通过最小化预测器的复杂性和结构化预测损失的上限来学习线性预测器。最小化是通过梯度下降算法进行的。对DDSM乳腺X线摄影医学图像，SUN自然图像数据集，Cora研究论文数据集，西班牙新闻文章句子数据集等4个基准数据集进行的实验表明了该方法的优越性。

##### URL
[https://arxiv.org/abs/1604.03010](https://arxiv.org/abs/1604.03010)

##### PDF
[https://arxiv.org/pdf/1604.03010](https://arxiv.org/pdf/1604.03010)

