---
layout: post
title: "Learning deep structured active contours end-to-end"
date: 2018-03-16 17:30:37
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Diego Marcos, Devis Tuia, Benjamin Kellenberger, Lisa Zhang, Min Bai, Renjie Liao, Raquel Urtasun
mathjax: true
---

* content
{:toc}

##### Abstract
The world is covered with millions of buildings, and precisely knowing each instance's position and extents is vital to a multitude of applications. Recently, automated building footprint segmentation models have shown superior detection accuracy thanks to the usage of Convolutional Neural Networks (CNN). However, even the latest evolutions struggle to precisely delineating borders, which often leads to geometric distortions and inadvertent fusion of adjacent building instances. We propose to overcome this issue by exploiting the distinct geometric properties of buildings. To this end, we present Deep Structured Active Contours (DSAC), a novel framework that integrates priors and constraints into the segmentation process, such as continuous boundaries, smooth edges, and sharp corners. To do so, DSAC employs Active Contour Models (ACM), a family of constraint- and prior-based polygonal models. We learn ACM parameterizations per instance using a CNN, and show how to incorporate all components in a structured output model, making DSAC trainable end-to-end. We evaluate DSAC on three challenging building instance segmentation datasets, where it compares favorably against state-of-the-art. Code will be made available.

##### Abstract (translated by Google)
世界上有数以百万计的建筑物，并且准确地了解每个实例的位置和范围对于大量应用程序至关重要。最近，由于使用了卷积神经网络（CNN），自动建筑物足迹分割模型显示了出众的检测精度。然而，即使是最新的演变也难以精确划定边界，这往往会导致相邻建筑物实体的几何扭曲和无意中融合。我们建议通过利用建筑物的独特几何特性来克服这个问题。为此，我们提出了深层结构化主动轮廓（DSAC），这是一种将先验和约束整合到分割过程中的新颖框架，如连续边界，光滑边缘和尖角。为此，DSAC采用主动轮廓模型（ACM），这是一组基于约束和先验的多边形模型。我们使用CNN学习每个实例的ACM参数化，并演示如何将所有组件结合到结构化输出模型中，从而使DSAC可端到端地进行培训。我们在三个具有挑战性的建筑物实例分段数据集上评估DSAC，并与最先进的建筑物进行比较。代码将可用。

##### URL
[https://arxiv.org/abs/1803.06329](https://arxiv.org/abs/1803.06329)

##### PDF
[https://arxiv.org/pdf/1803.06329](https://arxiv.org/pdf/1803.06329)

