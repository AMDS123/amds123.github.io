---
layout: post
title: "Searching for Efficient Multi-Scale Architectures for Dense Image Prediction"
date: 2018-09-11 22:36:01
categories: arXiv_CV
tags: arXiv_CV Segmentation Survey Image_Classification Classification Prediction
author: Liang-Chieh Chen, Maxwell D. Collins, Yukun Zhu, George Papandreou, Barret Zoph, Florian Schroff, Hartwig Adam, Jonathon Shlens
mathjax: true
---

* content
{:toc}

##### Abstract
The design of neural network architectures is an important component for achieving state-of-the-art performance with machine learning systems across a broad array of tasks. Much work has endeavored to design and build architectures automatically through clever construction of a search space paired with simple learning algorithms. Recent progress has demonstrated that such meta-learning methods may exceed scalable human-invented architectures on image classification tasks. An open question is the degree to which such methods may generalize to new domains. In this work we explore the construction of meta-learning techniques for dense image prediction focused on the tasks of scene parsing, person-part segmentation, and semantic image segmentation. Constructing viable search spaces in this domain is challenging because of the multi-scale representation of visual information and the necessity to operate on high resolution imagery. Based on a survey of techniques in dense image prediction, we construct a recursive search space and demonstrate that even with efficient random search, we can identify architectures that outperform human-invented architectures and achieve state-of-the-art performance on three dense prediction tasks including 82.7\% on Cityscapes (street scene parsing), 71.3\% on PASCAL-Person-Part (person-part segmentation), and 87.9\% on PASCAL VOC 2012 (semantic image segmentation). Additionally, the resulting architecture is more computationally efficient, requiring half the parameters and half the computational cost as previous state of the art systems.

##### Abstract (translated by Google)
神经网络架构的设计是通过机器学习系统在广泛的任务中实现最先进性能的重要组成部分。许多工作都致力于通过巧妙构建与简单学习算法配合的搜索空间来自动设计和构建体系结构。最近的进展表明，这种元学习方法可能超出可扩展的人为发明的图像分类任务架构。一个悬而未决的问题是这些方法可以推广到新领域的程度。在这项工作中，我们探索了密集图像预测的元学习技术的构建，重点是场景解析，人物部分分割和语义图像分割的任务。由于视觉信息的多尺度表示和在高分辨率图像上操作的必要性，在该领域中构建可行的搜索空间是具有挑战性的。基于对密集图像预测技术的调查，我们构建了一个递归搜索空间，并证明即使使用有效的随机搜索，我们也可以识别出优于人类发明架构的架构，并在三个密集预测上实现最先进的性能任务包括Cityscapes上的82.7 \％（街景解析），PASCAL-Person-Part（人员部分细分）上的71.3％，PASCAL VOC 2012上的87.9％（语义图像分割）。另外，所得到的体系结构在计算上更有效，需要一半的参数和一半的计算成本，如同现有技术系统。

##### URL
[http://arxiv.org/abs/1809.04184](http://arxiv.org/abs/1809.04184)

##### PDF
[http://arxiv.org/pdf/1809.04184](http://arxiv.org/pdf/1809.04184)

