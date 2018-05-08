---
layout: post
title: "A Data-Driven Approach to Smooth Pitch Correction for Singing Voice in Pop Music"
date: 2018-05-07 16:32:39
categories: arXiv_SD
tags: arXiv_SD Tracking RNN
author: Sanna Wager, Lijiang Guo, Aswin Sivaraman, Minje Kim
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a machine-learning approach to pitch correction for voice in a karaoke setting, where the vocals and accompaniment are on separate tracks and time-aligned. The network takes as input the time-frequency representation of the two tracks and predicts the amount of pitch-shifting in cents required to make the voice sound in-tune with the accompaniment. It is trained on examples of semi-professional singing. The proposed approach differs from existing real-time pitch correction methods by replacing pitch tracking and mapping to a discrete set of notes---for example, the twelve classes of the equal-tempered scale---with learning a correction that is continuous both in frequency and in time directly from the harmonics of the vocal and accompaniment tracks. A Recurrent Neural Network (RNN) model provides a correction that takes context into account, preserving expressive pitch bending and vibrato. This method can be extended into unsupervised pitch correction of a vocal performance---popularly referred to as autotuning.

##### Abstract (translated by Google)
在本文中，我们提出了一种机器学习方法来对卡拉OK设置中的声音进行音高修正，其中人声和伴奏位于单独的轨道上并且时间对齐。网络以两个轨道的时频表示为输入，并预测使声音与伴奏声音一致所需的音高变化量。它训练半专业演唱的例子。所提出的方法不同于现有的实时音调修正方法，通过将音调跟踪和映射替换为一组离散的音符 - 例如，12个相同音程的音阶 - 学习连续的修正在频率和时间上直接来自声乐和伴奏音轨的谐波。递归神经网络（RNN）模型提供了一种考虑背景的校正，保留了表现性的音高弯曲和颤音。这种方法可以扩展到声音表演的无监督俯仰校正---通常称为自动调谐。

##### URL
[http://arxiv.org/abs/1805.02603](http://arxiv.org/abs/1805.02603)

##### PDF
[http://arxiv.org/pdf/1805.02603](http://arxiv.org/pdf/1805.02603)

