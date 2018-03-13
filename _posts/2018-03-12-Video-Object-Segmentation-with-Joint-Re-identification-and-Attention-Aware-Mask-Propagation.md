---
layout: post
title: "Video Object Segmentation with Joint Re-identification and Attention-Aware Mask Propagation"
date: 2018-03-12 13:25:19
categories: arXiv_CV
tags: arXiv_CV Re-identification Segmentation Attention Tracking
author: Xiaoxiao Li, Chen Change Loy
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of video object segmentation can become extremely challenging when multiple instances co-exist. While each instance may exhibit large scale and pose variations, the problem is compounded when instances occlude each other causing failures in tracking. In this study, we formulate a deep recurrent network that is capable of segmenting and tracking objects in video simultaneously by their temporal continuity, yet able to re-identify them when they re-appear after a prolonged occlusion. We combine both temporal propagation and re-identification functionalities into a single framework that can be trained end-to-end. In particular, we present a re-identification module with template expansion to retrieve missing objects despite their large appearance changes. In addition, we contribute a new attention-based recurrent mask propagation approach that is robust to distractors not belonging to the target segment. Our approach achieves a new state-of-the-art global mean (Region Jaccard and Boundary F measure) of 68.2 on the challenging DAVIS 2017 benchmark (test-dev set), outperforming the winning solution which achieves a global mean of 66.1 on the same partition.

##### Abstract (translated by Google)
当多个实例共存时，视频对象分割的问题可能变得极具挑战性。虽然每个实例可能会出现大规模和姿态变化，但是当实例相互堵塞导致跟踪失败时，问题会更加复杂。在这项研究中，我们制定了一个深度循环网络，该网络能够通过时间上的连续性同时对视频中的物体进行分段和跟踪，但当它们在长时间遮挡后重新出现时，能够重新识别它们。我们将时间传播和重新识别功能组合到一个可以进行端到端培训的单一框架中。具体而言，我们提出了一个模板扩展的重新识别模块，以检索丢失的物体，尽管其外观变化很大。此外，我们提供了一种新的基于注意力的经常性掩模传播方法，该方法对不属于目标片段的分散注意力是健壮的。我们的方法在具有挑战性的DAVIS 2017基准测试（测试开发套件）上实现了全新的最先进的全局平均值（Region Jaccard和Boundary F度量），达到了68.2，超越了获得全球平均66.1相同的分区。

##### URL
[https://arxiv.org/abs/1803.04242](https://arxiv.org/abs/1803.04242)

##### PDF
[https://arxiv.org/pdf/1803.04242](https://arxiv.org/pdf/1803.04242)

