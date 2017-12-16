---
layout: post
title: "Boundary Flow: A Siamese Network that Predicts Boundary Motion without Training on Motion"
date: 2017-09-05 03:45:43
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Peng Lei, Fuxin Li, Sinisa Todorovic
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses a new problem of joint object boundary detection and boundary motion estimation in videos, which we named boundary flow estimation. Boundary flow is an important mid-level visual cue as boundaries characterize objects spatial extents, and the flow indicates objects motions and interactions. Yet, most prior work on motion estimation has focused on dense object motion or feature points that may not necessarily reside on boundaries. For boundary flow estimation, we specify a new fully convolutional Siamese network (FCSN) that jointly estimates object-level boundaries in two consecutive frames. Boundary correspondences in the two frames are predicted by the same FCSN with a new, unconventional deconvolution approach. Finally, the boundary flow estimate is improved with an edgelet-based filtering. Evaluation is conducted on three tasks: boundary detection in videos, boundary flow estimation, and optical flow estimation. On boundary detection, we achieve the state-of-the-art performance on the benchmark VSB100 dataset. On boundary flow estimation, we present the first results on the Sintel training dataset. For optical flow estimation, we run the recent approach CPM-Flow but on the augmented input with our boundary-flow matches, and achieve significant performance improvement on the Sintel benchmark.

##### Abstract (translated by Google)
本文针对视频中的联合对象边界检测和边界运动估计问题，提出了一种新的边界流估计方法。边界流是一个重要的中级视觉提示，因为边界表征了对象的空间范围，流指示了对象的运动和相互作用。然而，大部分先前的运动估计工作集中在密集的物体运动或特征点上，而这些运动或特征点可能不一定在边界上。对于边界流估计，我们指定一个新的完全卷积连体网络（FCSN），联合估计两个连续帧中的物体层边界。两帧中的边界对应由相同的FCSN用新的非常规反卷积方法预测。最后，通过基于小波的滤波来改善边界流量估计。对三个任务进行评估：视频中的边界检测，边界流量估计和光流估计。在边界检测方面，我们在基准VSB100数据集上实现了最先进的性能。在边界流动估计上，我们给出了Sintel训练数据集的第一个结果。对于光学流量估算，我们使用最近的CPM-Flow方法，但是使用我们的边界流量匹配的增量式输入，并且在Sintel基准上实现了显着的性能改进。

##### URL
[https://arxiv.org/abs/1702.08646](https://arxiv.org/abs/1702.08646)

##### PDF
[https://arxiv.org/pdf/1702.08646](https://arxiv.org/pdf/1702.08646)

