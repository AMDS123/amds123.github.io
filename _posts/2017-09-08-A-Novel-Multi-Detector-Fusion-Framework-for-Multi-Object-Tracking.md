---
layout: post
title: "A Novel Multi-Detector Fusion Framework for Multi-Object Tracking"
date: 2017-09-08 19:04:02
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Object_Tracking Detection
author: Roberto Henschel, Laura Leal-Taixé, Daniel Cremers, Bodo Rosenhahn
mathjax: true
---

* content
{:toc}

##### Abstract
In order to track all persons in a scene, the tracking-by-detection paradigm has proven to be a very effective approach. Yet, relying solely on a single detector is also a major limitation, as useful image information might be ignored. This work demonstrates how to incorporate several detectors into a tracking system, using a novel multi-object tracking formulation. We cast tracking as a weighted graph labeling problem, resulting in a binary quadratic program. As such problems are NP-hard, the solution can only be approximated. Based on the Frank-Wolfe algorithm, we present a new solver that is crucial to handle such difficult problems. As a result, the tracker can take information from many frames and different detectors holistically into account. When applied with head and full-body detections, the fusion helps to recover heavily occluded persons and to reduce false positives. Evaluation on pedestrian tracking is provided for multiple scenarios, showing superior results over single detector tracking and standard QP-solvers. Finally, our tracker performs state-of-the-art on the MOT16 benchmark and is the winner of the MOT17 challenge.

##### Abstract (translated by Google)
为了跟踪场景中的所有人，逐个检测范例已被证明是非常有效的方法。然而，仅仅依靠单个探测器也是一个主要的限制，因为有用的图像信息可能被忽略。这项工作演示了如何使用一种新颖的多目标跟踪公式将多个检测器合并到一个跟踪系统中。我们将跟踪作为加权图标记问题，导致二进制二次程序。由于这样的问题是NP难题，所以解决方案只能是近似的。基于弗兰克 - 沃尔夫算法，我们提出了一个新的求解器，这对处理这样的难题至关重要。因此，跟踪器可以综合考虑多个帧和不同检测器的信息。应用头部和全身检测时，融合有助于恢复严重阻塞的人，并减少误报。针对多种情况提供了行人跟踪评估，与单个检测器跟踪和标准QP解算器相比，显示出更好的结果。最后，我们的跟踪器在MOT16基准测试中进行了最先进的测试，并且赢得了MOT17的挑战。

##### URL
[https://arxiv.org/abs/1705.08314](https://arxiv.org/abs/1705.08314)

##### PDF
[https://arxiv.org/pdf/1705.08314](https://arxiv.org/pdf/1705.08314)

