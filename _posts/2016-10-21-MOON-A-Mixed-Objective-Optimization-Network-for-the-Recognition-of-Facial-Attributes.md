---
layout: post
title: "MOON: A Mixed Objective Optimization Network for the Recognition of Facial Attributes"
date: 2016-10-21 16:56:07
categories: arXiv_CV
tags: arXiv_CV Face CNN Optimization Recognition Face_Recognition
author: Ethan Rudd, Manuel Günther, Terrance Boult
mathjax: true
---

* content
{:toc}

##### Abstract
Attribute recognition, particularly facial, extracts many labels for each image. While some multi-task vision problems can be decomposed into separate tasks and stages, e.g., training independent models for each task, for a growing set of problems joint optimization across all tasks has been shown to improve performance. We show that for deep convolutional neural network (DCNN) facial attribute extraction, multi-task optimization is better. Unfortunately, it can be difficult to apply joint optimization to DCNNs when training data is imbalanced, and re-balancing multi-label data directly is structurally infeasible, since adding/removing data to balance one label will change the sampling of the other labels. This paper addresses the multi-label imbalance problem by introducing a novel mixed objective optimization network (MOON) with a loss function that mixes multiple task objectives with domain adaptive re-weighting of propagated loss. Experiments demonstrate that not only does MOON advance the state of the art in facial attribute recognition, but it also outperforms independently trained DCNNs using the same data. When using facial attributes for the LFW face recognition task, we show that our balanced (domain adapted) network outperforms the unbalanced trained network.

##### Abstract (translated by Google)
属性识别，特别是面部识别，为每个图像提取许多标签。虽然一些多任务视觉问题可以分解成不同的任务和阶段，例如，为每个任务训练独立模型，但是对于越来越多的问题，所有任务的联合优化已被证明可以提高性能。我们证明，对于深度卷积神经网络（DCNN）人脸属性提取，多任务优化效果较好。不幸的是，当训练数据不平衡时，可能难以将联合优化应用于DCNN，并且直接重新平衡多标签数据在结构上是不可行的，因为添加/移除数据以平衡一个标签将改变其他标签的采样。本文针对多标签不均衡问题，引入了一种新的混合目标优化网络（MOON），该网络具有混合多任务目标和传播损失的域自适应加权的损失函数。实验表明，MOON不仅提高了面部属性识别的先进水平，而且还使用相同的数据优于独立训练的DCNN。当面部属性用于LFW人脸识别任务时，我们显示我们的平衡（域适应）网络胜过不平衡训练的网络。

##### URL
[https://arxiv.org/abs/1603.07027](https://arxiv.org/abs/1603.07027)

##### PDF
[https://arxiv.org/pdf/1603.07027](https://arxiv.org/pdf/1603.07027)

