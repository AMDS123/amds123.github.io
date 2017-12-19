---
layout: post
title: "Deep Feature Learning with Relative Distance Comparison for Person Re-identification"
date: 2015-12-11 12:34:22
categories: arXiv_CV
tags: arXiv_CV Re-identification GAN Person_Re-identification CNN Optimization Gradient_Descent
author: Shengyong Ding, Liang Lin, Guangrun Wang, Hongyang Chao
mathjax: true
---

* content
{:toc}

##### Abstract
Identifying the same individual across different scenes is an important yet difficult task in intelligent video surveillance. Its main difficulty lies in how to preserve similarity of the same person against large appearance and structure variation while discriminating different individuals. In this paper, we present a scalable distance driven feature learning framework based on the deep neural network for person re-identification, and demonstrate its effectiveness to handle the existing challenges. Specifically, given the training images with the class labels (person IDs), we first produce a large number of triplet units, each of which contains three images, i.e. one person with a matched reference and a mismatched reference. Treating the units as the input, we build the convolutional neural network to generate the layered representations, and follow with the $L2$ distance metric. By means of parameter optimization, our framework tends to maximize the relative distance between the matched pair and the mismatched pair for each triplet unit. Moreover, a nontrivial issue arising with the framework is that the triplet organization cubically enlarges the number of training triplets, as one image can be involved into several triplet units. To overcome this problem, we develop an effective triplet generation scheme and an optimized gradient descent algorithm, making the computational load mainly depends on the number of original images instead of the number of triplets. On several challenging databases, our approach achieves very promising results and outperforms other state-of-the-art approaches.

##### Abstract (translated by Google)
在不同场景中识别同一个人是智能视频监控中的一项重要而艰巨的任务。它的主要困难在于如何保持同一个人的相似性，防止大的表象和结构变化，同时区分不同的个体。在本文中，我们提出了一种基于深度神经网络的可重构的距离驱动特征学习框架，用于人员重新识别，并展示了其处理现有挑战的有效性。具体来说，给定具有类别标签（人物ID）的训练图像，我们首先产生大量的三元组单元，每个单元包含三个图像，即具有匹配参考和不匹配参考的一个人。作为输入处理单位，我们建立卷积神经网络来生成分层表示，并遵循$ L2 $距离度量。通过参数优化，我们的框架倾向于最大化匹配对和不匹配对之间的每个三元组单元的相对距离。此外，框架产生的一个不平凡的问题是，三重组织立方体地扩大了训练三胞胎的数量，因为一幅图像可能涉及到几个三重单位。为了克服这个问题，我们开发了一个有效的三元组生成方案和一个优化的梯度下降算法，使计算量主要取决于原始图像的数量而不是三元组的数量。在一些具有挑战性的数据库中，我们的方法取得了非常有希望的结果，并且胜过了其他最先进的方法。

##### URL
[https://arxiv.org/abs/1512.03622](https://arxiv.org/abs/1512.03622)

##### PDF
[https://arxiv.org/pdf/1512.03622](https://arxiv.org/pdf/1512.03622)

