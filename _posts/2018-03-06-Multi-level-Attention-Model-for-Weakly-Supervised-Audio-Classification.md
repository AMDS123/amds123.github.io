---
layout: post
title: "Multi-level Attention Model for Weakly Supervised Audio Classification"
date: 2018-03-06 15:59:21
categories: arXiv_SD
tags: arXiv_SD Attention Weakly_Supervised Classification Prediction
author: Changsong Yu, Karim Said Barsim, Qiuqiang Kong, Bin Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a multi-level attention model to solve the weakly labelled audio classification problem. The objective of audio classification is to predict the presence or absence of audio events in an audio clip. Recently, Google published a large scale weakly labelled dataset called Audio Set, where each audio clip contains only the presence or absence of the audio events, without the onset and offset time of the audio events. Our multi-level attention model is an extension to the previously proposed single-level attention model. It consists of several attention modules applied on intermediate neural network layers. The output of these attention modules are concatenated to a vector followed by a multi-label classifier to make the final prediction of each class. Experiments shown that our model achieves a mean average precision (mAP) of 0.360, outperforms the state-of-the-art single-level attention model of 0.327 and Google baseline of 0.314.

##### Abstract (translated by Google)
在本文中，我们提出了一个多层次的关注模型来解决弱标记的音频分类问题。音频分类的目的是预测音频剪辑中音频事件的存在与否。最近，Google发布了一个名为Audio Set的大规模弱标记数据集，其中每个音频片段仅包含音频事件的存在或不存在，没有音频事件的开始和偏移时间。我们的多层次关注模型是对先前提出的单层关注模型的扩展。它由几个应用于中间神经网络层的注意模块组成。这些关注模块的输出连接到一个矢量，然后是多标签分类器，以对每个类进行最终预测。实验表明，我们的模型达到0.360的平均平均精确度（mAP），优于最新的0.327单级关注模型和0.314的Google基线。

##### URL
[http://arxiv.org/abs/1803.02353](http://arxiv.org/abs/1803.02353)

##### PDF
[http://arxiv.org/pdf/1803.02353](http://arxiv.org/pdf/1803.02353)

