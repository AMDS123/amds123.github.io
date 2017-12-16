---
layout: post
title: "Spatio-temporal Human Action Localisation and Instance Segmentation in Temporally Untrimmed Videos"
date: 2017-08-06 15:22:59
categories: arXiv_CV
tags: arXiv_CV Segmentation Action_Recognition Classification Recognition
author: Suman Saha, Gurkirt Singh, Michael Sapienza, Philip H. S. Torr, Fabio Cuzzolin
mathjax: true
---

* content
{:toc}

##### Abstract
Current state-of-the-art human action recognition is focused on the classification of temporally trimmed videos in which only one action occurs per frame. In this work we address the problem of action localisation and instance segmentation in which multiple concurrent actions of the same class may be segmented out of an image sequence. We cast the action tube extraction as an energy maximisation problem in which configurations of region proposals in each frame are assigned a cost and the best action tubes are selected via two passes of dynamic programming. One pass associates region proposals in space and time for each action category, and another pass is used to solve for the tube's temporal extent and to enforce a smooth label sequence through the video. In addition, by taking advantage of recent work on action foreground-background segmentation, we are able to associate each tube with class-specific segmentations. We demonstrate the performance of our algorithm on the challenging LIRIS-HARL dataset and achieve a new state-of-the-art result which is 14.3 times better than previous methods.

##### Abstract (translated by Google)
当前最先进的人类动作识别集中于时间修剪的视频的分类，其中每帧仅发生一个动作。在这项工作中，我们解决了动作定位和实例分割的问题，其中同一类的多个并发动作可以从图像序列中分割出来。我们把动作管提取作为一个能量最大化问题，在这个问题中，每个框架中的区域提议的配置被分配一个成本，并且通过两次动态编程来选择最好的动作管。一次通过将空间和时间的区域提案联合起来用于每个动作类别，另一次通过用于解决管子的时间范围，并且通过视频执行顺畅的标签序列。另外，通过利用最近在动作前景 - 背景分割方面的工作，我们能够将每个管与特定类的分割相关联。我们演示了我们的算法在具有挑战性的LIRIS-HARL数据集上的性能，并实现了比先前方法好14.3倍的新的最新结果。

##### URL
[https://arxiv.org/abs/1707.07213](https://arxiv.org/abs/1707.07213)

##### PDF
[https://arxiv.org/pdf/1707.07213](https://arxiv.org/pdf/1707.07213)

