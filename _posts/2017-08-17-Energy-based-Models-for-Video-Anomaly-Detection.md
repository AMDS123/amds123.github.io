---
layout: post
title: "Energy-based Models for Video Anomaly Detection"
date: 2017-08-17 11:44:34
categories: arXiv_CV
tags: arXiv_CV Detection
author: Hung Vu, Dinh Phung, Tu Dinh Nguyen, Anthony Trevors, Svetha Venkatesh
mathjax: true
---

* content
{:toc}

##### Abstract
Automated detection of abnormalities in data has been studied in research area in recent years because of its diverse applications in practice including video surveillance, industrial damage detection and network intrusion detection. However, building an effective anomaly detection system is a non-trivial task since it requires to tackle challenging issues of the shortage of annotated data, inability of defining anomaly objects explicitly and the expensive cost of feature engineering procedure. Unlike existing appoaches which only partially solve these problems, we develop a unique framework to cope the problems above simultaneously. Instead of hanlding with ambiguous definition of anomaly objects, we propose to work with regular patterns whose unlabeled data is abundant and usually easy to collect in practice. This allows our system to be trained completely in an unsupervised procedure and liberate us from the need for costly data annotation. By learning generative model that capture the normality distribution in data, we can isolate abnormal data points that result in low normality scores (high abnormality scores). Moreover, by leverage on the power of generative networks, i.e. energy-based models, we are also able to learn the feature representation automatically rather than replying on hand-crafted features that have been dominating anomaly detection research over many decades. We demonstrate our proposal on the specific application of video anomaly detection and the experimental results indicate that our method performs better than baselines and are comparable with state-of-the-art methods in many benchmark video anomaly detection datasets.

##### Abstract (translated by Google)
近年来，由于在视频监控，工业损伤检测和网络入侵检测等多种应用领域，研究领域对数据异常的自动检测进行了研究。然而，构建一个有效的异常检测系统是一个不平凡的任务，因为它需要解决注释数据短缺，明确定义异常对象的能力不足以及特征工程过程的昂贵成本等具有挑战性的问题。与现有的只能部分解决这些问题的应用程序不同，我们开发了一个独特的框架来同时解决上述问题。我们建议使用常规模式来处理未标记的数据，这些数据非常丰富，而且通常在实践中很容易收集，而不是处理异常对象的模糊定义。这使得我们的系统可以在无监督的程序中完全训练，并使我们摆脱对昂贵的数据注释的需求。通过学习捕捉数据正态分布的生成模型，我们可以分离导致低正态分数（高异常分数）的异常数据点。此外，通过利用生成网络（即基于能量的模型）的力量，我们也能够自动学习特征表示，而不是回答几十年来主导异常检测研究的手工特征。我们证明了我们关于视频异常检测的具体应用的建议，实验结果表明我们的方法比基线性能更好，并且在许多基准视频异常检测数据集中与最先进的方法相当。

##### URL
[https://arxiv.org/abs/1708.05211](https://arxiv.org/abs/1708.05211)

##### PDF
[https://arxiv.org/pdf/1708.05211](https://arxiv.org/pdf/1708.05211)

