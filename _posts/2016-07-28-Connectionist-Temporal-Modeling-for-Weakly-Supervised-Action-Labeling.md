---
layout: post
title: "Connectionist Temporal Modeling for Weakly Supervised Action Labeling"
date: 2016-07-28 19:35:50
categories: arXiv_CV
tags: arXiv_CV Sparse Weakly_Supervised Classification
author: De-An Huang, Li Fei-Fei, Juan Carlos Niebles
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a weakly-supervised framework for action labeling in video, where only the order of occurring actions is required during training time. The key challenge is that the per-frame alignments between the input (video) and label (action) sequences are unknown during training. We address this by introducing the Extended Connectionist Temporal Classification (ECTC) framework to efficiently evaluate all possible alignments via dynamic programming and explicitly enforce their consistency with frame-to-frame visual similarities. This protects the model from distractions of visually inconsistent or degenerated alignments without the need of temporal supervision. We further extend our framework to the semi-supervised case when a few frames are sparsely annotated in a video. With less than 1% of labeled frames per video, our method is able to outperform existing semi-supervised approaches and achieve comparable performance to that of fully supervised approaches.

##### Abstract (translated by Google)
我们提出了一个视频行动标签的弱监督框架，在训练期间只需要发生的动作顺序。关键的挑战是输入（视频）和标签（动作）序列之间的每帧对齐在训练期间是未知的。我们通过引入扩展连接主义时间分类（ECTC）框架来解决这个问题，以通过动态编程有效地评估所有可能的对齐，并明确地强化它们与帧到帧视觉相似性的一致性。这可以保护模型免受视觉不一致或退化的路线干扰，而不需要时间监督。我们进一步将我们的框架扩展到半监督的情况，当少数帧被稀疏地注释在一个视频。每个视频的标签帧数少于1％，我们的方法能够胜过现有的半监督方法，并且实现了与完全监督方法相当的性能。

##### URL
[https://arxiv.org/abs/1607.08584](https://arxiv.org/abs/1607.08584)

##### PDF
[https://arxiv.org/pdf/1607.08584](https://arxiv.org/pdf/1607.08584)

