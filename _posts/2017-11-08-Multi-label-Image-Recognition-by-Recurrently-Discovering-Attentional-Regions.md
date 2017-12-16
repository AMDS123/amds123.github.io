---
layout: post
title: "Multi-label Image Recognition by Recurrently Discovering Attentional Regions"
date: 2017-11-08 03:43:51
categories: arXiv_CV
tags: arXiv_CV Attention CNN Image_Classification RNN Classification Recognition
author: Zhouxia Wang, Tianshui Chen, Guanbin Li, Ruijia Xu, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel deep architecture to address multi-label image recognition, a fundamental and practical task towards general visual understanding. Current solutions for this task usually rely on an extra step of extracting hypothesis regions (i.e., region proposals), resulting in redundant computation and sub-optimal performance. In this work, we achieve the interpretable and contextualized multi-label image classification by developing a recurrent memorized-attention module. This module consists of two alternately performed components: i) a spatial transformer layer to locate attentional regions from the convolutional feature maps in a region-proposal-free way and ii) an LSTM (Long-Short Term Memory) sub-network to sequentially predict semantic labeling scores on the located regions while capturing the global dependencies of these regions. The LSTM also output the parameters for computing the spatial transformer. On large-scale benchmarks of multi-label image classification (e.g., MS-COCO and PASCAL VOC 07), our approach demonstrates superior performances over other existing state-of-the-arts in both accuracy and efficiency.

##### Abstract (translated by Google)
本文提出了一种新的深层次的体系结构来解决多标签图像识别，这是一个基本的和实际的任务，以一般的视觉理解该任务的当前解决方案通常依赖于提取假设区域（即区域提议）的额外步骤，导致冗余计算和次优性能。在这项工作中，我们通过开发一个反复记忆的关注模块来实现可解释和情境化的多标签图像分类。该模块由两个交替执行的组件组成：i）空间变换器层，以卷积特征映射以区域提议自由的方式定位注意区域;以及ii）LSTM（长 - 短期存储器）子网络，以顺序预测在捕获这些区域的全局依赖性的同时，定位区域上的语义标记评分。 LSTM还输出用于计算空间变换器的参数。在多标签图像分类（例如MS-COCO和PASCAL VOC 07）的大规模基准测试中，我们的方法在准确性和效率方面展现了优于其他现有技术的先进性能。

##### URL
[https://arxiv.org/abs/1711.02816](https://arxiv.org/abs/1711.02816)

##### PDF
[https://arxiv.org/pdf/1711.02816](https://arxiv.org/pdf/1711.02816)

