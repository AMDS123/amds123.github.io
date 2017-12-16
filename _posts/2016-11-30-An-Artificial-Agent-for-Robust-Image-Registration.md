---
layout: post
title: "An Artificial Agent for Robust Image Registration"
date: 2016-11-30 20:05:55
categories: arXiv_CV
tags: arXiv_CV Attention CNN Optimization
author: Rui Liao, Shun Miao, Pierre de Tournemire, Sasa Grbic, Ali Kamen, Tommaso Mansi, Dorin Comaniciu
mathjax: true
---

* content
{:toc}

##### Abstract
3-D image registration, which involves aligning two or more images, is a critical step in a variety of medical applications from diagnosis to therapy. Image registration is commonly performed by optimizing an image matching metric as a cost function. However, this task is challenging due to the non-convex nature of the matching metric over the plausible registration parameter space and insufficient approaches for a robust optimization. As a result, current approaches are often customized to a specific problem and sensitive to image quality and artifacts. In this paper, we propose a completely different approach to image registration, inspired by how experts perform the task. We first cast the image registration problem as a "strategy learning" process, where the goal is to find the best sequence of motion actions (e.g. up, down, etc.) that yields image alignment. Within this approach, an artificial agent is learned, modeled using deep convolutional neural networks, with 3D raw image data as the input, and the next optimal action as the output. To cope with the dimensionality of the problem, we propose a greedy supervised approach for an end-to-end training, coupled with attention-driven hierarchical strategy. The resulting registration approach inherently encodes both a data-driven matching metric and an optimal registration strategy (policy). We demonstrate, on two 3-D/3-D medical image registration examples with drastically different nature of challenges, that the artificial agent outperforms several state-of-art registration methods by a large margin in terms of both accuracy and robustness.

##### Abstract (translated by Google)
包括对齐两个或更多个图像的三维图像配准是从诊断到治疗的各种医学应用中的关键步骤。图像配准通常通过将图像匹配度量优化为成本函数来执行。然而，由于匹配度量与非合理配准参数空间的非凸性质以及用于稳健优化的方法不足，这个任务是具有挑战性的。因此，目前的方法通常是针对特定的问题而定制的，并且对图像质量和伪像敏感。在本文中，我们提出了一种完全不同的图像配准方法，受专家如何执行任务的启发。我们首先将图像配准问题称为“策略学习”过程，其目标是找出产生图像对齐的最佳运动动作序列（例如上，下等）。在这种方法中，学习人造代理，使用深度卷积神经网络进行建模，以三维原始图像数据为输入，以下一个最佳动作作为输出。为了处理问题的维度，我们提出了一个贪婪监督的方法进行端到端的培训，再加上注意力驱动的分层策略。由此产生的注册方法固有地编码数据驱动的匹配度量和最优注册策略（策略）。我们在两个三维/三维医学图像配准示例中展示了具有截然不同挑战性质的人造代理在准确性和鲁棒性方面大大优于几种最先进的配准方法。

##### URL
[https://arxiv.org/abs/1611.10336](https://arxiv.org/abs/1611.10336)

##### PDF
[https://arxiv.org/pdf/1611.10336](https://arxiv.org/pdf/1611.10336)

