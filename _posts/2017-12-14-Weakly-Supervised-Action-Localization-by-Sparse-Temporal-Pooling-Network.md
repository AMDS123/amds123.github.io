---
layout: post
title: "Weakly Supervised Action Localization by Sparse Temporal Pooling Network"
date: 2017-12-14 03:34:03
categories: arXiv_CV
tags: arXiv_CV Sparse Attention Weakly_Supervised CNN Classification
author: Phuc Nguyen, Ting Liu, Gautam Prasad, Bohyung Han
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a weakly supervised temporal action localization algorithm on untrimmed videos using convolutional neural networks. Our algorithm predicts temporal intervals of human actions given video-level class labels with no requirement of temporal localization information of actions. This objective is achieved by proposing a novel deep neural network that recognizes actions and identifies a sparse set of key segments associated with the actions through adaptive temporal pooling of video segments. We design the loss function of the network to comprise two terms--one for classification error and the other for sparsity of the selected segments. After recognizing actions with sparse attention weights for key segments, we extract temporal proposals for actions using temporal class activation mappings to estimate time intervals that localize target actions. The proposed algorithm attains state-of-the-art accuracy on the THUMOS14 dataset and outstanding performance on ActivityNet1.3 even with weak supervision.

##### Abstract (translated by Google)
我们提出了一个使用卷积神经网络的未修剪视频的弱监督时间动作定位算法。我们的算法预测给定视频级别标签的人类动作的时间间隔，而不需要动作的时间定位信息。这个目标是通过提出一种新颖的深度神经网络来实现的，该神经网络通过视频片段的自适应时间合并来识别动作并识别与动作相关联的关键片段的稀疏集合。我们设计网络的损失函数包括两个术语 - 一个用于分类错误，另一个用于选择片段的稀疏性。在识别出针对关键段的稀疏关注权重的操作之后，我们使用时间类激活映射来提取针对动作的时间提议以估计对目标动作进行本地化的时间间隔。所提出的算法在THUMOS14数据集上达到了最新的精度，并且即使在监督力较弱的情况下也能在ActivityNet1.3上表现出色。

##### URL
[http://arxiv.org/abs/1712.05080](http://arxiv.org/abs/1712.05080)

##### PDF
[http://arxiv.org/pdf/1712.05080](http://arxiv.org/pdf/1712.05080)

