---
layout: post
title: "Improving Trajectory Modelling for DNN-based Speech Synthesis by using Stacked Bottleneck Features and Minimum Generation Error Training"
date: 2016-04-05 11:31:02
categories: arXiv_SD
tags: arXiv_SD RNN Relation
author: Zhizheng Wu, Simon King
mathjax: true
---

* content
{:toc}

##### Abstract
We propose two novel techniques --- stacking bottleneck features and minimum generation error training criterion --- to improve the performance of deep neural network (DNN)-based speech synthesis. The techniques address the related issues of frame-by-frame independence and ignorance of the relationship between static and dynamic features, within current typical DNN-based synthesis frameworks. Stacking bottleneck features, which are an acoustically--informed linguistic representation, provides an efficient way to include more detailed linguistic context at the input. The minimum generation error training criterion minimises overall output trajectory error across an utterance, rather than minimising the error per frame independently, and thus takes into account the interaction between static and dynamic features. The two techniques can be easily combined to further improve performance. We present both objective and subjective results that demonstrate the effectiveness of the proposed techniques. The subjective results show that combining the two techniques leads to significantly more natural synthetic speech than from conventional DNN or long short-term memory (LSTM) recurrent neural network (RNN) systems.

##### Abstract (translated by Google)
为了提高基于深度神经网络（DNN）的语音合成的性能，我们提出了两种新的技术 - 叠加瓶颈特征和最小生成误差训练准则。这些技术在当前典型的基于DNN的综合框架内解决了逐帧独立性的相关问题以及静态和动态特征之间关系的无知。叠加的瓶颈功能，这是一个声学的语言表达，提供了一个有效的方式，包括更详细的语言环境在输入。最小生成误差训练标准最大限度地减少了整个话语中的总体输出轨迹误差，而不是最小化每帧的误差，因此考虑到静态和动态特征之间的相互作用。这两种技术可以很容易地结合起来，进一步提高性能。我们提出的客观和主观结果都证明了所提出技术的有效性。主观结果表明，结合这两种技术导致显着更多的自然合成语音比传统的DNN或长期短期记忆（LSTM）递归神经网络（RNN）系统。

##### URL
[https://arxiv.org/abs/1602.06727](https://arxiv.org/abs/1602.06727)

##### PDF
[https://arxiv.org/pdf/1602.06727](https://arxiv.org/pdf/1602.06727)

