---
layout: post
title: "Indirect Match Highlights Detection with Deep Convolutional Neural Networks"
date: 2017-10-02 10:14:41
categories: arXiv_CV
tags: arXiv_CV Attention CNN Detection
author: Marco Godi, Paolo Rota, Francesco Setti
mathjax: true
---

* content
{:toc}

##### Abstract
Highlights in a sport video are usually referred as actions that stimulate excitement or attract attention of the audience. A big effort is spent in designing techniques which find automatically highlights, in order to automatize the otherwise manual editing process. Most of the state-of-the-art approaches try to solve the problem by training a classifier using the information extracted on the tv-like framing of players playing on the game pitch, learning to detect game actions which are labeled by human observers according to their perception of highlight. Obviously, this is a long and expensive work. In this paper, we reverse the paradigm: instead of looking at the gameplay, inferring what could be exciting for the audience, we directly analyze the audience behavior, which we assume is triggered by events happening during the game. We apply deep 3D Convolutional Neural Network (3D-CNN) to extract visual features from cropped video recordings of the supporters that are attending the event. Outputs of the crops belonging to the same frame are then accumulated to produce a value indicating the Highlight Likelihood (HL) which is then used to discriminate between positive (i.e. when a highlight occurs) and negative samples (i.e. standard play or time-outs). Experimental results on a public dataset of ice-hockey matches demonstrate the effectiveness of our method and promote further research in this new exciting direction.

##### Abstract (translated by Google)
运动视频中的亮点通常被称为刺激兴奋或引起观众注意的动作。为了自动化手动编辑过程，花费大量的精力来设计自动突出显示的技术。大多数现有技术的方法试图通过使用在玩游戏音调的玩家的电视状框架上提取的信息来训练分类器来解决该问题，学习检测由人类观察者标记的游戏动作以他们的看法为重点。显然，这是一个漫长而昂贵的工作。在本文中，我们颠覆了范式：不是看游戏玩法，而是推断令观众感到兴奋的东西，我们直接分析观众的行为，我们假设这是由游戏过程中发生的事件触发的。我们应用深度3D卷积神经网络（3D-CNN）从参加活动的支持者的裁剪录像中提取视觉特征。然后累计属于同一帧的作物的输出，以产生表示高亮似然性（HL）的值，然后用该高度似然性来区分正片（即高亮出现时）和负片样（即标准播放或超时） 。在冰球比赛的公开数据集上的实验结果证明了我们的方法的有效性，并促进了这个新的激动人心的方向进一步的研究。

##### URL
[https://arxiv.org/abs/1710.00568](https://arxiv.org/abs/1710.00568)

##### PDF
[https://arxiv.org/pdf/1710.00568](https://arxiv.org/pdf/1710.00568)

