---
layout: post
title: "A Structural Correlation Filter Combined with A Multi-task Gaussian Particle Filter for Visual Tracking"
date: 2018-03-03 11:11:17
categories: arXiv_CV
tags: arXiv_CV Tracking Detection Relation
author: Manna Dai, Shuying Cheng, Xiangjian He, Dadong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel structural correlation filter combined with a multi-task Gaussian particle filter (KCF-GPF) model for robust visual tracking. We first present an assemble structure where several KCF trackers as weak experts provide a preliminary decision for a Gaussian particle filter to make a final decision. The proposed method is designed to exploit and complement the strength of a KCF and a Gaussian particle filter. Compared with the existing tracking methods based on correlation filters or particle filters, the proposed tracker has several advantages. First, it can detect the tracked target in a large-scale search scope via weak KCF trackers and evaluate the reliability of weak trackers\rq decisions for a Gaussian particle filter to make a strong decision, and hence it can tackle fast motions, appearance variations, occlusions and re-detections. Second, it can effectively handle large-scale variations via a Gaussian particle filter. Third, it can be amenable to fully parallel implementation using importance sampling without resampling, thereby it is convenient for VLSI implementation and can lower the computational costs. Extensive experiments on the OTB-2013 dataset containing 50 challenging sequences demonstrate that the proposed algorithm performs favourably against 16 state-of-the-art trackers.

##### Abstract (translated by Google)
在本文中，我们提出了一种新颖的结构相关滤波器结合多任务高斯粒子滤波器（KCF-GPF）模型用于鲁棒视觉跟踪。我们首先提出一个组装结构，其中几个KCF跟踪器作为弱专家为高斯粒子滤波器提供初步决策以作出最终决定。所提出的方法旨在利用和补充KCF和高斯粒子滤波器的强度。与基于相关滤波器或粒子滤波器的现有跟踪方法相比，所提出的跟踪器具有多个优点。首先，它可以通过弱KCF跟踪器检测大规模搜索范围内的跟踪目标，并评估高斯粒子滤波器的弱跟踪器\ rq决策的可靠性，从而做出强有力的决策，因此它可以解决快速运动，外观变化，遮挡和重新检测。其次，它可以通过高斯粒子滤波器有效处理大范围的变化。第三，采用重采样技术可以完全并行实现而不需重采样，因此便于VLSI的实现，并且可以降低计算成本。在包含50个具有挑战性的序列的OTB-2013数据集上的大量实验表明，所提出的算法对16个最先进的跟踪器表现出良好的效果。

##### URL
[https://arxiv.org/abs/1803.05845](https://arxiv.org/abs/1803.05845)

##### PDF
[https://arxiv.org/pdf/1803.05845](https://arxiv.org/pdf/1803.05845)

