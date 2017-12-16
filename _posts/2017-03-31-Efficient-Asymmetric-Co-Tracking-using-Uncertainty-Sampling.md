---
layout: post
title: "Efficient Asymmetric Co-Tracking using Uncertainty Sampling"
date: 2017-03-31 23:28:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Classification Detection
author: Kourosh Meshgi, Maryam Sadat Mirzaei, Shigeyuki Oba, Shin Ishii
mathjax: true
---

* content
{:toc}

##### Abstract
Adaptive tracking-by-detection approaches are popular for tracking arbitrary objects. They treat the tracking problem as a classification task and use online learning techniques to update the object model. However, these approaches are heavily invested in the efficiency and effectiveness of their detectors. Evaluating a massive number of samples for each frame (e.g., obtained by a sliding window) forces the detector to trade the accuracy in favor of speed. Furthermore, misclassification of borderline samples in the detector introduce accumulating errors in tracking. In this study, we propose a co-tracking based on the efficient cooperation of two detectors: a rapid adaptive exemplar-based detector and another more sophisticated but slower detector with a long-term memory. The sampling labeling and co-learning of the detectors are conducted by an uncertainty sampling unit, which improves the speed and accuracy of the system. We also introduce a budgeting mechanism which prevents the unbounded growth in the number of examples in the first detector to maintain its rapid response. Experiments demonstrate the efficiency and effectiveness of the proposed tracker against its baselines and its superior performance against state-of-the-art trackers on various benchmark videos.

##### Abstract (translated by Google)
自适应跟踪检测方法是跟踪任意对象的常用方法。他们将跟踪问题作为分类任务，并使用在线学习技术来更新对象模型。但是，这些方法在检测器的效率和有效性方面投入很大。评估每个帧的大量样本（例如，通过滑动窗口获得的）迫使检测器交换准确性以有利于速度。此外，检测器中边界样本的错误分类引入了跟踪中的累积误差。在这项研究中，我们提出了基于两个探测器的高效协作的协同追踪：一个快速自适应的基于样本的探测器和另一个更复杂但更慢的探测器与长期记忆。不确定采样单元进行采样标记和检测器联合学习，提高了系统的速度和精度。我们还引入了一个预算机制，可以防止第一台探测器的例数无限增长，保持其快速响应。实验证明了所提出的跟踪器在其基线上的效率和有效性，以及其在各种基准视频上针对最先进的跟踪器的优越性能。

##### URL
[https://arxiv.org/abs/1704.00083](https://arxiv.org/abs/1704.00083)

##### PDF
[https://arxiv.org/pdf/1704.00083](https://arxiv.org/pdf/1704.00083)

