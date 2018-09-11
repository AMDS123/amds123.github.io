---
layout: post
title: "Tracking by Animation: Unsupervised Learning of Multi-Object Attentive Trackers"
date: 2018-09-10 04:59:25
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Detection
author: Zhen He, Jian Li, Daxue Liu, Hangen He, David Barber
mathjax: true
---

* content
{:toc}

##### Abstract
Online Multi-Object Tracking (MOT) from videos is a challenging computer vision task which has been extensively studied for decades. Most of the existing MOT algorithms are based on the Tracking-by-Detection (TBD) paradigm combined with popular machine learning approaches which largely reduce the human effort to tune algorithm parameters. However, the commonly used supervised learning approaches require the labeled data (e.g., bounding boxes), which is expensive for videos. Also, the TBD framework is usually suboptimal since it is not end-to-end, i.e., it considers the task as detection and tracking, but not jointly. To achieve both label-free and end-to-end learning of MOT, we propose a Tracking-by-Animation framework, where a differentiable neural model first tracks objects from input frames and then animates these objects into reconstructed frames. Learning is then driven by the reconstruction error through backpropagation. We further propose a Reprioritized Attentive Tracking to improve the robustness of data association. Experiments conducted on both synthetic and real video datasets show the potential of the proposed model.

##### Abstract (translated by Google)
视频在线多目标跟踪（MOT）是一项具有挑战性的计算机视觉任务，已经过数十年的广泛研究。大多数现有的MOT算法都基于检测跟踪（TBD）范例，结合流行的机器学习方法，这大大减少了调整算法参数的人力。然而，常用的监督学习方法需要标记数据（例如，边界框），这对于视频来说是昂贵的。此外，TBD框架通常不是最理想的，因为它不是端到端的，即，它将任务视为检测和跟踪，而不是联合。为了实现MOT的无标签和端到端学习，我们提出了一种逐动画跟踪框架，其中可微分神经模型首先跟踪输入帧中的对象，然后将这些对象动画化为重建帧。然后通过反向传播通过重建误差来驱动学习。我们进一步提出了重新优先级的跟踪跟踪，以提高数据关联的稳健性。在合成和真实视频数据集上进行的实验显示了所提出的模型的潜力。

##### URL
[http://arxiv.org/abs/1809.03137](http://arxiv.org/abs/1809.03137)

##### PDF
[http://arxiv.org/pdf/1809.03137](http://arxiv.org/pdf/1809.03137)

