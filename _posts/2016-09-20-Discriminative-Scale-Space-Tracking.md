---
layout: post
title: "Discriminative Scale Space Tracking"
date: 2016-09-20 12:57:08
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Detection Relation
author: Martin Danelljan, Gustav Häger, Fahad Shahbaz Khan, Michael Felsberg
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate scale estimation of a target is a challenging research problem in visual object tracking. Most state-of-the-art methods employ an exhaustive scale search to estimate the target size. The exhaustive search strategy is computationally expensive and struggles when encountered with large scale variations. This paper investigates the problem of accurate and robust scale estimation in a tracking-by-detection framework. We propose a novel scale adaptive tracking approach by learning separate discriminative correlation filters for translation and scale estimation. The explicit scale filter is learned online using the target appearance sampled at a set of different scales. Contrary to standard approaches, our method directly learns the appearance change induced by variations in the target scale. Additionally, we investigate strategies to reduce the computational cost of our approach. Extensive experiments are performed on the OTB and the VOT2014 datasets. Compared to the standard exhaustive scale search, our approach achieves a gain of 2.5% in average overlap precision on the OTB dataset. Additionally, our method is computationally efficient, operating at a 50% higher frame rate compared to the exhaustive scale search. Our method obtains the top rank in performance by outperforming 19 state-of-the-art trackers on OTB and 37 state-of-the-art trackers on VOT2014.

##### Abstract (translated by Google)
目标精确的尺度估计是视觉对象跟踪中具有挑战性的研究问题。大多数最先进的方法采用详尽的比例搜索来估计目标大小。详尽的搜索策略在计算上是昂贵的，遇到大规模变化时会遇到困难。本文研究了在逐个检测框架下准确和鲁棒的尺度估计问题。我们提出了一种新的尺度自适应跟踪方法，通过学习单独的判别式相关滤波器进行平移和尺度估计显式比例过滤器是使用在一组不同尺度上采样的目标外观在线学习的。与标准方法相反，我们的方法直接学习目标尺度变化引起的外观变化。此外，我们调查策略，以减少我们的方法的计算成本。在OTB和VOT2014数据集上进行了大量的实验。与标准的穷尽尺度搜索相比，我们的方法在OTB数据集平均重叠精度上获得了2.5％的增益。另外，我们的方法在计算上是高效的，与全面的比例搜索相比，帧速率高出50％。我们的方法通过超越OTB上的19个最先进的跟踪器以及VOT2014上的37个最先进的跟踪器而获得了最佳性能。

##### URL
[https://arxiv.org/abs/1609.06141](https://arxiv.org/abs/1609.06141)

##### PDF
[https://arxiv.org/pdf/1609.06141](https://arxiv.org/pdf/1609.06141)

