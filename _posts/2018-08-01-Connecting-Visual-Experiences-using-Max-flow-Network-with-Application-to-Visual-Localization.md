---
layout: post
title: "Connecting Visual Experiences using Max-flow Network with Application to Visual Localization"
date: 2018-08-01 07:46:58
categories: arXiv_CV
tags: arXiv_CV Face SLAM Recognition
author: A.H. Abdul Hafez, Nakul Agarwal, C.V. Jawahar
mathjax: true
---

* content
{:toc}

##### Abstract
We are motivated by the fact that multiple representations of the environment are required to stand for the changes in appearance with time and for changes that appear in a cyclic manner. These changes are, for example, from day to night time, and from day to day across seasons. In such situations, the robot visits the same routes multiple times and collects different appearances of it. Multiple visual experiences usually find robotic vision applications like visual localization, mapping, place recognition, and autonomous navigation. The novelty in this paper is an algorithm that connects multiple visual experiences via aligning multiple image sequences. This problem is solved by finding the maximum flow in a directed graph flow-network, whose vertices represent the matches between frames in the test and reference sequences. Edges of the graph represent the cost of these matches. The problem of finding the best match is reduced to finding the minimum-cut surface, which is solved as a maximum flow network problem. Application to visual localization is considered in this paper to show the effectiveness of the proposed multiple image sequence alignment method, without loosing its generality. Experimental evaluations show that the precision of sequence matching is improved by considering multiple visual sequences for the same route, and that the method performs favorably against state-of-the-art single representation methods like SeqSLAM and ABLE-M.

##### Abstract (translated by Google)
我们的动机是需要多种环境表示来代表外观随时间的变化以及以循环方式出现的变化。例如，这些变化是从白天到夜晚，以及跨越季节的每天。在这种情况下，机器人多次访问相同的路线并收集不同的外观。多种视觉体验通常可以找到机器人视觉应用，如视觉定位，绘图，地点识别和自主导航。本文的新颖性是通过对齐多个图像序列来连接多个视觉体验的算法。通过在有向图流网络中找到最大流量来解决该问题，该流网络的顶点表示测试和参考序列中的帧之间的匹配。图的边缘表示这些匹配的成本。找到最佳匹配的问题减少到找到最小切割表面，这被解决为最大流动网络问题。本文考虑应用于视觉定位，以显示所提出的多图像序列比对方法的有效性，而不失其一般性。实验评估表明，通过考虑相同路线的多个视觉序列来提高序列匹配的精度，并且该方法有利地对抗SeqSLAM和ABLE-M等现有技术的单一表示方法。

##### URL
[https://arxiv.org/abs/1808.00208](https://arxiv.org/abs/1808.00208)

##### PDF
[https://arxiv.org/pdf/1808.00208](https://arxiv.org/pdf/1808.00208)

