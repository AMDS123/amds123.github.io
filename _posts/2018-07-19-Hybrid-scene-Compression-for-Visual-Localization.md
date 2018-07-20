---
layout: post
title: "Hybrid scene Compression for Visual Localization"
date: 2018-07-19 16:04:58
categories: arXiv_CV
tags: arXiv_CV
author: Federico Camposeco, Andrea Cohen, Marc Pollefeys, Torsten Sattler
mathjax: true
---

* content
{:toc}

##### Abstract
Localizing an image wrt. a large scale 3D scene represents a core task for many computer vision applications. The increasing size of available 3D scenes makes visual localization prohibitively slow for real-time applications due to the large amount of data that the system needs to analyze and store. Therefore, compression becomes a necessary step in order to manage large scenes. In this work, we introduce a new hybrid compression algorithm that selects two subsets of points from the original 3D model: a small set of points with full appearance information, and an additional, larger set of points with compressed information. Our algorithm takes into account both spatial coverage as well as appearance uniqueness during compression. Quantization techniques are exploited during compression time, reducing run-time wrt. previous compression methods. A RANSAC variant tailored to our specific compression output is also introduced. Experiments on six large-scale datasets show that our method performs better than previous compression techniques in terms of memory, run-time and accuracy. Furthermore, the localization rates and pose accuracy obtained are comparable to state-of-the-art feature-based methods, while using a small fraction of the memory.

##### Abstract (translated by Google)
本地化图像wrt。大规模3D场景代表了许多计算机视觉应用的核心任务。由于系统需要分析和存储大量数据，可用3D场景的大小越来越大，使得实时应用程序的视觉本地化速度极慢。因此，压缩成为管理大型场景的必要步骤。在这项工作中，我们引入了一种新的混合压缩算法，该算法从原始3D模型中选择两个点子集：一组具有完整外观信息的点，以及一组具有压缩信息的附加的更大点。我们的算法考虑了空间覆盖以及压缩期间的外观唯一性。在压缩时间期间利用量化技术，减少运行时间。以前的压缩方法。还引入了针对我们的特定压缩输出量身定制的RANSAC变体。六个大型数据集的实验表明，我们的方法在内存，运行时间和准确性方面比以前的压缩技术表现更好。此外，获得的定位率和姿势精度与现有技术中基于特征的方法相当，同时使用一小部分内存。

##### URL
[https://arxiv.org/abs/1807.07512](https://arxiv.org/abs/1807.07512)

##### PDF
[https://arxiv.org/pdf/1807.07512](https://arxiv.org/pdf/1807.07512)

