---
layout: post
title: "Deep Pose Consensus Networks"
date: 2018-03-22 01:22:50
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Geonho Cha, Minsik Lee, Jungchan Cho, Songhwai Oh
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of estimating a 3D human pose from a single image, which is important but difficult to solve due to many reasons, such as self-occlusions, wild appearance changes, and inherent ambiguities of 3D estimation from a 2D cue. These difficulties make the problem ill-posed, which have become requiring increasingly complex estimators to enhance the performance. On the other hand, most existing methods try to handle this problem based on a single complex estimator, which might not be good solutions. In this paper, to resolve this issue, we propose a multiple-partial-hypothesis-based framework for the problem of estimating 3D human pose from a single image, which can be fine-tuned in an end-to-end fashion. We first select several joint groups from a human joint model using the proposed sampling scheme, and estimate the 3D poses of each joint group separately based on deep neural networks. After that, they are aggregated to obtain the final 3D poses using the proposed robust optimization formula. The overall procedure can be fine-tuned in an end-to-end fashion, resulting in better performance. In the experiments, the proposed framework shows the state-of-the-art performances on popular benchmark data sets, namely Human3.6M and HumanEva, which demonstrate the effectiveness of the proposed framework.

##### Abstract (translated by Google)
在本文中，我们解决了从单个图像估计三维人体姿态的问题，这很重要但很难解决，原因很多，如自闭塞，外观变化以及2D估计的固有模糊性线索。这些困难使这个问题不适当，这已经变得越来越复杂的估计人员需要提高绩效。另一方面，大多数现有的方法都是基于单个复杂的估计器来处理这个问题，这可能不是很好的解决方案。在本文中，为了解决这个问题，我们提出了一个基于多部分假设的框架，用于从单个图像估计3D人体姿态的问题，可以以端到端的方式进行微调。我们首先使用所提出的采样方案从人类关节模型中选择几个关节组，并基于深度神经网络分别估计每个关节组的三维姿态。之后，使用建议的鲁棒优化公式来聚合它们以获得最终的3D姿势。整个过程可以以端到端的方式进行微调，从而获得更好的性能。在实验中，所提出的框架显示了在流行的基准数据集上的最新性能，即Human3.6M和HumanEva，它们证明了所提出的框架的有效性。

##### URL
[https://arxiv.org/abs/1803.08190](https://arxiv.org/abs/1803.08190)

##### PDF
[https://arxiv.org/pdf/1803.08190](https://arxiv.org/pdf/1803.08190)

