---
layout: post
title: "Near-Online Multi-target Tracking with Aggregated Local Flow Descriptor"
date: 2015-04-09 14:57:32
categories: arXiv_CV
tags: arXiv_CV Regularization Tracking Detection
author: Wongun Choi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we focus on the two key aspects of multiple target tracking problem: 1) designing an accurate affinity measure to associate detections and 2) implementing an efficient and accurate (near) online multiple target tracking algorithm. As the first contribution, we introduce a novel Aggregated Local Flow Descriptor (ALFD) that encodes the relative motion pattern between a pair of temporally distant detections using long term interest point trajectories (IPTs). Leveraging on the IPTs, the ALFD provides a robust affinity measure for estimating the likelihood of matching detections regardless of the application scenarios. As another contribution, we present a Near-Online Multi-target Tracking (NOMT) algorithm. The tracking problem is formulated as a data-association between targets and detections in a temporal window, that is performed repeatedly at every frame. While being efficient, NOMT achieves robustness via integrating multiple cues including ALFD metric, target dynamics, appearance similarity, and long term trajectory regularization into the model. Our ablative analysis verifies the superiority of the ALFD metric over the other conventional affinity metrics. We run a comprehensive experimental evaluation on two challenging tracking datasets, KITTI and MOT datasets. The NOMT method combined with ALFD metric achieves the best accuracy in both datasets with significant margins (about 10% higher MOTA) over the state-of-the-arts.

##### Abstract (translated by Google)
本文重点研究了多目标跟踪问题的两个关键问题：1）设计了一个准确的亲和度量度来检测关联; 2）实现一个高效，准确的（近）在线多目标跟踪算法。作为第一个贡献，我们引入了一种新颖的聚合本地流描述符（ALFD），其使用长期兴趣点轨迹（IPT）对一对时间上相距较远的检测之间的相对运动模式进行编码。利用IPT，ALFD提供了一个强大的相关性度量，用于估计匹配检测的可能性，而不管应用场景如何。作为另一个贡献，我们提出了一个在线多目标跟踪（NOMT）算法。跟踪问题被制定为目标和时间窗口中的检测之间的数据关联，其在每一帧被重复执行。在提高效率的同时，NOMT通过将包括ALFD度量，目标动态，外观相似性和长期轨迹正则化在内的多种线索整合到模型中，实现了鲁棒性。我们的烧蚀分析验证了ALFD度量优于其他传统相关度量的优势。我们对两个具有挑战性的跟踪数据集KITTI和MOT数据集进行了全面的实验评估。 NOMT方法与ALFD度量相结合，在两个数据集中获得了最高的准确度，并且具有显着的利润率（比MOTA高出约10％）。

##### URL
[https://arxiv.org/abs/1504.02340](https://arxiv.org/abs/1504.02340)

##### PDF
[https://arxiv.org/pdf/1504.02340](https://arxiv.org/pdf/1504.02340)

