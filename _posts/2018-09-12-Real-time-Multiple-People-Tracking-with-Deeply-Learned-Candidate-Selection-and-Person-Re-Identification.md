---
layout: post
title: "Real-time Multiple People Tracking with Deeply Learned Candidate Selection and Person Re-Identification"
date: 2018-09-12 13:39:27
categories: arXiv_CV
tags: arXiv_CV Re-identification Tracking Person_Re-identification CNN Object_Tracking Prediction Detection
author: Long Chen, Haizhou Ai, Zijie Zhuang, Chong Shang
mathjax: true
---

* content
{:toc}

##### Abstract
Online multi-object tracking is a fundamental problem in time-critical video analysis applications. A major challenge in the popular tracking-by-detection framework is how to associate unreliable detection results with existing tracks. In this paper, we propose to handle unreliable detection by collecting candidates from outputs of both detection and tracking. The intuition behind generating redundant candidates is that detection and tracks can complement each other in different scenarios. Detection results of high confidence prevent tracking drifts in the long term, and predictions of tracks can handle noisy detection caused by occlusion. In order to apply optimal selection from a considerable amount of candidates in real-time, we present a novel scoring function based on a fully convolutional neural network, that shares most computations on the entire image. Moreover, we adopt a deeply learned appearance representation, which is trained on large-scale person re-identification datasets, to improve the identification ability of our tracker. Extensive experiments show that our tracker achieves real-time and state-of-the-art performance on a widely used people tracking benchmark.

##### Abstract (translated by Google)
在线多目标跟踪是时间关键视频分析应用中的基本问题。流行的逐个检测框架的一个主要挑战是如何将不可靠的检测结果与现有的跟踪相关联。在本文中，我们建议通过从检测和跟踪的输出中收集候选来处理不可靠的检测。生成冗余候选者的直觉是检测和跟踪可以在不同场景中相互补充。高可信度的检测结果可以防止长期跟踪漂移，并且轨道的预测可以处理由遮挡引起的噪声检测。为了实时应用大量候选者的最佳选择，我们提出了一种基于完全卷积神经网络的新型评分函数，它在整个图像上共享大多数计算。此外，我们采用深入学习的外观表示，在大型人员重新识别数据集上进行训练，以提高我们的跟踪器的识别能力。大量实验表明，我们的跟踪器可以在广泛使用的人员跟踪基准上实现实时和最先进的性能。

##### URL
[http://arxiv.org/abs/1809.04427](http://arxiv.org/abs/1809.04427)

##### PDF
[http://arxiv.org/pdf/1809.04427](http://arxiv.org/pdf/1809.04427)

