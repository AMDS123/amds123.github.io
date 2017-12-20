---
layout: post
title: "End-to-end weakly-supervised semantic alignment"
date: 2017-12-19 10:52:22
categories: arXiv_CV
tags: arXiv_CV CNN
author: Ignacio Rocco, Relja Arandjelovi&#x107;, Josef Sivic
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle the task of semantic alignment where the goal is to compute dense semantic correspondence aligning two images depicting objects of the same category. This is a challenging task due to large intra-class variation, changes in viewpoint and background clutter. We present the following three principal contributions. First, we develop a convolutional neural network architecture for semantic alignment that is trainable in an end-to-end manner from weak image-level supervision in the form of matching image pairs. The outcome is that parameters are learnt from rich appearance variation present in different but semantically related images without the need for tedious manual annotation of correspondences at training time. Second, the main component of this architecture is a differentiable soft inlier scoring module, inspired by the RANSAC inlier scoring procedure, that computes the quality of the alignment based on only geometrically consistent correspondences thereby reducing the effect of background clutter. Third, we demonstrate that the proposed approach achieves state-of-the-art performance on multiple standard benchmarks for semantic alignment.

##### Abstract (translated by Google)
我们处理语义对齐的任务，其目标是计算描绘同一类别的对象的两个图像对齐的密集语义对应关系。这是一个具有挑战性的任务，因为课堂内部变化很大，视点和背景混乱。我们提出以下三个主要贡献。首先，我们开发了一种语义对齐的卷积神经网络体系结构，以匹配图像对的形式从弱图像层次的监督中以端对端的方式进行训练。结果是，参数是从不同的但语义相关的图像中出现的丰富的外观变化中学习的，而不需要在训练时间繁琐的人工对话的注释。其次，这种体系结构的主要组成部分是一个受RANSAC inlier评分程序启发的可区分软件inlier评分模块，它根据几何一致的对应关系计算对齐的质量，从而减少背景杂波的影响。第三，我们证明了所提出的方法在用于语义对齐的多个标准基准上实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1712.06861](http://arxiv.org/abs/1712.06861)

##### PDF
[http://arxiv.org/pdf/1712.06861](http://arxiv.org/pdf/1712.06861)

