---
layout: post
title: "Temporal-Needle: A view and appearance invariant video descriptor"
date: 2016-12-14 21:46:09
categories: arXiv_CV
tags: arXiv_CV Detection
author: Michal Yarom, Michal Irani
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to detect similar actions across videos can be very useful for real-world applications in many fields. However, this task is still challenging for existing systems, since videos that present the same action, can be taken from significantly different viewing directions, performed by different actors and backgrounds and under various video qualities. Video descriptors play a significant role in these systems. In this work we propose the "temporal-needle" descriptor which captures the dynamic behavior, while being invariant to viewpoint and appearance. The descriptor is computed using multi temporal scales of the video and by computing self-similarity for every patch through time in every temporal scale. The descriptor is computed for every pixel in the video. However, to find similar actions across videos, we consider only a small subset of the descriptors - the statistical significant descriptors. This allow us to find good correspondences across videos more efficiently. Using the descriptor, we were able to detect the same behavior across videos in a variety of scenarios. We demonstrate the use of the descriptor in tasks such as temporal and spatial alignment, action detection and even show its potential in unsupervised video clustering into categories. In this work we handled only videos taken with stationary cameras, but the descriptor can be extended to handle moving camera as well.

##### Abstract (translated by Google)
跨视频检测类似操作的能力对于许多领域的实际应用非常有用。然而，对于现有系统来说，这个任务仍然是具有挑战性的，因为呈现相同动作的视频可以从明显不同的观看方向获得，由不同的演员和背景以及在不同的视频质量下执行。视频描述符在这些系统中起着重要的作用。在这项工作中，我们提出的“时针”描述符捕捉的动态行为，而不变的观点和外观。使用视频的多时间尺度计算描述符，并且通过计算每个时间尺度上每个时间片的自相似性。描述符是针对视频中的每个像素计算的。但是，要在视频中找到类似的操作，我们只考虑描述符的一小部分 - 统计重要的描述符。这使我们能够更有效地找到跨视频的良好通信。使用描述符，我们能够在各种场景中检测到视频中的相同行为。我们演示了描述符在诸如时间和空间对齐，动作检测等任务中的使用，甚至在无监督的视频聚类中显示其潜力。在这项工作中，我们只处理固定摄像机拍摄的视频，但是描述符也可以扩展到处理移动的摄像机。

##### URL
[https://arxiv.org/abs/1612.04854](https://arxiv.org/abs/1612.04854)

##### PDF
[https://arxiv.org/pdf/1612.04854](https://arxiv.org/pdf/1612.04854)

