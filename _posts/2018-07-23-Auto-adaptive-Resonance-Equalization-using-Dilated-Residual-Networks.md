---
layout: post
title: "Auto-adaptive Resonance Equalization using Dilated Residual Networks"
date: 2018-07-23 14:18:56
categories: arXiv_SD
tags: arXiv_SD
author: Maarten Grachten, Emmanuel Deruty, Alexandre Tanguy
mathjax: true
---

* content
{:toc}

##### Abstract
In music and audio production, attenuation of spectral resonances is an important step towards a technically correct result. In this paper we present a two-component system to automate the task of resonance equalization. The first component is a dynamic equalizer that automatically detects resonances and offers to attenuate them by a user-specified factor. The second component is a deep neural network that predicts the optimal attenuation factor based on the windowed audio. The network is trained and validated on empirical data gathered from an experiment in which sound engineers choose their preferred attenuation factors for a set of tracks. We test two distinct network architectures for the predictive model and find that a dilated residual network operating directly on the audio signal is on a par with a network architecture that requires a prior audio feature extraction stage. Both architectures predict human-preferred resonance attenuation factors significantly better than a baseline approach.

##### Abstract (translated by Google)
在音乐和音频制作中，频谱共振的衰减是朝着技术上正确的结果迈出的重要一步。在本文中，我们提出了一个双组分系统来自动完成共振均衡任务。第一个组件是动态均衡器，可自动检测共振，并根据用户指定的因子对其进行衰减。第二个组件是深度神经网络，它根据窗口音频预测最佳衰减系数。该网络是根据从实验中收集的经验数据进行训练和验证的，其中声音工程师为一组轨道选择其首选衰减系数。我们为预测模型测试了两种不同的网络架构，发现直接在音频信号上运行的扩张的剩余网络与需要先前音频特征提取阶段的网络架构相当。两种架构都预测人类优选的共振衰减因子明显优于基线方法。

##### URL
[http://arxiv.org/abs/1807.08636](http://arxiv.org/abs/1807.08636)

##### PDF
[http://arxiv.org/pdf/1807.08636](http://arxiv.org/pdf/1807.08636)

