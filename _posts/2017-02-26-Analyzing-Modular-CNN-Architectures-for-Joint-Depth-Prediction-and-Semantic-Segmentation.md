---
layout: post
title: "Analyzing Modular CNN Architectures for Joint Depth Prediction and Semantic Segmentation"
date: 2017-02-26 09:30:08
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Prediction Relation
author: Omid Hosseini Jafari, Oliver Groth, Alexander Kirillov, Michael Ying Yang, Carsten Rother
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the task of designing a modular neural network architecture that jointly solves different tasks. As an example we use the tasks of depth estimation and semantic segmentation given a single RGB image. The main focus of this work is to analyze the cross-modality influence between depth and semantic prediction maps on their joint refinement. While most previous works solely focus on measuring improvements in accuracy, we propose a way to quantify the cross-modality influence. We show that there is a relationship between final accuracy and cross-modality influence, although not a simple linear one. Hence a larger cross-modality influence does not necessarily translate into an improved accuracy. We find that a beneficial balance between the cross-modality influences can be achieved by network architecture and conjecture that this relationship can be utilized to understand different network design choices. Towards this end we propose a Convolutional Neural Network (CNN) architecture that fuses the state of the state-of-the-art results for depth estimation and semantic labeling. By balancing the cross-modality influences between depth and semantic prediction, we achieve improved results for both tasks using the NYU-Depth v2 benchmark.

##### Abstract (translated by Google)
本文介绍了设计一个模块化神经网络架构的任务，共同解决不同的任务。作为一个例子，我们使用给定单个RGB图像的深度估计和语义分割的任务。这项工作的主要重点是分析深度和语义预测地图之间的联合细化的跨模态影响。虽然大多数以前的作品只是专注于衡量准确性的提高，但我们提出了一种量化跨模态影响的方法。我们表明，最终的准确性和跨模态的影响，虽然不是一个简单的线性之间有一个关系。因此，较大的交叉模态影响并不一定意味着提高了准确性。我们发现，网络架构可以实现跨模态影响之间的有利平衡，并且可以利用这种关系来理解不同的网络设计选择。为此，我们提出了一种卷积神经网络（CNN）架构，它融合了深度估计和语义标签的最新结果的状态。通过平衡深度和语义预测之间的交叉模式影响，我们使用NYU-Depth v2基准来实现两项任务的改进结果。

##### URL
[https://arxiv.org/abs/1702.08009](https://arxiv.org/abs/1702.08009)

##### PDF
[https://arxiv.org/pdf/1702.08009](https://arxiv.org/pdf/1702.08009)

