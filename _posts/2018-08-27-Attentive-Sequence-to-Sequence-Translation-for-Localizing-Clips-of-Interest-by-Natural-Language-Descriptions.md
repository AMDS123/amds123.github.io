---
layout: post
title: "Attentive Sequence to Sequence Translation for Localizing Clips of Interest by Natural Language Descriptions"
date: 2018-08-27 12:01:26
categories: arXiv_CV
tags: arXiv_CV RNN
author: Ke Ning, Linchao Zhu, Ming Cai, Yi Yang, Di Xie, Fei Wu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel attentive sequence to sequence translator (ASST) for clip localization in videos by natural language descriptions. We make two contributions. First, we propose a bi-directional Recurrent Neural Network (RNN) with a finely calibrated vision-language attentive mechanism to comprehensively understand the free-formed natural language descriptions. The RNN parses natural language descriptions in two directions, and the attentive model attends every meaningful word or phrase to each frame, thereby resulting in a more detailed understanding of video content and description semantics. Second, we design a hierarchical architecture for the network to jointly model language descriptions and video content. Given a video-description pair, the network generates a matrix representation, i.e., a sequence of vectors. Each vector in the matrix represents a video frame conditioned by the description. The 2D representation not only preserves the temporal dependencies of frames but also provides an effective way to perform frame-level video-language matching. The hierarchical architecture exploits video content with multiple granularities, ranging from subtle details to global context. Integration of the multiple granularities yields a robust representation for multi-level video-language abstraction. We validate the effectiveness of our ASST on two large-scale datasets. Our ASST outperforms the state-of-the-art by $4.28\%$ in Rank$@1$ on the DiDeMo dataset. On the Charades-STA dataset, we significantly improve the state-of-the-art by $13.41\%$ in Rank$@1,IoU=0.5$.

##### Abstract (translated by Google)
我们通过自然语言描述提出了一种用于序列翻译器（ASST）的新颖注意序列，用于在视频中进行剪辑定位。我们做了两个贡献。首先，我们提出了一种双向递归神经网络（RNN），其具有精细校准的视觉语言注意机制，以全面理解自由形成的自然语言描述。 RNN在两个方向上解析自然语言描述，并且注意模型在每个帧上参与每个有意义的单词或短语，从而导致对视频内容和描述语义的更详细的理解。其次，我们为网络设计了一个分层架构，以共同模拟语言描述和视频内容。给定视频描述对，网络生成矩阵表示，即矢量序列。矩阵中的每个矢量表示由描述调节的视频帧。 2D表示不仅保留了帧的时间依赖性，还提供了执行帧级视频语言匹配的有效方式。分层体系结构利用多个粒度的视频内容，从细微的细节到全局上下文。多个粒度的集成产生用于多级视频语言抽象的鲁棒表示。我们验证了ASST在两个大型数据集上的有效性。我们的ASST在DiDeMo数据集上的Rank $ @ 1 $中优于现有技术的$ 4.28 \％$。在Charades-STA数据集上，我们在Rank $ @ 1，IoU = 0.5 $中显着提高了最新技术水平$ 13.41 \％$。

##### URL
[http://arxiv.org/abs/1808.08803](http://arxiv.org/abs/1808.08803)

##### PDF
[http://arxiv.org/pdf/1808.08803](http://arxiv.org/pdf/1808.08803)

