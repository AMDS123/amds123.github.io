---
layout: post
title: "A Universal Update-pacing Framework For Visual Tracking"
date: 2016-03-01 04:12:41
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Zexi Hu, Yuefang Gao, Dong Wang, Xuhong Tian
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel framework to alleviate the model drift problem in visual tracking, which is based on paced updates and trajectory selection. Given a base tracker, an ensemble of trackers is generated, in which each tracker's update behavior will be paced and then traces the target object forward and backward to generate a pair of trajectories in an interval. Then, we implicitly perform self-examination based on trajectory pair of each tracker and select the most robust tracker. The proposed framework can effectively leverage temporal context of sequential frames and avoid to learn corrupted information. Extensive experiments on the standard benchmark suggest that the proposed framework achieves superior performance against state-of-the-art trackers.

##### Abstract (translated by Google)
本文提出了一种新的框架来缓解视觉跟踪中的模型漂移问题，该框架是基于节奏更新和轨迹选择。给定一个基本跟踪器，生成一个跟踪器的集合，其中每个跟踪器的更新行为将被调节，然后向前和向后跟踪目标对象以在一个区间内生成一对轨迹。然后，我们基于每个跟踪器的轨迹对隐式执行自我检查，并选择最强健的跟踪器。所提出的框架可以有效利用时序上下文的帧序列，避免学习被破坏的信息。标准基准的大量实验表明，所提出的框架实现了对最先进的跟踪器的优越性能。

##### URL
[https://arxiv.org/abs/1603.00132](https://arxiv.org/abs/1603.00132)

##### PDF
[https://arxiv.org/pdf/1603.00132](https://arxiv.org/pdf/1603.00132)

