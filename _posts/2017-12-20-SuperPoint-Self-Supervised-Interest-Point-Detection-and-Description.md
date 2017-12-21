---
layout: post
title: "SuperPoint: Self-Supervised Interest Point Detection and Description"
date: 2017-12-20 18:38:35
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Daniel DeTone, Tomasz Malisiewicz, Andrew Rabinovich
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a self-supervised framework for training interest point detectors and descriptors suitable for a large number of multiple-view geometry problems in computer vision. As opposed to patch-based neural networks, our fully-convolutional model operates on full-sized images and jointly computes pixel-level interest point locations and associated descriptors in one forward pass. We introduce Homographic Adaptation, a multi-scale, multi-homography approach for boosting interest point detection accuracy and performing cross-domain adaptation (e.g., synthetic-to-real). Our model, when trained on the MS-COCO generic image dataset using Homographic Adaptation, is able to repeatedly detect a much richer set of interest points than the initial pre-adapted deep model and any other traditional corner detector. The final system gives rise to strong interest point repeatability on the HPatches dataset and outperforms traditional descriptors such as ORB and SIFT on point matching accuracy and on the task of homography estimation.

##### Abstract (translated by Google)
本文提出了一种适合于计算机视觉中大量多视点几何问题的自适应训练兴趣点检测器和描述符的框架。与基于补丁的神经网络相反，我们的全卷积模型在全尺寸图像上运行，并在一个正向通道中联合计算像素级兴趣点位置和相关描述符。我们引入了Homographic Adaptation，这是一种多尺度，多单应性的方法，用于提高兴趣点检测精度并执行跨域适应（例如合成到实际）。我们的模型在使用同形适应对MS-COCO通用图像数据集进行训练时，能够重复检测比初始预适应深度模型和任何其他传统角点检测器更丰富的兴趣点集合。最终的系统在HPatches数据集上产生强烈的兴趣点重复性，并且胜过传统的描述符，如ORB和SIFT在点匹配精度和单应性估计的任务。

##### URL
[https://arxiv.org/abs/1712.07629](https://arxiv.org/abs/1712.07629)

##### PDF
[https://arxiv.org/pdf/1712.07629](https://arxiv.org/pdf/1712.07629)

