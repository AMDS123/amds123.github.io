---
layout: post
title: "Fast Video Shot Transition Localization with Deep Structured Models"
date: 2018-08-13 14:04:03
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Shitao Tang, Litong Feng, Zhangkui Kuang, Yimin Chen, Wei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of video shot transition is a crucial pre-processing step in video analysis. Previous studies are restricted on detecting sudden content changes between frames through similarity measurement and multi-scale operations are widely utilized to deal with transitions of various lengths. However, localization of gradual transitions are still under-explored due to the high visual similarity between adjacent frames. Cut shot transitions are abrupt semantic breaks while gradual shot transitions contain low-level spatial-temporal patterns caused by video effects in addition to the gradual semantic breaks, e.g. dissolve. In order to address the problem, we propose a structured network which is able to detect these two shot transitions using targeted models separately. Considering speed performance trade-offs, we design a smart framework. With one TITAN GPU, the proposed method can achieve a 30\(\times\) real-time speed. Experiments on public TRECVID07 and RAI databases show that our method outperforms the state-of-the-art methods. In order to train a high-performance shot transition detector, we contribute a new database ClipShots, which contains 128636 cut transitions and 38120 gradual transitions from 4039 online videos. ClipShots intentionally collect short videos for more hard cases caused by hand-held camera vibrations, large object motions, and occlusion.

##### Abstract (translated by Google)
视频镜头转换的检测是视频分析中至关重要的预处理步骤。先前的研究仅限于通过相似性测量来检测帧之间的突然内容变化，并且多尺度操作被广泛用于处理各种长度的过渡。然而，由于相邻帧之间的高视觉相似性，逐渐过渡的定位仍未得到充分研究。剪切转换是突然的语义中断，而渐变镜头转换包含由视频效果引起的低级空间 - 时间模式，以及逐渐的语义中断，例如，溶解。为了解决这个问题，我们提出了一种结构化网络，它能够分别使用目标模型检测这两个镜头过渡。考虑到速度性能的权衡，我们设计了一个智能框架。使用一个TITAN GPU，所提出的方法可以实现30 \（\ times \）的实时速度。公共TRECVID07和RAI数据库的实验表明，我们的方法优于最先进的方法。为了训练高性能镜头过渡探测器，我们提供了一个新的数据库ClipShots，其中包含128636个切换过渡和38120个4039在线视频的逐渐过渡。 ClipShots故意收集短视频，以解决由手持相机振动，大物体运动和遮挡引起的更多硬情况。

##### URL
[http://arxiv.org/abs/1808.04234](http://arxiv.org/abs/1808.04234)

##### PDF
[http://arxiv.org/pdf/1808.04234](http://arxiv.org/pdf/1808.04234)

