---
layout: post
title: "Learning Distributional Representation and Set Distance for Multi-shot Person Re-identification"
date: 2018-08-03 08:39:23
categories: arXiv_CV
tags: arXiv_CV Re-identification Attention Person_Re-identification
author: Ting-Yao Hu, Xiaojun Chang, Alexander G. Hauptmann
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification aims to identify a specific person at distinct time and locations. It is challenging because of occlusion, illumination, and viewpoint change in camera views. Recently, multi-shot person re-id task receives more attention because it is closer to real world application. A key point of a good algorithm for multi-shot person re-id is how to aggregate appearance features of all images temporally. Most of the current approaches apply pooling strategies and obtain a fixed size representation. We argue that representing a set of images as a feature vector may lose the matching evidences between examples. %A few very recent methods handle this issue by introducing multi-stage attention mechanism. However, In this work, we propose the idea of distributional representation, which interprets a image set as samples generated from a distribution in appearance feature space, and learn a distributional set distance function to compare two image sets. Specifically, we choose Wasserstein distance in this study. In this way, the proper alignment between two image sets can be discovered naturally in an non-parametric manner. Furthermore, the distance between distributions can serve as a supervision signal to finetune the appearance feature extractor in our model. Experiment results show that our proposed method achieve state-of-the-art performance on MARS dataset.

##### Abstract (translated by Google)
人员重新识别的目的是在不同的时间和地点识别特定的人。由于相机视图中的遮挡，照明和视点变化，因此具有挑战性。最近，由于更接近现实世界的应用程序，多镜头人员重新识别任务受到更多关注。多重人物重新识别的良好算法的关键点是如何在时间上聚合所有图像的外观特征。大多数当前方法应用汇集策略并获得固定大小的表示。我们认为将一组图像表示为特征向量可能会丢失示例之间的匹配证据。 ％一些最近的方法通过引入多阶段注意机制来处理这个问题。然而，在这项工作中，我们提出了分布式表示的思想，它将图像集解释为从外观特征空间中的分布生成的样本，并学习分布集距离函数来比较两个图像集。具体来说，我们在本研究中选择了Wasserstein距离。以这种方式，可以以非参数方式自然地发现两个图像集之间的适当对准。此外，分布之间的距离可以作为监督信号来微调我们模型中的外观特征提取器。实验结果表明，我们提出的方法在MARS数据集上实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1808.01119](http://arxiv.org/abs/1808.01119)

##### PDF
[http://arxiv.org/pdf/1808.01119](http://arxiv.org/pdf/1808.01119)

