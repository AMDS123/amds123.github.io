---
layout: post
title: "Bidirectional Attentive Fusion with Context Gating for Dense Video Captioning"
date: 2018-04-03 08:29:53
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption Prediction
author: Jingwen Wang, Wenhao Jiang, Lin Ma, Wei Liu, Yong Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Dense video captioning is a newly emerging task that aims at both localizing and describing all events in a video. We identify and tackle two challenges on this task, namely, (1) how to utilize both past and future contexts for accurate event proposal predictions, and (2) how to construct informative input to the decoder for generating natural event descriptions. First, previous works predominantly generate temporal event proposals in the forward direction, which neglects future video context. We propose a bidirectional proposal method that effectively exploits both past and future contexts to make proposal predictions. Second, different events ending at (nearly) the same time are indistinguishable in the previous works, resulting in the same captions. We solve this problem by representing each event with an attentive fusion of hidden states from the proposal module and video contents (e.g., C3D features). We further propose a novel context gating mechanism to balance the contributions from the current event and its surrounding contexts dynamically. We empirically show that our attentively fused event representation is superior to the proposal hidden states or video contents alone. By coupling proposal and captioning modules into one unified framework, our model outperforms the state-of-the-arts on the ActivityNet Captions dataset with a relative gain of over 100% (Meteor score increases from 4.82 to 9.65).

##### Abstract (translated by Google)
密集视频字幕是一项新兴任务，旨在本地化和描述视频中的所有事件。我们在此任务上识别并解决两个挑战，即（1）如何利用过去和未来的上下文来进行准确的事件提议预测，以及（2）如何构建对解码器的信息输入以生成自然事件描述。首先，先前的作品主要在前向生成时间事件提议，这忽略了未来的视频上下文。我们提出了一种双向提议方法，可以有效地利用过去和未来的上下文来进行提案预测。其次，在（几乎）同一时间结束的不同事件在先前的作品中是难以区分的，从而产生相同的字幕。我们通过使用来自提议模块的隐藏状态和视频内容（例如，C3D特征）的细心融合来表示每个事件来解决该问题。我们进一步提出了一种新的上下文门控机制，以动态地平衡当前事件及其周围环境的贡献。我们凭经验表明，我们专注的融合事件表示优于单独的提议隐藏状态或视频内容。通过将提案和字幕模块耦合到一个统一的框架中，我们的模型优于ActivityNet Captions数据集的最新技术，相对增益超过100％（Meteor得分从4.82增加到9.65）。

##### URL
[https://arxiv.org/abs/1804.00100](https://arxiv.org/abs/1804.00100)

##### PDF
[https://arxiv.org/pdf/1804.00100](https://arxiv.org/pdf/1804.00100)

