---
layout: post
title: "Robust Heartbeat Detection from Multimodal Data via CNN-based Generalizable Information Fusion"
date: 2018-06-29 06:47:16
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: B S Chandra, C S Sastry, S Jana
mathjax: true
---

* content
{:toc}

##### Abstract
Objective: Heartbeat detection remains central to cardiac disease diagnosis and management, and is traditionally performed based on electrocardiogram (ECG). To improve robustness and accuracy of detection, especially, in certain critical-care scenarios, the use of additional physiological signals such as arterial blood pressure (BP) has recently been suggested. There, estimation of heartbeat location requires information fusion from multiple signals. However, reported efforts in this direction often obtain multimodal estimates somewhat indirectly, by voting among separately obtained signal-specific intermediate estimates. In contrast, we propose to directly fuse information from multiple signals without requiring intermediate estimates, and thence estimate heartbeat location in a robust manner. Method: We propose as a heartbeat detector, a convolutional neural network (CNN) that learns fused features from multiple physiological signals. This method eliminates the need for hand-picked signal-specific features and ad hoc fusion schemes. Further, being data-driven, the same algorithm learns suitable features from arbitrary set of signals. Results: Using ECG and BP signals of PhysioNet 2014 Challenge database, we obtained a score of 94%. Further, using two ECG channels of MIT-BIH arrhythmia database, we scored 99.92\%. Both those scores compare favourably with previously reported database-specific results. Also, our detector achieved high accuracy in a variety of clinical conditions. Conclusion: The proposed CNN-based information fusion (CIF) algorithm is generalizable, robust and efficient in detecting heartbeat location from multiple signals. Significance: In medical signal monitoring systems, our technique would accurately estimate heartbeat locations even when only a subset of channels are reliable.

##### Abstract (translated by Google)
目的：心跳检测仍然是心脏病诊断和管理的核心，传统上是基于心电图（ECG）进行的。为了提高检测的稳健性和准确性，尤其是在某些重症监护情景中，最近已经提出使用诸如动脉血压（BP）的额外生理信号。在那里，心跳位置的估计需要来自多个信号的信息融合。然而，报告的这方面的努力通常通过在单独获得的信号特定中间估计之间进行投票来间接地获得多模态估计。相反，我们建议直接融合来自多个信号的信息而不需要中间估计，并且因此以稳健的方式估计心跳位置。方法：我们建议作为心跳检测器，卷积神经网络（CNN），从多个生理信号中学习融合特征。该方法消除了对手工挑选的信号特定特征和ad hoc融合方案的需要。此外，作为数据驱动，相同的算法从任意信号集学习合适的特征。结果：使用PhysioNet 2014 Challenge数据库的ECG和BP信号，我们获得了94％的分数。此外，使用MIT-BIH心律失常数据库的两个ECG通道，我们得分为99.92％。这些得分与先前报告的数据库特定结果相比是有利的。此外，我们的检测器在各种临床条件下都具有高精度。结论：所提出的基于CNN的信息融合（CIF）算法具有通用性，鲁棒性和高效性，可以从多个信号中检测心跳位置。意义：在医疗信号监测系统中，即使只有一部分通道可靠，我们的技术也能准确估计心跳位置。

##### URL
[http://arxiv.org/abs/1807.03232](http://arxiv.org/abs/1807.03232)

##### PDF
[http://arxiv.org/pdf/1807.03232](http://arxiv.org/pdf/1807.03232)

