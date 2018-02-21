---
layout: post
title: "Latent RANSAC"
date: 2018-02-20 10:16:11
categories: arXiv_CV
tags: arXiv_CV Detection
author: Simon Korman, Roee Litman
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method that can evaluate a RANSAC hypothesis in constant time, i.e. independent of the size of the data. A key observation here is that correct hypotheses are tightly clustered together in the latent parameter domain. In a manner similar to the generalized Hough transform we seek to find this cluster, only that we need as few as two votes for a successful detection. Rapidly locating such pairs of similar hypotheses is made possible by adapting the recent "Random Grids" range-search technique. We only perform the usual (costly) hypothesis verification stage upon the discovery of a close pair of hypotheses. We show that this event rarely happens for incorrect hypotheses, enabling a significant speedup of the RANSAC pipeline. The suggested approach is applied and tested on three robust estimation problems: camera localization, 3D rigid alignment and 2D-homography estimation. We perform rigorous testing on both synthetic and real datasets, demonstrating an improvement in efficiency without a compromise in accuracy. Furthermore, we achieve state-of-the-art 3D alignment results on the challenging "Redwood" loop-closure challenge.

##### Abstract (translated by Google)
我们提出一种可以在恒定时间内评估RANSAC假设的方法，即独立于数据的大小。这里的一个关键观察是，正确的假设紧密聚集在潜在参数域中。以类似于广义Hough变换的方式，我们试图找到这个集群，只有我们需要少于两票才能成功检测。通过调整最近的“随机网格”范围搜索技术，可以快速定位这些类似的假设对。我们只在发现一对紧密的假设时才执行通常的（昂贵的）假设验证阶段。我们证明这个事件很少发生错误的假设，使得RANSAC管道显着加速。所提出的方法在三个稳健的估计问题上被应用和测试：照相机定位，3D刚性对准和2D单应估计。我们对合成数据集和真实数据集进行严格测试，证明在不影响准确性的情况下提高了效率。此外，我们在具有挑战性的“红木”闭环挑战中实现了最先进的3D对准结果。

##### URL
[http://arxiv.org/abs/1802.07045](http://arxiv.org/abs/1802.07045)

##### PDF
[http://arxiv.org/pdf/1802.07045](http://arxiv.org/pdf/1802.07045)

