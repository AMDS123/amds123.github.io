---
layout: post
title: "T-RECS: Training for Rate-Invariant Embeddings by Controlling Speed for Action Recognition"
date: 2018-03-23 04:11:36
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Embedding RNN Recognition
author: Madan Ravi Ganesh, Eric Hofesmann, Byungsu Min, Nadha Gafoor, Jason J. Corso
mathjax: true
---

* content
{:toc}

##### Abstract
An action should remain identifiable when modifying its speed: consider the contrast between an expert chef and a novice chef each chopping an onion. Here, we expect the novice chef to have a relatively measured and slow approach to chopping when compared to the expert. In general, the speed at which actions are performed, whether slower or faster than average, should not dictate how they are recognized. We explore the erratic behavior caused by this phenomena on state-of-the-art deep network-based methods for action recognition in terms of maximum performance and stability in recognition accuracy across a range of input video speeds. By observing the trends in these metrics and summarizing them based on expected temporal behaviour w.r.t. variations in input video speeds, we find two distinct types of network architectures. In this paper, we propose a preprocessing method named T-RECS, as a way to extend deep-network-based methods for action recognition to explicitly account for speed variability in the data. We do so by adaptively resampling the inputs to a given model. T-RECS is agnostic to the specific deep-network model; we apply it to four state-of-the-art action recognition architectures, C3D, I3D, TSN, and ConvNet+LSTM. On HMDB51 and UCF101, T-RECS-based I3D models show a peak improvement of at least 2.9% in performance over the baseline while T-RECS-based C3D models achieve a maximum improvement in stability by 59% over the baseline, on the HMDB51 dataset.

##### Abstract (translated by Google)
在改变速度时应该保持可识别的行为：考虑专家厨师和新手厨师每次切碎洋葱时的对比。在这里，我们预计新手厨师与专家相比，会有相对测量和缓慢的切入方法。一般来说，执行动作的速度，无论速度是否慢于平均速度，都不应决定如何识别它们。我们探索由这种现象引起的不稳定行为，这种现象是针对动作识别的最先进的基于深度网络的方法，在输入视频速度范围内的最大性能和识别准确度的稳定性方面。通过观察这些指标的趋势并根据预期的时间行为对其进行总结。输入视频速度的变化，我们发现两种不同类型的网络架构。在本文中，我们提出了一种名为T-RECS的预处理方法，作为一种扩展基于深度网络的动作识别方法，以明确说明数据中的速度变化。我们通过对给定模型的输入进行自适应重新采样来实现这一点。 T-RECS对特定的深度网络模型是不可知的;我们将它应用于四个最先进的动作识别架构，C3D，I3D，TSN和ConvNet + LSTM。在HMDB51和UCF101上，与基线相比，基于T-RECS的I3D模型在性能方面表现出至少2.9％的峰值改善，而基于T-RECS的C3D模型在基线上稳定性最大改善59％数据集。

##### URL
[https://arxiv.org/abs/1803.08094](https://arxiv.org/abs/1803.08094)

##### PDF
[https://arxiv.org/pdf/1803.08094](https://arxiv.org/pdf/1803.08094)

