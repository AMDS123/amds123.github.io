---
layout: post
title: "DTR-GAN: Dilated Temporal Relational Adversarial Network for Video Summarization"
date: 2018-04-30 14:27:24
categories: arXiv_CV
tags: arXiv_CV Adversarial Video_Caption GAN Summarization RNN Relation
author: Yujia Zhang, Michael Kampffmeyer, Xiaodan Liang, Dingwen Zhang, Min Tan, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
The large amount of videos popping up every day, make it is more and more critical that key information within videos can be extracted and understood in a very short time. Video summarization, the task of finding the smallest subset of frames, which still conveys the whole story of a given video, is thus of great significance to improve efficiency of video understanding. In this paper, we propose a novel Dilated Temporal Relational Generative Adversarial Network (DTR-GAN) to achieve frame-level video summarization. Given a video, it can select a set of key frames, which contains the most meaningful and compact information. Specifically, DTR-GAN learns a dilated temporal relational generator and a discriminator with three-player loss in an adversarial manner. A new dilated temporal relation (DTR) unit is introduced for enhancing temporal representation capturing. The generator aims to select key frames by using DTR units to effectively exploit global multi-scale temporal context and to complement the commonly used Bi-LSTM. To ensure that the summaries capture enough key video representation from a global perspective rather than a trivial randomly shorten sequence, we present a discriminator that learns to enforce both the information completeness and compactness of summaries via a three-player loss. The three-player loss includes the generated summary loss, the random summary loss, and the real summary (ground-truth) loss, which play important roles for better regularizing the learned model to obtain useful summaries. Comprehensive experiments on two public datasets SumMe and TVSum show the superiority of our DTR-GAN over the state-of-the-art approaches.

##### Abstract (translated by Google)
大量的视频每天都在出现，因此视频中的关键信息可以在很短的时间内被提取和理解就显得越来越重要。视频摘要是查找帧的最小子集的任务，它仍能传达给定视频的整个故事，因此对提高视频理解的效率具有重要意义。在本文中，我们提出了一种新颖的扩展时间关系生成对抗网络（DTR-GAN）来实现帧级视频摘要。给定一个视频，它可以选择一组关键帧，其中包含最有意义和紧凑的信息。具体而言，DTR-GAN以对抗方式学习了一个扩展的时间关系生成器和一个三人游戏损失的鉴别器。引入了新的扩张时间关系（DTR）单元来增强时间表示捕获。该发生器旨在通过使用DTR单元来有效利用全球多尺度时间背景并补充常用的Bi-LSTM来选择关键帧。为了确保摘要从全局的角度捕捉足够的关键视频表示而不是随机缩短的序列，我们提供了一个鉴别器，通过三名玩家的损失学会强化信息的完整性和总结的紧凑性。三人球员损失包括生成的总结损失，随机总结损失和真实总结（地面实情）损失，这对于更好地规范学习模型以获得有用的总结起着重要作用。对两个公共数据集SumMe和TVSum的综合实验表明，我们的DTR-GAN优于最先进的方法。

##### URL
[https://arxiv.org/abs/1804.11228](https://arxiv.org/abs/1804.11228)

##### PDF
[https://arxiv.org/pdf/1804.11228](https://arxiv.org/pdf/1804.11228)

