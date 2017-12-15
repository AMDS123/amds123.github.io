---
layout: post
title: "Convolutional Two-Stream Network Fusion for Video Action Recognition"
date: 2016-09-26 10:47:21
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Prediction Recognition
author: Christoph Feichtenhofer, Axel Pinz, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
Recent applications of Convolutional Neural Networks (ConvNets) for human action recognition in videos have proposed different solutions for incorporating the appearance and motion information. We study a number of ways of fusing ConvNet towers both spatially and temporally in order to best take advantage of this spatio-temporal information. We make the following findings: (i) that rather than fusing at the softmax layer, a spatial and temporal network can be fused at a convolution layer without loss of performance, but with a substantial saving in parameters; (ii) that it is better to fuse such networks spatially at the last convolutional layer than earlier, and that additionally fusing at the class prediction layer can boost accuracy; finally (iii) that pooling of abstract convolutional features over spatiotemporal neighbourhoods further boosts performance. Based on these studies we propose a new ConvNet architecture for spatiotemporal fusion of video snippets, and evaluate its performance on standard benchmarks where this architecture achieves state-of-the-art results.

##### Abstract (translated by Google)
卷积神经网络（ConvNets）最近在视频中用于人类动作识别的应用已经提出了结合外观和运动信息的不同解决方案。我们研究了多种在空间和时间上融合ConvNet塔的方法，以便最好地利用这个时空信息。我们得出以下结论：（i）不是在softmax层上融合，而是在空间和时间网络可以在卷积层融合而不损失性能，但是大大节省了参数; （ii）最好在最后一个卷积层上在空间上融合这些网络，而在类别预测层进行另外的融合可以提高准确性;最后（iii）将抽象卷积特征集中于时空邻域进一步提升性能。基于这些研究，我们提出了一种新的视频片段时空融合的ConvNet体系结构，并评估其在标准基准测试中的性能，其中该体系结构实现了最新的结果。

##### URL
[https://arxiv.org/abs/1604.06573](https://arxiv.org/abs/1604.06573)

##### PDF
[https://arxiv.org/pdf/1604.06573](https://arxiv.org/pdf/1604.06573)

