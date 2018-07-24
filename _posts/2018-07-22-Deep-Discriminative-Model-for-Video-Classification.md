---
layout: post
title: "Deep Discriminative Model for Video Classification"
date: 2018-07-22 08:46:02
categories: arXiv_CV
tags: arXiv_CV Sparse Action_Recognition Video_Classification Classification Deep_Learning Recognition
author: Mohammad Tavakolian, Abdenour Hadid
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a new deep learning approach for video-based scene classification. We design a Heterogeneous Deep Discriminative Model (HDDM) whose parameters are initialized by performing an unsupervised pre-training in a layer-wise fashion using Gaussian Restricted Boltzmann Machines (GRBM). In order to avoid the redundancy of adjacent frames, we extract spatiotemporal variation patterns within frames and represent them sparsely using Sparse Cubic Symmetrical Pattern (SCSP). Then, a pre-initialized HDDM is separately trained using the videos of each class to learn class-specific models. According to the minimum reconstruction error from the learnt class-specific models, a weighted voting strategy is employed for the classification. The performance of the proposed method is extensively evaluated on two action recognition datasets; UCF101 and Hollywood II, and three dynamic texture and dynamic scene datasets; DynTex, YUPENN, and Maryland. The experimental results and comparisons against state-of-the-art methods demonstrate that the proposed method consistently achieves superior performance on all datasets.

##### Abstract (translated by Google)
本文提出了一种新的基于视频场景分类的深度学习方法。我们设计了一个异构深度判别模型（HDDM），其参数通过使用高斯限制玻尔兹曼机器（GRBM）以分层方式执行无监督预训练来初始化。为了避免相邻帧的冗余，我们提取帧内的时空变化模式，并使用稀疏立方对称模式（SCSP）稀疏地表示它们。然后，使用每个类的视频单独训练预初始化的HDDM以学习类特定模型。根据所学习的类特定模型的最小重建误差，采用加权投票策略进行分类。在两个动作识别数据集上广泛评估了所提方法的性能; UCF101和好莱坞II，以及三个动态纹理和动态场景数据集; DynTex，YUPENN和Maryland。实验结果和与现有技术方法的比较表明，所提出的方法始终在所有数据集上实现卓越的性能。

##### URL
[http://arxiv.org/abs/1807.08259](http://arxiv.org/abs/1807.08259)

##### PDF
[http://arxiv.org/pdf/1807.08259](http://arxiv.org/pdf/1807.08259)

