---
layout: post
title: "Cost-effective Object Detection: Active Sample Mining with Switchable Selection Criteria"
date: 2018-06-30 09:07:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Prediction Detection
author: Keze Wang, Liang Lin, Xiaopeng Yan, Ziliang Chen, Dongyu Zhang, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Though quite challenging, the training of object detectors using large-scale unlabeled or partially labeled datasets has attracted increasing interests from researchers due to its fundamental importance for applications of neural networks and learning systems. To address this problem, many active learning (AL) methods have been proposed that employ up-to-date detectors to retrieve representative minority samples according to predefined confidence or uncertainty thresholds. However, these AL methods cause the detectors to ignore the remaining majority samples (i.e., those with low uncertainty or high prediction confidence). In this work, by developing a principled active sample mining (ASM) framework, we demonstrate that cost-effectively mining samples from these unlabeled majority data is key to training more powerful object detectors while minimizing user effort. Specifically, our ASM framework involves a selectively switchable sample selection mechanism for determining whether an unlabeled sample should be manually annotated via AL or automatically pseudo-labeled via a novel self-learning process. The proposed process can be compatible with mini-batch based training (i.e., using a batch of unlabeled or partially labeled data as a one-time input) for object detection. Extensive experiments on two public benchmarks clearly demonstrate that our ASM framework can achieve performance comparable to that of alternative methods but with significantly fewer annotations.

##### Abstract (translated by Google)
虽然非常具有挑战性，但使用大规模未标记或部分标记的数据集的物体探测器的训练由于其对​​神经网络和学习系统的应用具有根本重要性而引起了研究人员越来越多的兴趣。为了解决该问题，已经提出了许多主动学习（AL）方法，其采用最新的检测器来根据预定义的置信度或不确定性阈值来检索代表性的少数样本。然而，这些AL方法使得检测器忽略剩余的大多数样本（即，具有低不确定性或高预测置信度的样本）。在这项工作中，通过开发原则性主动样本挖掘（ASM）框架，我们证明从这些未标记的多数数据中经济有效地挖掘样本是培训更强大的物体探测器同时最大限度地减少用户工作量的关键。具体而言，我们的ASM框架涉及选择性可切换的样本选择机制，用于确定是否应通过AL手动注释未标记的样本或通过新颖的自学过程自动伪标记。所提出的过程可以与基于小批量的训练兼容（即，使用一批未标记或部分标记的数据作为一次性输入）用于对象检测。对两个公共基准的广泛实验清楚地表明，我们的ASM框架可以实现与替代方法相当的性能，但注释明显更少。

##### URL
[http://arxiv.org/abs/1807.00147](http://arxiv.org/abs/1807.00147)

##### PDF
[http://arxiv.org/pdf/1807.00147](http://arxiv.org/pdf/1807.00147)

