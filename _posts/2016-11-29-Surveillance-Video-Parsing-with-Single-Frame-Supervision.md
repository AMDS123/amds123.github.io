---
layout: post
title: "Surveillance Video Parsing with Single Frame Supervision"
date: 2016-11-29 12:22:46
categories: arXiv_CV
tags: arXiv_CV Face
author: Si Liu, Changhu Wang, Ruihe Qian, Han Yu, Renda Bao
mathjax: true
---

* content
{:toc}

##### Abstract
Surveillance video parsing, which segments the video frames into several labels, e.g., face, pants, left-leg, has wide applications. However,pixel-wisely annotating all frames is tedious and inefficient. In this paper, we develop a Single frame Video Parsing (SVP) method which requires only one labeled frame per video in training stage. To parse one particular frame, the video segment preceding the frame is jointly considered. SVP (1) roughly parses the frames within the video segment, (2) estimates the optical flow between frames and (3) fuses the rough parsing results warped by optical flow to produce the refined parsing result. The three components of SVP, namely frame parsing, optical flow estimation and temporal fusion are integrated in an end-to-end manner. Experimental results on two surveillance video datasets show the superiority of SVP over state-of-the-arts.

##### Abstract (translated by Google)
将视频帧分成几个标签（例如，脸，裤子，左腿）的监视视频解析具有广泛的应用。然而，像素明智地注释所有帧是繁琐和低效的。在本文中，我们开发了一种单帧视频分析（SVP）方法，在训练阶段每个视频只需要一个标记帧。为了解析一个特定的帧，联合考虑帧之前的视频片段。 SVP（1）粗略地解析视频片段内的帧，（2）估计帧之间的光流，（3）融合光流所产生的粗略解析结果，产生精确的解析结果。 SVP的三个组成部分，即帧解析，光流估计和时间融合是以端到端的方式进行的。两个监控视频数据集的实验结果显示了SVP优于现有技术的优势。

##### URL
[https://arxiv.org/abs/1611.09587](https://arxiv.org/abs/1611.09587)

##### PDF
[https://arxiv.org/pdf/1611.09587](https://arxiv.org/pdf/1611.09587)

