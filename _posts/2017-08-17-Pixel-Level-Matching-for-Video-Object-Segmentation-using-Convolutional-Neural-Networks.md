---
layout: post
title: "Pixel-Level Matching for Video Object Segmentation using Convolutional Neural Networks"
date: 2017-08-17 05:04:23
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Jae Shin Yoon, Francois Rameau, Junsik Kim, Seokju Lee, Seunghak Shin, In So Kweon
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel video object segmentation algorithm based on pixel-level matching using Convolutional Neural Networks (CNN). Our network aims to distinguish the target area from the background on the basis of the pixel-level similarity between two object units. The proposed network represents a target object using features from different depth layers in order to take advantage of both the spatial details and the category-level semantic information. Furthermore, we propose a feature compression technique that drastically reduces the memory requirements while maintaining the capability of feature representation. Two-stage training (pre-training and fine-tuning) allows our network to handle any target object regardless of its category (even if the object's type does not belong to the pre-training data) or of variations in its appearance through a video sequence. Experiments on large datasets demonstrate the effectiveness of our model - against related methods - in terms of accuracy, speed, and stability. Finally, we introduce the transferability of our network to different domains, such as the infrared data domain.

##### Abstract (translated by Google)
我们提出了一种基于卷积神经网络（CNN）的基于像素级匹配的视频对象分割算法。我们的网络旨在根据两个对象单元之间的像素级相似性来区分目标区域和背景。提出的网络代表一个目标对象使用来自不同深度层次的特征，以利用空间细节和类别级别的语义信息。此外，我们提出了一种特征压缩技术，可以在保持特征表示能力的同时大大降低内存需求。两阶段训练（预训练和微调）允许我们的网络处理任何目标对象，而不管其类别（即使对象的类型不属于训练前的数据）或通过视频的外观变化序列。大数据集上的实验证明了我们的模型在相对于相关方法的精度，速度和稳定性方面的有效性。最后，我们介绍了我们的网络在不同的领域，如红外数据领域的可转移性。

##### URL
[https://arxiv.org/abs/1708.05137](https://arxiv.org/abs/1708.05137)

##### PDF
[https://arxiv.org/pdf/1708.05137](https://arxiv.org/pdf/1708.05137)

