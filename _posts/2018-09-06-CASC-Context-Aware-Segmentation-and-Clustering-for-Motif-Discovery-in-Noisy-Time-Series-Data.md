---
layout: post
title: "CASC: Context-Aware Segmentation and Clustering for Motif Discovery in Noisy Time Series Data"
date: 2018-09-06 04:50:08
categories: arXiv_AI
tags: arXiv_AI Segmentation Optimization
author: Saachi Jain, David Hallac, Rok Sosic, Jure Leskovec
mathjax: true
---

* content
{:toc}

##### Abstract
Complex systems, such as airplanes, cars, or financial markets, produce multivariate time series data consisting of system observations over a period of time. Such data can be interpreted as a sequence of segments, where each segment is associated with a certain state of the system. An important problem in this domain is to identify repeated sequences of states, known as motifs. Such motifs correspond to complex behaviors that capture common sequences of state transitions. For example, a motif of "making a turn" might manifest in sensor data as a sequence of states: slowing down, turning the wheel, and then speeding back up. However, discovering these motifs is challenging, because the individual states are unknown and need to be learned from the noisy time series. Simultaneously, the time series also needs to be precisely segmented and each segment needs to be associated with a state. Here we develop context-aware segmentation and clustering (CASC), a method for discovering common motifs in time series data. We formulate the problem of motif discovery as a large optimization problem, which we then solve using a greedy alternating minimization-based approach. CASC performs well in the presence of noise in the input data and is scalable to very large datasets. Furthermore, CASC leverages common motifs to more robustly segment the time series and assign segments to states. Experiments on synthetic data show that CASC outperforms state-of-the-art baselines by up to 38.2%, and two case studies demonstrate how our approach discovers insightful motifs in real-world time series data.

##### Abstract (translated by Google)
复杂系统，如飞机，汽车或金融市场，产生多变量时间序列数据，包括一段时间内的系统观测。这样的数据可以被解释为段的序列，其中每个段与系统的特定状态相关联。该领域中的一个重要问题是识别重复的状态序列，称为基序。这些图案对应于捕获状态转换的常见序列的复杂行为。例如，“转弯”的主题可能会在传感器数据中显示为一系列状态：减速，转动车轮，然后加速返回。然而，发现这些图案是具有挑战性的，因为个别状态是未知的，需要从嘈杂的时间序列中学习。同时，时间序列也需要精确分割，每个分段都需要与状态相关联。在这里，我们开发了上下文感知分段和聚类（CASC），一种用于发现时间序列数据中的共同主题的方法。我们将主题发现的问题表述为一个大的优化问题，然后我们使用贪婪的交替最小化方法来解决。 CASC在输入数据中存在噪声时表现良好，并且可扩展到非常大的数据集。此外，CASC利用共同的主题来更加稳健地划分时间序列并将段分配给州。对合成数据的实验表明，CASC的表现优于最先进的基线高达38.2％，两个案例研究证明了我们的方法如何在现实世界的时间序列数据中发现有洞察力的图案。

##### URL
[http://arxiv.org/abs/1809.01819](http://arxiv.org/abs/1809.01819)

##### PDF
[http://arxiv.org/pdf/1809.01819](http://arxiv.org/pdf/1809.01819)

