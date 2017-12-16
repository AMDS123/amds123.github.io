---
layout: post
title: "End-to-End Multi-View Lipreading"
date: 2017-09-01 18:51:53
categories: arXiv_CV
tags: arXiv_CV Knowledge RNN Classification Deep_Learning
author: Stavros Petridis, Yujiang Wang, Zuwei Li, Maja Pantic
mathjax: true
---

* content
{:toc}

##### Abstract
Non-frontal lip views contain useful information which can be used to enhance the performance of frontal view lipreading. However, the vast majority of recent lipreading works, including the deep learning approaches which significantly outperform traditional approaches, have focused on frontal mouth images. As a consequence, research on joint learning of visual features and speech classification from multiple views is limited. In this work, we present an end-to-end multi-view lipreading system based on Bidirectional Long-Short Memory (BLSTM) networks. To the best of our knowledge, this is the first model which simultaneously learns to extract features directly from the pixels and performs visual speech classification from multiple views and also achieves state-of-the-art performance. The model consists of multiple identical streams, one for each view, which extract features directly from different poses of mouth images. The temporal dynamics in each stream/view are modelled by a BLSTM and the fusion of multiple streams/views takes place via another BLSTM. An absolute average improvement of 3% and 3.8% over the frontal view performance is reported on the OuluVS2 database when the best two (frontal and profile) and three views (frontal, profile, 45) are combined, respectively. The best three-view model results in a 10.5% absolute improvement over the current multi-view state-of-the-art performance on OuluVS2, without using external databases for training, achieving a maximum classification accuracy of 96.9%.

##### Abstract (translated by Google)
非正面的嘴唇视图包含有用的信息，可用于提高正面视图的唇部表现。然而，近年来绝大多数的唇读作品，包括远远超过传统方法的深度学习方法，都集中在正面的嘴部图像上。因此，从多个角度研究视觉特征和语音分类的联合学习是有限的。在这项工作中，我们提出了一个基于双向长短内存（BLSTM）网络的端到端多视图唇读系统。就我们所知，这是第一个同时学习从像素中直接提取特征并从多个视角进行视觉语音分类的模型，同时也实现了最先进的性能。该模型由多个相同的流组成，每个视图对应一个视图，直接从不同的嘴巴图像中提取特征。每个流/视图中的时间动态是由BLSTM建模的，而多个流/视图的融合是通过另一个BLSTM进行的。 OuluVS2数据库报告的正面视图性能绝对平均提高3％和3.8％，分别将最好的两个（正面和剖面）和三个视图（正面，剖面45）组合在一起。最佳的三视图模型比OuluVS2的当前多视图最先进的性能提高了10.5％，而不使用外部数据库进行训练，实现了96.9％的最大分类准确率。

##### URL
[https://arxiv.org/abs/1709.00443](https://arxiv.org/abs/1709.00443)

##### PDF
[https://arxiv.org/pdf/1709.00443](https://arxiv.org/pdf/1709.00443)

