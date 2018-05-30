---
layout: post
title: "Pointly-Supervised Action Localization"
date: 2018-05-29 09:52:37
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization Inference
author: Pascal Mettes, Cees G. M. Snoek
mathjax: true
---

* content
{:toc}

##### Abstract
This paper strives for spatio-temporal localization of human actions in videos. In the literature, the consensus is to achieve localization by training on bounding box annotations provided for each frame of each training video. As annotating boxes in video is expensive, cumbersome and error-prone, we propose to bypass box-supervision. Instead, we introduce action localization based on point-supervision. We start from unsupervised spatio-temporal proposals, which provide a set of candidate regions in videos. While normally used exclusively for inference, we show spatio-temporal proposals can also be leveraged during training when guided by a sparse set of point annotations. We introduce an overlap measure between points and spatio-temporal proposals and incorporate them all into a new objective of a Multiple Instance Learning optimization. During inference, we introduce pseudo-points, visual cues from videos, that automatically guide the selection of spatio-temporal proposals. We outline five spatial and one temporal pseudo-point, as well as a measure to best leverage pseudo-points at test time. Experimental evaluation on three action localization datasets shows our pointly-supervised approach (i) is as effective as traditional box-supervision at a fraction of the annotation cost, (ii) is robust to sparse and noisy point annotations, (iii) benefits from pseudo-points during inference, and (iv) outperforms recent weakly-supervised alternatives. This leads us to conclude that points provide a viable alternative to boxes for action localization.

##### Abstract (translated by Google)
本文力求在视频中对人类行为进行时空定位。在文献中，共识是通过针对每个训练视频的每个帧提供的边界框注释的训练来实现本地化。由于视频中的注释框昂贵，麻烦且容易出错，因此我们建议绕开框监督。相反，我们引入基于点监督的行动本地化。我们从无监督的时空提议开始，这些提议在视频中提供了一组候选区域。虽然通常专用于推理，但我们还是展示了在训练过程中，时空提议也可以在稀疏的点注释引导下使用。我们引入点与时空提议之间的重叠度量，并将它们全部纳入多实例学习优化的新目标。在推断过程中，我们引入了来自视频的伪点，视觉线索，可自动指导时空提议的选择。我们概述了五个空间和一个时间伪点，以及在测试时间最好地利用伪点的一种方法。对三个动作定位数据集的实验评估表明，我们的点监督方法（i）在注释费用的一小部分与传统盒子监督方法一样有效，（ii）对稀疏和有噪点注释有鲁棒性，（iii） （iv）胜过最近的弱监督替代品。这导致我们得出结论：点为行动本地化提供了一个可行的替代方案。

##### URL
[http://arxiv.org/abs/1805.11333](http://arxiv.org/abs/1805.11333)

##### PDF
[http://arxiv.org/pdf/1805.11333](http://arxiv.org/pdf/1805.11333)

