---
layout: post
title: "Second-order Temporal Pooling for Action Recognition"
date: 2018-08-07 01:38:50
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Embedding Deep_Learning Relation Recognition
author: Anoop Cherian, Stephen Gould
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning models for video-based action recognition usually generate features for short clips (consisting of a few frames); such clip-level features are aggregated to video-level representations by computing statistics on these features. Typically zero-th (max) or the first-order (average) statistics are used. In this paper, we explore the benefits of using second-order statistics. Specifically, we propose a novel end-to-end learnable feature aggregation scheme, dubbed temporal correlation pooling that generates an action descriptor for a video sequence by capturing the similarities between the temporal evolution of clip-level CNN features computed across the video. Such a descriptor, while being computationally cheap, also naturally encodes the co-activations of multiple CNN features, thereby providing a richer characterization of actions than their first-order counterparts. We also propose higher-order extensions of this scheme by computing correlations after embedding the CNN features in a reproducing kernel Hilbert space. We provide experiments on benchmark datasets such as HMDB-51 and UCF-101, fine-grained datasets such as MPII Cooking activities and JHMDB, as well as the recent Kinetics-600. Our results demonstrate the advantages of higher-order pooling schemes that when combined with hand-crafted features (as is standard practice) achieves state-of-the-art accuracy.

##### Abstract (translated by Google)
基于视频的动作识别的深度学习模型通常会生成短片的特征（由几帧组成）;通过计算这些特征的统计数据，这些剪辑级特征被聚合到视频级表示。通常使用零（最大）或一阶（平均）统计。在本文中，我们探讨了使用二阶统计量的好处。具体而言，我们提出了一种新颖的端到端可学习特征聚合方案，称为时间相关池，其通过捕获在视频上计算的剪辑级CNN特征的时间演变之间的相似性来生成视频序列的动作描述符。这样的描述符虽然在计算上便宜，但也自然地编码多个CNN特征的共同激活，从而提供比它们的一阶对应物更丰富的动作表征。我们还通过在再生内核Hilbert空间中嵌入CNN特征之后计算相关性来提出该方案的高阶扩展。我们提供基准数据集的实验，如HMDB-51和UCF-101，细粒度数据集，如MPII烹饪活动和JHMDB，以及最近的Kinetics-600。我们的结果证明了高阶汇集方案的优势，当与手工制作的特征（标准实践）相结合时，可以实现最先进的精度。

##### URL
[http://arxiv.org/abs/1704.06925](http://arxiv.org/abs/1704.06925)

##### PDF
[http://arxiv.org/pdf/1704.06925](http://arxiv.org/pdf/1704.06925)

