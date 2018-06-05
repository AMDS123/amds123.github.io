---
layout: post
title: "TernausNetV2: Fully Convolutional Network for Instance Segmentation"
date: 2018-06-03 17:55:13
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Transfer_Learning Semantic_Segmentation RNN Detection
author: Vladimir I. Iglovikov, Selim Seferbekov, Alexander V. Buslaev, Alexey Shvets
mathjax: true
---

* content
{:toc}

##### Abstract
The most common approaches to instance segmentation are complex and use two-stage networks with object proposals, conditional random-fields, template matching or recurrent neural networks. In this work we present TernausNetV2 - a simple fully convolutional network that allows extracting objects from a high-resolution satellite imagery on an instance level. The network has popular encoder-decoder type of architecture with skip connections but has a few essential modifications that allows using for semantic as well as for instance segmentation tasks. This approach is universal and allows to extend any network that has been successfully applied for semantic segmentation to perform instance segmentation task. In addition, we generalize network encoder that was pre-trained for RGB images to use additional input channels. It makes possible to use transfer learning from visual to a wider spectral range. For DeepGlobe-CVPR 2018 building detection sub-challenge, based on public leaderboard score, our approach shows superior performance in comparison to other methods. The source code corresponding pre-trained weights are publicly available at https://github.com/ternaus/TernausNetV2

##### Abstract (translated by Google)
最常用的实例分割方法非常复杂，可以使用带有对象提议，条件随机场，模板匹配或递归神经网络的两阶段网络。在这项工作中，我们介绍TernausNetV2  - 一个简单的完全卷积网络，允许从实例级别的高分辨率卫星图像中提取对象。该网络具有流行的编码器 - 解码器类型的体系结构，具有跳过连接，但具有一些必要的修改，允许用于语义以及例如分割任务。这种方法是通用的，可以扩展任何已经成功应用于语义分割的网络，以执行实例分割任务。另外，我们推广了针对RGB图像预先训练的网络编码器，以使用额外的输入通道。它使得使用从视觉到更宽光谱范围的转移学习成为可能。对于基于公共排行榜评分的DeepGlobe-CVPR 2018建筑物检测子挑战，我们的方法与其他方法相比表现出优越的性能。 https://github.com/ternaus/TernausNetV2上提供了相应的预先训练权重的源代码

##### URL
[http://arxiv.org/abs/1806.00844](http://arxiv.org/abs/1806.00844)

##### PDF
[http://arxiv.org/pdf/1806.00844](http://arxiv.org/pdf/1806.00844)

