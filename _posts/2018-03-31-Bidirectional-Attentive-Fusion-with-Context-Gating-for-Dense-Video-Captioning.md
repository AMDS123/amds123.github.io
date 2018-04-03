---
layout: post
title: "Bidirectional Attentive Fusion with Context Gating for Dense Video Captioning"
date: 2018-03-31 01:08:33
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
密集视频字幕是一项新兴的任务，旨在对视频中的所有事件进行本地化和描述。 （1）如何利用过去和未来的背景来准确预测事件提议，以及（2）如何为解码器生成自然事件描述的信息输入。首先，以前的作品主要在前进方向上产生时间事件提议，这忽略了未来的视频情境。我们提出了一种双向提案方法，有效利用过去和未来的背景来进行提案预测。其次，在（几乎）同时结束的不同事件在以前的作品中难以区分，导致相同的标题。我们通过用提案模块和视频内容（例如，C3D特征）的隐藏状态的周密融合表示每个事件来解决这个问题。我们进一步提出了一种新颖的情景门控机制来动态地平衡当前事件及其周围情境的贡献。我们凭经验表明，我们精心融合的事件表示优于仅隐藏状态或视频内容的提议。通过将提议和字幕模块整合到一个统一的框架中，我们的模型在ActivityNet Captions数据集上的表现优于现有技术，相对增益超过100％（流星得分从4.82增加到9.65）。

##### URL
[http://arxiv.org/abs/1804.00100](http://arxiv.org/abs/1804.00100)

##### PDF
[http://arxiv.org/pdf/1804.00100](http://arxiv.org/pdf/1804.00100)

