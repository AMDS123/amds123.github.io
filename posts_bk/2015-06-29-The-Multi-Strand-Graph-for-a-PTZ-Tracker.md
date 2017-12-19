---
layout: post
title: "The Multi-Strand Graph for a PTZ Tracker"
date: 2015-06-29 01:59:32
categories: arXiv_CV
tags: arXiv_CV Face Tracking
author: Shachaf Melman, Yael Moses, Gérard Medioni, Yinghao Cai
mathjax: true
---

* content
{:toc}

##### Abstract
High-resolution images can be used to resolve matching ambiguities between trajectory fragments (tracklets), which is one of the main challenges in multiple target tracking. A PTZ camera, which can pan, tilt and zoom, is a powerful and efficient tool that offers both close-up views and wide area coverage on demand. The wide-area view makes it possible to track many targets while the close-up view allows individuals to be identified from high-resolution images of their faces. A central component of a PTZ tracking system is a scheduling algorithm that determines which target to zoom in on. In this paper we study this scheduling problem from a theoretical perspective, where the high resolution images are also used for tracklet matching. We propose a novel data structure, the Multi-Strand Tracking Graph (MSG), which represents the set of tracklets computed by a tracker and the possible associations between them. The MSG allows efficient scheduling as well as resolving -- directly or by elimination -- matching ambiguities between tracklets. The main feature of the MSG is the auxiliary data saved in each vertex, which allows efficient computation while avoiding time-consuming graph traversal. Synthetic data simulations are used to evaluate our scheduling algorithm and to demonstrate its superiority over a na\"ive one.

##### Abstract (translated by Google)
高分辨率图像可以用来解决轨迹碎片（轨迹）之间的匹配模糊，这是多目标跟踪中的主要挑战之一。可以平移，倾斜和缩放的PTZ摄像机是一个功能强大且高效的工具，可同时提供特写视图和广泛的区域覆盖。广角视图可以跟踪多个目标，而特写视图可以从人脸的高分辨率图像中识别出个人。 PTZ跟踪系统的核心部件是调度算法，用于确定放大哪个目标。在本文中，我们从理论角度研究这种调度问题，其中高分辨率图像也用于轨迹匹配。我们提出了一种新颖的数据结构 - 多链跟踪图（MSG），它代表由跟踪器计算的一组tracklets以及它们之间可能的关联。 MSG允许高效的调度以及直接或通过消除匹配轨迹之间的模糊性。 MSG的主要功能是保存在每个顶点的辅助数据，这样可以在避免耗时的图形遍历的同时进行高效的计算。综合数据模拟被用来评估我们的调度算法，并展示其优于一个优势。

##### URL
[https://arxiv.org/abs/1506.08485](https://arxiv.org/abs/1506.08485)

##### PDF
[https://arxiv.org/pdf/1506.08485](https://arxiv.org/pdf/1506.08485)

