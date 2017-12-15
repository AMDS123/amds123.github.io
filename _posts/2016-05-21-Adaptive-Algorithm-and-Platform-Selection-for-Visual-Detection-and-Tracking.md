---
layout: post
title: "Adaptive Algorithm and Platform Selection for Visual Detection and Tracking"
date: 2016-05-21 06:58:02
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: Shu Zhang, Qi Zhu, Amit Roy-Chowdhury
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision algorithms are known to be extremely sensitive to the environmental conditions in which the data is captured, e.g., lighting conditions and target density. Tuning of parameters or choosing a completely new algorithm is often needed to achieve a certain performance level, especially when there is a limitation of the computation source. In this paper, we focus on this problem and propose a framework to adaptively select the "best" algorithm-parameter combination and the computation platform under performance and cost constraints at design time, and adapt the algorithms at runtime based on real-time inputs. This necessitates developing a mechanism to switch between different algorithms as the nature of the input video changes. Our proposed algorithm calculates a similarity function between a test video scenario and each training scenario, where the similarity calculation is based on learning a manifold of image features that is shared by both the training and test datasets. Similarity between training and test dataset indicates the same algorithm can be applied to both of them and achieve similar performance. We design a cost function with this similarity measure to find the most similar training scenario to the test data. The "best" algorithm under a given platform is obtained by selecting the algorithm with a specific parameter combination that performs the best on the corresponding training data. The proposed framework can be used first offline to choose the platform based on performance and cost constraints, and then online whereby the "best" algorithm is selected for each new incoming video segment for a given platform. In the experiments, we apply our algorithm to the problems of pedestrian detection and tracking. We show how to adaptively select platforms and algorithm-parameter combinations. Our results provide optimal performance on 3 publicly available datasets.

##### Abstract (translated by Google)
已知计算机视觉算法对捕获数据的环境条件（例如照明条件和目标密度）非常敏感。通常需要调整参数或选择一个全新的算法来达到一定的性能水平，特别是当计算源存在限制时。在本文中，我们着重讨论这个问题，并提出了一个框架，在设计时自适应地选择“最佳”算法参数组合和性能和成本约束下的计算平台，并基于实时输入来适应运行时间的算法。随着输入视频的性质改变，这就需要开发一种机制来在不同的算法之间切换。我们提出的算法计算测试视频场景和每个训练场景之间的相似度函数，其中相似度计算是基于学习训练数据集和测试数据集共享的图像特征的多样性。训练和测试数据集之间的相似性表明相同的算法可以应用于它们两者并且实现类似的性能。我们用这种相似性度量来设计一个成本函数，以找到与测试数据最相似的训练场景。在给定平台下的“最佳”算法是通过选择具有在相应训练数据上表现最佳的特定参数组合的算法来获得的。所提出的框架可以首先使用离线来基于性能和成本约束来选择平台，然后在线从而针对给定平台的每个新的传入视频片段选择“最佳”算法。在实验中，我们将该算法应用于行人检测和跟踪问题。我们展示了如何自适应地选择平台和算法参数组合。我们的结果在3个公开可用的数据集上提供最佳性能。

##### URL
[https://arxiv.org/abs/1605.06597](https://arxiv.org/abs/1605.06597)

##### PDF
[https://arxiv.org/pdf/1605.06597](https://arxiv.org/pdf/1605.06597)

