---
layout: post
title: "Two-stream Collaborative Learning with Spatial-Temporal Attention for Video Classification"
date: 2017-11-09 06:49:21
categories: arXiv_CV
tags: arXiv_CV Salient Attention Video_Classification Classification Relation
author: Yuxin Peng, Yunzhen Zhao, Junchao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Video classification is highly important with wide applications, such as video search and intelligent surveillance. Video naturally consists of static and motion information, which can be represented by frame and optical flow. Recently, researchers generally adopt the deep networks to capture the static and motion information \textbf{\emph{separately}}, which mainly has two limitations: (1) Ignoring the coexistence relationship between spatial and temporal attention, while they should be jointly modelled as the spatial and temporal evolutions of video, thus discriminative video features can be extracted.(2) Ignoring the strong complementarity between static and motion information coexisted in video, while they should be collaboratively learned to boost each other. For addressing the above two limitations, this paper proposes the approach of two-stream collaborative learning with spatial-temporal attention (TCLSTA), which consists of two models: (1) Spatial-temporal attention model: The spatial-level attention emphasizes the salient regions in frame, and the temporal-level attention exploits the discriminative frames in video. They are jointly learned and mutually boosted to learn the discriminative static and motion features for better classification performance. (2) Static-motion collaborative model: It not only achieves mutual guidance on static and motion information to boost the feature learning, but also adaptively learns the fusion weights of static and motion streams, so as to exploit the strong complementarity between static and motion information to promote video classification. Experiments on 4 widely-used datasets show that our TCLSTA approach achieves the best performance compared with more than 10 state-of-the-art methods.

##### Abstract (translated by Google)
视频分类对于视频搜索和智能监控等广泛的应用非常重要。视频自然由静态和运动信息组成，可以用帧和光流来表示。最近，研究者普遍采用深度网络来捕捉静态和动态信息，主要有两个局限性：（1）忽略空间和时间关注的共存关系，而应该共同建模（2）忽视静态信息和运动信息在视频中共存的强互补性，同时要协同学习，相互促进。为解决上述两个局限性，本文提出了一种具有时空关注的双流协同学习方法（TCLSTA），它包括两个模型：（1）空间 - 时间关注模型：空间关注强调显着性区域在帧中，并且时间层面的注意力利用了视频中的判别性帧。他们共同学习，相互促进，学习有区别的静态和动作特征，以获得更好的分类性能。 （2）静态协同模型：不仅实现了静态和动态信息的互相引导，促进了特征学习，而且自适应地学习了静态和动态流的融合权重，从而利用静态和动态之间的强互补性信息推广视频分类。 4个广泛使用的数据集上的实验表明，与超过10个最先进的方法相比，我们的TCLSTA方法实现了最佳的性能。

##### URL
[https://arxiv.org/abs/1711.03273](https://arxiv.org/abs/1711.03273)

##### PDF
[https://arxiv.org/pdf/1711.03273](https://arxiv.org/pdf/1711.03273)

