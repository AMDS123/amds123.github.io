---
layout: post
title: "Approximate Fisher Kernels of non-iid Image Models for Image Categorization"
date: 2015-10-03 19:35:38
categories: arXiv_CV
tags: arXiv_CV
author: Ramazan Gokberk Cinbis, Jakob Verbeek, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
The bag-of-words (BoW) model treats images as sets of local descriptors and represents them by visual word histograms. The Fisher vector (FV) representation extends BoW, by considering the first and second order statistics of local descriptors. In both representations local descriptors are assumed to be identically and independently distributed (iid), which is a poor assumption from a modeling perspective. It has been experimentally observed that the performance of BoW and FV representations can be improved by employing discounting transformations such as power normalization. In this paper, we introduce non-iid models by treating the model parameters as latent variables which are integrated out, rendering all local regions dependent. Using the Fisher kernel principle we encode an image by the gradient of the data log-likelihood w.r.t. the model hyper-parameters. Our models naturally generate discounting effects in the representations; suggesting that such transformations have proven successful because they closely correspond to the representations obtained for non-iid models. To enable tractable computation, we rely on variational free-energy bounds to learn the hyper-parameters and to compute approximate Fisher kernels. Our experimental evaluation results validate that our models lead to performance improvements comparable to using power normalization, as employed in state-of-the-art feature aggregation methods.

##### Abstract (translated by Google)
词袋（BoW）模型将图像视为局部描述符的集合，并通过视觉词直方图来表示它们。 Fisher矢量（FV）表示通过考虑局部描述符的一阶和二阶统计量来扩展BoW。在这两个表示中，局部描述符被假定为相同和独立分布（iid），从建模的角度来看这是一个糟糕的假设。已经通过实验观察到，BoW和FV表示的性能可以通过使用诸如功率归一化的折扣转换来改进。在本文中，我们引入非iid模型，将模型参数视为被集成的潜在变量，使所有局部区域都相关。使用Fisher核心原理，我们用数据对数似然函数w.r.t的梯度对图像进行编码。模型超参数。我们的模型在表示中自然产生折扣效应;这表明这样的转换已经被证明是成功的，因为它们与非iid模型获得的表示紧密相关。为了使易处理的计算，我们依靠变分自由能边界来学习超参数和计算近似Fisher核。我们的实验评估结果验证了我们的模型导致性能改进与使用功率归一化相当，如用于最先进的功能聚合方法。

##### URL
[https://arxiv.org/abs/1510.00857](https://arxiv.org/abs/1510.00857)

##### PDF
[https://arxiv.org/pdf/1510.00857](https://arxiv.org/pdf/1510.00857)

