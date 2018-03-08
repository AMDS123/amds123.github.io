---
layout: post
title: "Single View Stereo Matching"
date: 2018-03-07 12:07:23
categories: arXiv_CV
tags: arXiv_CV Inference
author: Yue Luo, Jimmy Ren, Mude Lin, Jiahao Pang, Wenxiu Sun, Hongsheng Li, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Previous monocular depth estimation methods take a single view and directly regress the expected results. Though recent advances are made by applying geometrically inspired loss functions during training, the inference procedure does not explicitly impose any geometrical constraint. Therefore these models purely rely on the quality of data and the effectiveness of learning to generalize. This either leads to suboptimal results or the demand of huge amount of expensive ground truth labelled data to generate reasonable results. In this paper, we show for the first time that the monocular depth estimation problem can be reformulated as two sub-problems, a view synthesis procedure followed by stereo matching, with two intriguing properties, namely i) geometrical constraints can be explicitly imposed during inference; ii) demand on labelled depth data can be greatly alleviated. We show that the whole pipeline can still be trained in an end-to-end fashion and this new formulation plays a critical role in advancing the performance. The resulting model outperforms all the previous monocular depth estimation methods as well as the stereo block matching method in the challenging KITTI dataset by only using a small number of real training data. The model also generalizes well to other monocular depth estimation benchmarks. We also discuss the implications and the advantages of solving monocular depth estimation using stereo methods.

##### Abstract (translated by Google)
先前的单眼深度估计方法采用单一视图并直接对预期结果进行回归。虽然最近的进展是通过在训练期间应用几何启发损失函数来进行的，但推理过程并没有明确强加任何几何约束。因此这些模型完全依赖于数据的质量和学习的有效性来推广。这或者导致次优结果或者需要大量标记数据的大量地面实况来产生合理的结果。在本文中，我们首次展示了单眼深度估计问题可以被重新表述为两个子问题，一个视图合成过程，然后是立体匹配，具有两个有趣的特性，即i）在推理过程中可以明确强加几何约束; ii）对标记的深度数据的需求可以大大减轻。我们表明，整个管道仍然可以以端到端的方式进行培训，而这种新配方在提高性能方面起着关键作用。通过仅使用少量实际训练数据，所得模型胜过所有以前的单眼深度估计方法以及具有挑战性的KITTI数据集中的立体块匹配方法。该模型也很好地推广到其他单眼深度估计基准。我们还讨论了使用立体方法解决单眼深度估计的含义和优点。

##### URL
[http://arxiv.org/abs/1803.02612](http://arxiv.org/abs/1803.02612)

##### PDF
[http://arxiv.org/pdf/1803.02612](http://arxiv.org/pdf/1803.02612)

