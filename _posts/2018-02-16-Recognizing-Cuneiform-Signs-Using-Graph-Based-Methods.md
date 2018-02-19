---
layout: post
title: "Recognizing Cuneiform Signs Using Graph Based Methods"
date: 2018-02-16 12:28:28
categories: arXiv_CV
tags: arXiv_CV Classification Prediction
author: Nils M. Kriege, Matthias Fey, Denis Fisseler, Petra Mutzel, Frank Weichert
mathjax: true
---

* content
{:toc}

##### Abstract
The cuneiform script constitutes one of the earliest systems of writing and is realized by wedge-shaped marks on clay tablets. A tremendous number of cuneiform tablets have already been discovered and are incrementally digitalized and made available to automated processing. As reading cuneiform script is still a manual task, we address the real-world application of recognizing cuneiform signs by two graph based methods with complementary runtime characteristics. We present a graph model for cuneiform signs together with a tailored distance measure based on the concept of the graph edit distance. We propose efficient heuristics for its computation and demonstrate its effectiveness in classification tasks experimentally. To this end, the distance measure is used to implement a nearest neighbor classifier leading to a high computational cost for the prediction phase with increasing training set size. In order to overcome this issue, we propose to use CNNs adapted to graphs as an alternative approach shifting the computational cost to the training phase. We demonstrate the practicability of both approaches in an extensive experimental comparison regarding runtime and prediction accuracy. Although currently available annotated real-world data is still limited, we obtain a high accuracy using CNNs, in particular, when the training set is enriched by augmented examples.

##### Abstract (translated by Google)
楔形文字是最早的写作系统之一，通过粘土片上的楔形标记实现。已经发现了大量的楔形文字片剂，并且逐渐数字化并可用于自动处理。由于阅读楔形文字仍然是一项手动任务，我们通过具有互补运行时特性的两种基于图形的方法来处理识别楔形文字符号的现实应用。我们根据图编辑距离的概念给出楔形符号的图模型以及定制的距离度量。我们针对其计算提出了有效的启发式方法，并通过实验证明了其在分类任务中的有效性为此，距离度量用于实现最近邻分类器，导致预测阶段的高计算成本，同时增加训练集大小。为了克服这个问题，我们建议使用适合于图的CNNs作为将计算成本转移到训练阶段的替代方法。我们在关于运行时间和预测精度的广泛实验比较中证明了这两种方法的实用性。尽管目前可用的带注释的真实世界数据仍然有限，但我们使用CNN获得高准确性，特别是当训练集由增强示例丰富时。

##### URL
[https://arxiv.org/abs/1802.05908](https://arxiv.org/abs/1802.05908)

##### PDF
[https://arxiv.org/pdf/1802.05908](https://arxiv.org/pdf/1802.05908)

