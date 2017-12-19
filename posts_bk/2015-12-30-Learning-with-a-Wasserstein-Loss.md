---
layout: post
title: "Learning with a Wasserstein Loss"
date: 2015-12-30 01:08:11
categories: arXiv_CV
tags: arXiv_CV Regularization Prediction
author: Charlie Frogner, Chiyuan Zhang, Hossein Mobahi, Mauricio Araya-Polo, Tomaso Poggio
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to predict multi-label outputs is challenging, but in many problems there is a natural metric on the outputs that can be used to improve predictions. In this paper we develop a loss function for multi-label learning, based on the Wasserstein distance. The Wasserstein distance provides a natural notion of dissimilarity for probability measures. Although optimizing with respect to the exact Wasserstein distance is costly, recent work has described a regularized approximation that is efficiently computed. We describe an efficient learning algorithm based on this regularization, as well as a novel extension of the Wasserstein distance from probability measures to unnormalized measures. We also describe a statistical learning bound for the loss. The Wasserstein loss can encourage smoothness of the predictions with respect to a chosen metric on the output space. We demonstrate this property on a real-data tag prediction problem, using the Yahoo Flickr Creative Commons dataset, outperforming a baseline that doesn't use the metric.

##### Abstract (translated by Google)
学习预测多标签输出是具有挑战性的，但是在许多问题中，输出的自然度量可用于改进预测。在本文中，我们基于Wasserstein距离开发了多标签学习的损失函数。 Wasserstein距离为概率测度提供了一个自然的不相似的概念。尽管关于确切的Wasserstein距离的优化是昂贵的，但是最近的工作已经描述了有效计算的正则化近似。我们描述了基于这种正则化的高效学习算法，以及从概率测量到非标准化测量的Wasserstein距离的新颖扩展。我们还描述了一个统计学习的损失界限。 Wasserstein损失可以鼓励预测在输出空间上选择的度量的平滑性。我们使用雅虎Flickr知识共享数据集，在一个实际数据标签预测问题上演示了这个属性，其性能优于不使用该指标的基准。

##### URL
[https://arxiv.org/abs/1506.05439](https://arxiv.org/abs/1506.05439)

##### PDF
[https://arxiv.org/pdf/1506.05439](https://arxiv.org/pdf/1506.05439)

