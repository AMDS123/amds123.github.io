---
layout: post
title: "Low-rank Bilinear Pooling for Fine-Grained Classification"
date: 2016-11-30 01:30:12
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Shu Kong, Charless Fowlkes
mathjax: true
---

* content
{:toc}

##### Abstract
Pooling second-order local feature statistics to form a high-dimensional bilinear feature has been shown to achieve state-of-the-art performance on a variety of fine-grained classification tasks. To address the computational demands of high feature dimensionality, we propose to represent the covariance features as a matrix and apply a low-rank bilinear classifier. The resulting classifier can be evaluated without explicitly computing the bilinear feature map which allows for a large reduction in the compute time as well as decreasing the effective number of parameters to be learned. To further compress the model, we propose classifier co-decomposition that factorizes the collection of bilinear classifiers into a common factor and compact per-class terms. The co-decomposition idea can be deployed through two convolutional layers and trained in an end-to-end architecture. We suggest a simple yet effective initialization that avoids explicitly first training and factorizing the larger bilinear classifiers. Through extensive experiments, we show that our model achieves state-of-the-art performance on several public datasets for fine-grained classification trained with only category labels. Importantly, our final model is an order of magnitude smaller than the recently proposed compact bilinear model, and three orders smaller than the standard bilinear CNN model.

##### Abstract (translated by Google)
汇集二阶局部特征统计以形成高维双线性特征已被证明在各种细粒度的分类任务上实现了最先进的性能。为了解决高维特征的计算需求，我们提出将协方差特征表示为矩阵并应用低秩双线性分类器。可以在不明确计算双线性特征映射的情况下评估得到的分类器，该双线性特征映射允许计算时间的大量减少以及减少要学习的参数的有效数量。为了进一步压缩模型，我们提出了分类器的协同分解，将双线性分类器的集合分解成一个公共因子和紧凑的每类术语。协同分解的思想可以通过两个卷积层进行部署，并在端到端的体系结构中进行训练。我们建议一个简单而有效的初始化，避免明确的首先训练和分解更大的双线性分类器。通过广泛的实验，我们证明了我们的模型在几个公共数据集上实现了最先进的性能，只用类别标签进行细粒度分类。重要的是，我们的最终模型比最近提出的紧凑双线性模型小一个数量级，比标准双线性CNN模型小三个数量级。

##### URL
[https://arxiv.org/abs/1611.05109](https://arxiv.org/abs/1611.05109)

##### PDF
[https://arxiv.org/pdf/1611.05109](https://arxiv.org/pdf/1611.05109)

