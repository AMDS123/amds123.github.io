---
layout: post
title: "Spatio-Temporal Channel Correlation Networks for Action Classification"
date: 2018-06-19 12:43:40
categories: arXiv_CV
tags: arXiv_CV Knowledge Embedding CNN Classification Relation
author: Ali Diba, Mohsen Fayyaz, Vivek Sharma, M.Mahdi Arzani, Rahman Yousefzadeh, Juergen Gall, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
The work in this paper is driven by the question if spatio-temporal correlations are enough for 3D convolutional neural networks (CNN)? Most of the traditional 3D networks use local spatio-temporal features. We introduce a new block that models correlations between channels of a 3D CNN with respect to temporal and spatial features. This new block can be added as a residual unit to different parts of 3D CNNs. We name our novel block 'Spatio-Temporal Channel Correlation' (STC). By embedding this block to the current state-of-the-art architectures such as ResNext and ResNet, we improved the performance by 2-3\% on Kinetics dataset. Our experiments show that adding STC blocks to current state-of-the-art architectures outperforms the state-of-the-art methods on the HMDB51, UCF101 and Kinetics datasets. The other issue in training 3D CNNs is about training them from scratch with a huge labeled dataset to get a reasonable performance. So the knowledge learned in 2D CNNs is completely ignored. Another contribution in this work is a simple and effective technique to transfer knowledge from a pre-trained 2D CNN to a randomly initialized 3D CNN for a stable weight initialization. This allows us to significantly reduce the number of training samples for 3D CNNs. Thus, by fine-tuning this network, we beat the performance of generic and recent methods in 3D CNNs, which were trained on large video datasets, e.g. Sports-1M, and fine-tuned on the target datasets, e.g. HMDB51/UCF101.

##### Abstract (translated by Google)
本文中的工作是由三维卷积神经网络（CNN）的时空相关性是否足够的问题驱动的？大多数传统的3D网络使用本地时空特征。我们引入了一个新的模块，该模块针对时间和空间特征对3D CNN的通道之间的相关性进行建模。这个新块可以作为残余单元添加到3D CNN的不同部分。我们命名我们的小说“时空频道相关”（STC）。通过将此块嵌入到当前最先进的体系结构（如ResNext和ResNet）中，我们在Kinetics数据集上将性能提高了2-3％。我们的实验表明，将STC模块添加到当前最先进的体系结构中，将优于HMDB51，UCF101和Kinetics数据集上的最先进方法。培训3D CNN的另一个问题是要从头开始用一个巨大的标记数据集来训练它们，以获得合理的性能。因此，二维CNN中学到的知识被完全忽略。这项工作的另一个贡献是将知识从预先训练的二维CNN转移到随机初始化的3D CNN以实现稳定的体重初始化的简单而有效的技术。这使我们能够显着减少3D CNN的训练样本数量。因此，通过微调这个网络，我们击败了在大型视频数据集上训练的3D CNN中的通用和最近方法的性能，例如， Sports-1M，并对目标数据集进行微调，例如HMDB51 / UCF101。

##### URL
[http://arxiv.org/abs/1806.07754](http://arxiv.org/abs/1806.07754)

##### PDF
[http://arxiv.org/pdf/1806.07754](http://arxiv.org/pdf/1806.07754)

