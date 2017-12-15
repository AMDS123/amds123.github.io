---
layout: post
title: "LipNet: End-to-End Sentence-level Lipreading"
date: 2016-12-16 16:09:34
categories: arXiv_CL
tags: arXiv_CL Knowledge Classification Prediction
author: Yannis M. Assael, Brendan Shillingford, Shimon Whiteson, Nando de Freitas
mathjax: true
---

* content
{:toc}

##### Abstract
Lipreading is the task of decoding text from the movement of a speaker's mouth. Traditional approaches separated the problem into two stages: designing or learning visual features, and prediction. More recent deep lipreading approaches are end-to-end trainable (Wand et al., 2016; Chung & Zisserman, 2016a). However, existing work on models trained end-to-end perform only word classification, rather than sentence-level sequence prediction. Studies have shown that human lipreading performance increases for longer words (Easton & Basala, 1982), indicating the importance of features capturing temporal context in an ambiguous communication channel. Motivated by this observation, we present LipNet, a model that maps a variable-length sequence of video frames to text, making use of spatiotemporal convolutions, a recurrent network, and the connectionist temporal classification loss, trained entirely end-to-end. To the best of our knowledge, LipNet is the first end-to-end sentence-level lipreading model that simultaneously learns spatiotemporal visual features and a sequence model. On the GRID corpus, LipNet achieves 95.2% accuracy in sentence-level, overlapped speaker split task, outperforming experienced human lipreaders and the previous 86.4% word-level state-of-the-art accuracy (Gergen et al., 2016).

##### Abstract (translated by Google)
读音是解码说话者嘴巴运动的文本。传统的方法将问题分为两个阶段：设计或学习视觉特征和预测。最近的深度阅读方法是端到端的可训练（Wand等，2016; Chung＆Zisserman，2016a）。然而，现有的关于端到端训练模型的工作只能执行单词分类，而不是句子级序列预测。研究表明，对于更长的单词，人类的唇读性能会增加（Easton＆Basala，1982），这表明在模糊的通信通道中捕获时间上下文的特征的重要性。受此观察的启发，我们展示了LipNet，一种将可变长度的视频帧序列映射到文本的模型，利用时空卷积，循环网络和连接主义时态分类丢失，完全端对端地训练。据我们所知，LipNet是第一个同时学习时空视觉特征和序列模型的端到端句级水平的唇读模型。在网格语料库上，LipNet的句子级别准确度达到了95.2％，重叠的说话者分裂任务，超过了经验丰富的人类唇膏和先前的86.4％字水平的最新准确度（Gergen et al。，2016）。

##### URL
[https://arxiv.org/abs/1611.01599](https://arxiv.org/abs/1611.01599)

##### PDF
[https://arxiv.org/pdf/1611.01599](https://arxiv.org/pdf/1611.01599)

