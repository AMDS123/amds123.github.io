---
layout: post
title: "Modeling Singing F0 With Neural Network Driven Transition-Sustain Models"
date: 2018-03-11 19:55:02
categories: arXiv_SD
tags: arXiv_SD Prediction
author: Kanru Hua
mathjax: true
---

* content
{:toc}

##### Abstract
This study focuses on generating fundamental frequency (F0) curves of singing voice from musical scores stored in a midi-like notation. Current statistical parametric approaches to singing F0 modeling meet difficulties in reproducing vibratos and the temporal details at note boundaries due to the oversmoothing tendency of statistical models. This paper presents a neural network based solution that models a pair of neighboring notes at a time (the transition model) and uses a separate network for generating vibratos (the sustain model). Predictions from the two models are combined by summation after proper enveloping to enforce continuity. In the training phase, mild misalignment between the scores and the target F0 is addressed by back-propagating the gradients to the networks' inputs. Subjective listening tests on the NITech singing database show that transition-sustain models are able to generate F0 trajectories close to the original performance.

##### Abstract (translated by Google)
这项研究的重点是从储存在midi-like符号中的乐谱中产生歌声的基频（F0）曲线。由于统计模型的过度平滑趋势，当前用于唱歌F0建模的统计参数方法在音符边界处再现颤音和时间细节方面遇到困难。本文提出了一种基于神经网络的解决方案，一次模拟一对相邻音符（转换模型），并使用单独的网络来产生颤音（维持模型）。通过适当的包络来加强连续性，两个模型的预测结合在一起。在训练阶段，分数与目标F0之间的轻微偏差通过向网络输入反向传播梯度来解决。 NITech唱歌数据库的主观听力测试表明，转换维持模型能够产生接近原始性能的F0轨迹。

##### URL
[https://arxiv.org/abs/1803.04030](https://arxiv.org/abs/1803.04030)

##### PDF
[https://arxiv.org/pdf/1803.04030](https://arxiv.org/pdf/1803.04030)

