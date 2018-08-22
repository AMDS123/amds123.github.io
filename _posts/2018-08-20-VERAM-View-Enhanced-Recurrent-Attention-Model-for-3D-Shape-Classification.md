---
layout: post
title: "VERAM: View-Enhanced Recurrent Attention Model for 3D Shape Classification"
date: 2018-08-20 21:08:02
categories: arXiv_CV
tags: arXiv_CV Attention Classification Recognition
author: Songle Chen, Lintao Zheng, Yan Zhang, Zhixin Sun, Kai Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-view deep neural network is perhaps the most successful approach in 3D shape classification. However, the fusion of multi-view features based on max or average pooling lacks a view selection mechanism, limiting its application in, e.g., multi-view active object recognition by a robot. This paper presents VERAM, a recurrent attention model capable of actively selecting a sequence of views for highly accurate 3D shape classification. VERAM addresses an important issue commonly found in existing attention-based models, i.e., the unbalanced training of the subnetworks corresponding to next view estimation and shape classification. The classification subnetwork is easily overfitted while the view estimation one is usually poorly trained, leading to a suboptimal classification performance. This is surmounted by three essential view-enhancement strategies: 1) enhancing the information flow of gradient backpropagation for the view estimation subnetwork, 2) devising a highly informative reward function for the reinforcement training of view estimation and 3) formulating a novel loss function that explicitly circumvents view duplication. Taking grayscale image as input and AlexNet as CNN architecture, VERAM with 9 views achieves instance-level and class-level accuracy of 95:5% and 95:3% on ModelNet10, 93:7% and 92:1% on ModelNet40, both are the state-of-the-art performance under the same number of views.

##### Abstract (translated by Google)
多视图深度神经网络可能是3D形状分类中最成功的方法。然而，基于最大或平均合并的多视图特征的融合缺乏视图选择机制，限制其在例如机器人的多视图活动对象识别中的应用。本文介绍了VERAM，这是一种能够主动选择一系列视图以进行高精度3D形状分类的循环注意模型。 VERAM解决了现有基于注意力的模型中常见的重要问题，即对应于下一个视图估计和形状分类的子网络的不平衡训练。分类子网很容易过度拟合，而视图估计通常训练不良，导致分类性能欠佳。这包括三个基本的视图增强策略：1）增强视图估计子网的梯度反向传播的信息流，2）为视图估计的强化训练设计高信息奖励函数和3）制定新的损失函数明确规避视图重复。将灰度图像作为输入，AlexNet作为CNN架构，具有9个视图的VERAM在ModelNet10上实现95：5％和95：3％的实例级和类级准确度，在ModelNet40上实现93：7％和92：1％，两者都是在相同数量的观点下，这是最先进的表现。

##### URL
[http://arxiv.org/abs/1808.06698](http://arxiv.org/abs/1808.06698)

##### PDF
[http://arxiv.org/pdf/1808.06698](http://arxiv.org/pdf/1808.06698)

