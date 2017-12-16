---
layout: post
title: "PixelNet: Towards a General Pixel-level Architecture"
date: 2016-09-21 19:32:46
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Semantic_Segmentation Prediction Detection
author: Aayush Bansal, Xinlei Chen, Bryan Russell, Abhinav Gupta, Deva Ramanan
mathjax: true
---

* content
{:toc}

##### Abstract
We explore architectures for general pixel-level prediction problems, from low-level edge detection to mid-level surface normal estimation to high-level semantic segmentation. Convolutional predictors, such as the fully-convolutional network (FCN), have achieved remarkable success by exploiting the spatial redundancy of neighboring pixels through convolutional processing. Though computationally efficient, we point out that such approaches are not statistically efficient during learning precisely because spatial redundancy limits the information learned from neighboring pixels. We demonstrate that (1) stratified sampling allows us to add diversity during batch updates and (2) sampled multi-scale features allow us to explore more nonlinear predictors (multiple fully-connected layers followed by ReLU) that improve overall accuracy. Finally, our objective is to show how a architecture can get performance better than (or comparable to) the architectures designed for a particular task. Interestingly, our single architecture produces state-of-the-art results for semantic segmentation on PASCAL-Context, surface normal estimation on NYUDv2 dataset, and edge detection on BSDS without contextual post-processing.

##### Abstract (translated by Google)
我们研究一般像素级预测问题的架构，从低级边缘检测到中级表面法线估计，再到高级语义分割。卷积预测器，例如完全卷积网络（FCN），通过卷积处理利用相邻像素的空间冗余，取得了显着的成功。尽管计算效率很高，但我们指出，这种方法在学习期间不具有统计效率，因为空间冗余限制了从相邻像素学习的信息。我们证明：（1）分层采样允许我们在批次更新期间添加多样性;（2）采样多尺度特征使我们能够探索更多的非线性预测器（多个完全连接层，随后是ReLU），这提高了整体的准确性。最后，我们的目标是展示一个体系结构如何获得比为特定任务设计的体系结构更好（或相当于）的性能。有趣的是，我们的单一架构在PASCAL-Context上进行语义分割，在NYUDv2数据集上进行表面法线估计以及在没有上下文后处理的情况下在BSDS上进行边缘检测。

##### URL
[https://arxiv.org/abs/1609.06694](https://arxiv.org/abs/1609.06694)

##### PDF
[https://arxiv.org/pdf/1609.06694](https://arxiv.org/pdf/1609.06694)

