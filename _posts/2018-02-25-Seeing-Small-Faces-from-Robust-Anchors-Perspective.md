---
layout: post
title: "Seeing Small Faces from Robust Anchor's Perspective"
date: 2018-02-25 18:48:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection Face_Detection
author: Chenchen Zhu, Ran Tao, Khoa Luu, Marios Savvides
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a novel anchor design to support anchor-based face detection for superior scale-invariant performance, especially on tiny faces. To achieve this, we explicitly address the problem that anchor-based detectors drop performance drastically on faces with tiny sizes, e.g. less than 16x16 pixels. In this paper, we investigate why this is the case. We discover that current anchor design cannot guarantee high overlaps between tiny faces and anchor boxes, which increases the difficulty of training. The new Expected Max Overlapping (EMO) score is proposed which can theoretically explain the low overlapping issue and inspire several effective strategies of new anchor design leading to higher face overlaps, including anchor stride reduction with new network architectures, extra shifted anchors, and stochastic face shifting. Comprehensive experiments show that our proposed method significantly outperforms the baseline anchor-based detector, while consistently achieving state-of-the-art results on challenging face detection datasets with competitive runtime speed.

##### Abstract (translated by Google)
本文介绍了一种新颖的锚点设计，以支持基于锚点的人脸检测以实现卓越的尺度不变性能，特别是在微小的人脸上。为了达到这个目的，我们明确地解决了基于锚的检测器在小尺寸的面上急剧降低性能的问题，例如，小于16x16像素。在本文中，我们调查为什么会出现这种情况。我们发现目前的锚固设计不能保证微小的表面和锚箱之间的高度重叠，这增加了训练的难度。提出了新的期望最大重叠（EMO）分数，理论上可以解释低重叠问题，并激发新的锚设计的几种有效策略，导致更高的面重叠，包括新网络体系结构锚定步幅减少，额外移位锚点和随机面移动。综合实验表明，我们提出的方法明显优于基线锚定检测器，同时始终如一地在具有竞争性运行速度的具有挑战性的人脸检测数据集上实现最新的结果。

##### URL
[http://arxiv.org/abs/1802.09058](http://arxiv.org/abs/1802.09058)

##### PDF
[http://arxiv.org/pdf/1802.09058](http://arxiv.org/pdf/1802.09058)

