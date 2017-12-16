---
layout: post
title: "Temporal Convolutional Networks: A Unified Approach to Action Segmentation"
date: 2016-08-29 20:48:15
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN RNN Relation
author: Colin Lea, Rene Vidal, Austin Reiter, Gregory D. Hager
mathjax: true
---

* content
{:toc}

##### Abstract
The dominant paradigm for video-based action segmentation is composed of two steps: first, for each frame, compute low-level features using Dense Trajectories or a Convolutional Neural Network that encode spatiotemporal information locally, and second, input these features into a classifier that captures high-level temporal relationships, such as a Recurrent Neural Network (RNN). While often effective, this decoupling requires specifying two separate models, each with their own complexities, and prevents capturing more nuanced long-range spatiotemporal relationships. We propose a unified approach, as demonstrated by our Temporal Convolutional Network (TCN), that hierarchically captures relationships at low-, intermediate-, and high-level time-scales. Our model achieves superior or competitive performance using video or sensor data on three public action segmentation datasets and can be trained in a fraction of the time it takes to train an RNN.

##### Abstract (translated by Google)
基于视频的动作分割的主要范式由两个步骤组成：首先，对于每一帧，使用密集轨迹计算低级特征或在本地编码时空信息的卷积神经网络;其次，将这些特征输入分类器捕捉高层次的时间关系，如递归神经网络（RNN）。虽然通常是有效的，但是这种分离需要指定两个独立的模型，每个模型都有其自身的复杂性，并防止捕获更多微妙的远程时空关系。我们提出了一种统一的方法，正如我们的时域卷积网络（TCN）所展示的那样，它在低层，中层和高层时间尺度上分层次捕获关系。我们的模型使用三个公共活动分割数据集上的视频或传感器数据来实现优异的或有竞争力的性能，并且可以训练一小部分时间来训练RNN。

##### URL
[https://arxiv.org/abs/1608.08242](https://arxiv.org/abs/1608.08242)

##### PDF
[https://arxiv.org/pdf/1608.08242](https://arxiv.org/pdf/1608.08242)

