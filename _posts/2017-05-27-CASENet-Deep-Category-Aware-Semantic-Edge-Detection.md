---
layout: post
title: "CASENet: Deep Category-Aware Semantic Edge Detection"
date: 2017-05-27 03:35:36
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Deep_Learning Detection Recognition
author: Zhiding Yu, Chen Feng, Ming-Yu Liu, Srikumar Ramalingam
mathjax: true
---

* content
{:toc}

##### Abstract
Boundary and edge cues are highly beneficial in improving a wide variety of vision tasks such as semantic segmentation, object recognition, stereo, and object proposal generation. Recently, the problem of edge detection has been revisited and significant progress has been made with deep learning. While classical edge detection is a challenging binary problem in itself, the category-aware semantic edge detection by nature is an even more challenging multi-label problem. We model the problem such that each edge pixel can be associated with more than one class as they appear in contours or junctions belonging to two or more semantic classes. To this end, we propose a novel end-to-end deep semantic edge learning architecture based on ResNet and a new skip-layer architecture where category-wise edge activations at the top convolution layer share and are fused with the same set of bottom layer features. We then propose a multi-label loss function to supervise the fused activations. We show that our proposed architecture benefits this problem with better performance, and we outperform the current state-of-the-art semantic edge detection methods by a large margin on standard data sets such as SBD and Cityscapes.

##### Abstract (translated by Google)
边界和边缘线索对于改善诸如语义分割，对象识别，立体声和对象建议生成等各种视觉任务是非常有益的。最近，边缘检测的问题已经被重新审视，深入的学习已经取得了重大的进展。经典的边缘检测本身就是一个具有挑战性的二元问题，而本质上的类别感知语义边缘检测是一个更具挑战性的多标签问题。我们对问题进行建模，使得每个边缘像素可以与属于两个或多个语义类的轮廓或交叉点中出现的多个类相关联。为此，我们提出了一种基于ResNet的新型端到端深度语义边缘学习体系结构和一种新的跳过层体系结构，其中顶级卷积层上的类别边缘激活共享并与同一组底层特征。然后，我们提出一个多标签损失函数来监督融合激活。我们表明，我们所提出的体系结构能够以更好的性能为这个问题带来好处，而且我们在诸如SBD和Cityscapes这样的标准数据集上大大超越了当前最先进的语义边缘检测方法。

##### URL
[https://arxiv.org/abs/1705.09759](https://arxiv.org/abs/1705.09759)

##### PDF
[https://arxiv.org/pdf/1705.09759](https://arxiv.org/pdf/1705.09759)

