---
layout: post
title: "Dual Attention Network for Scene Segmentation"
date: 2018-09-09 14:48:22
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention
author: Jun Fu, Jing Liu, Haijie Tian, Zhiwei Fang, Hanqing Lu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the scene segmentation task by capturing rich contextual dependencies based on the selfattention mechanism. Unlike previous works that capture contexts by multi-scale features fusion, we propose a Dual Attention Networks (DANet) to adaptively integrate local features with their global dependencies. Specifically, we append two types of attention modules on top of traditional dilated FCN, which model the semantic interdependencies in spatial and channel dimensions respectively. The position attention module selectively aggregates the features at each position by a weighted sum of the features at all positions. Similar features would be related to each other regardless of their distances. Meanwhile, the channel attention module selectively emphasizes interdependent channel maps by integrating associated features among all channel maps. We sum the outputs of the two attention modules to further improve feature representation which contributes to more precise segmentation results. We achieve new state-of-the-art segmentation performance on three challenging scene segmentation datasets, i.e., Cityscapes, PASCAL Context and COCO Stuff dataset. In particular, a Mean IoU score of 81.5% on Cityscapes test set is achieved without using coarse data

##### Abstract (translated by Google)
在本文中，我们通过基于自我约束机制捕获丰富的上下文依赖性来解决场景分割任务。与以前通过多尺度特征融合捕获上下文的工作不同，我们提出了双重注意网络（DANet）来自适应地集成本地特征及其全局依赖性。具体来说，我们在传统的扩张FCN之上附加两种类型的注意模块，它们分别对空间和通道维度中的语义相互依赖性进行建模。位置关注模块通过所有位置处的特征的加权和来选择性地聚合每个位置处的特征。无论距离如何，类似的特征都将彼此相关。同时，信道关注模块通过整合所有信道映射之间的相关特征来选择性地强调相互依赖的信道映射。我们将两个注意模块的输出相加以进一步改进特征表示，这有助于更精确的分割结果。我们在三个具有挑战性的场景分割数据集上实现了新的最先进的分割性能，即Cityscapes，PASCAL Context和COCO Stuff数据集。特别是，在不使用粗略数据的情况下，Cityscapes测试集的平均IoU得分为81.5％

##### URL
[http://arxiv.org/abs/1809.02983](http://arxiv.org/abs/1809.02983)

##### PDF
[http://arxiv.org/pdf/1809.02983](http://arxiv.org/pdf/1809.02983)

