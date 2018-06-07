---
layout: post
title: "Instance Segmentation and Tracking with Cosine Embeddings and Recurrent Hourglass Networks"
date: 2018-06-06 08:57:15
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Embedding CNN Semantic_Segmentation
author: Christian Payer, Darko &#x160;tern, Thomas Neff, Horst Bischof, Martin Urschler
mathjax: true
---

* content
{:toc}

##### Abstract
Different to semantic segmentation, instance segmentation assigns unique labels to each individual instance of the same class. In this work, we propose a novel recurrent fully convolutional network architecture for tracking such instance segmentations over time. The network architecture incorporates convolutional gated recurrent units (ConvGRU) into a stacked hourglass network to utilize temporal video information. Furthermore, we train the network with a novel embedding loss based on cosine similarities, such that the network predicts unique embeddings for every instance throughout videos. Afterwards, these embeddings are clustered among subsequent video frames to create the final tracked instance segmentations. We evaluate the recurrent hourglass network by segmenting left ventricles in MR videos of the heart, where it outperforms a network that does not incorporate video information. Furthermore, we show applicability of the cosine embedding loss for segmenting leaf instances on still images of plants. Finally, we evaluate the framework for instance segmentation and tracking on six datasets of the ISBI celltracking challenge, where it shows state-of-the-art performance.

##### Abstract (translated by Google)
与语义分割不同，实例分段为同一类的每个单独实例分配唯一标签。在这项工作中，我们提出了一种新颖的循环全卷积网络架构，用于跟踪这些实例分段随着时间的推移。网络体系结构将卷积门控循环单元（ConvGRU）合并到堆叠沙漏网络中以利用时间视频信息。此外，我们使用基于余弦相似性的新颖嵌入损失来训练网络，以便网络能够预测整个视频中每个实例的唯一嵌入。之后，这些嵌入在后续视频帧中聚集，以创建最终跟踪的实例分段。我们通过在心脏的MR视频中分割左心室来评估复发性沙漏网络，在那里它的表现优于不包含视频信息的网络。此外，我们还展示了在植物静止图像上分割叶子实例的余弦嵌入损失的适用性。最后，我们评估了ISBI细胞追踪挑战的六个数据集上的实例分割和追踪框架，并显示了最先进的性能。

##### URL
[http://arxiv.org/abs/1806.02070](http://arxiv.org/abs/1806.02070)

##### PDF
[http://arxiv.org/pdf/1806.02070](http://arxiv.org/pdf/1806.02070)

