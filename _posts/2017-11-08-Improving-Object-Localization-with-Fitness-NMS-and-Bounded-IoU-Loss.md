---
layout: post
title: "Improving Object Localization with Fitness NMS and Bounded IoU Loss"
date: 2017-11-08 02:01:13
categories: arXiv_CV
tags: arXiv_CV Detection
author: Lachlan Tychsen-Smith, Lars Petersson
mathjax: true
---

* content
{:toc}

##### Abstract
We demonstrate that many detection methods are designed to identify only a sufficently accurate bounding box, rather than the best available one. To address this issue we propose a simple and fast modification to the existing methods called Fitness NMS. This method is tested with the DeNet model and obtains a significantly improved MAP at greater localization accuracies without a loss in evaluation rate. Next we derive a novel bounding box regression loss based on a set of IoU upper bounds that better matches the goal of IoU maximization while still providing good convergence properties. Following these novelties we investigate RoI clustering schemes for improving evaluation rates for the DeNet \textit{wide} model variants and provide an analysis of localization performance at various input image dimensions. We obtain a MAP[0.5:0.95] of 33.6\%@79Hz and 41.8\%@5Hz for MSCOCO and a Titan X (Maxwell).

##### Abstract (translated by Google)
我们证明，许多检测方法的目的只是确定一个足够精确的边界框，而不是最好的一个。为了解决这个问题，我们建议对现有的称为Fitness NMS的方法进行简单快速的修改。用DeNet模型对这种方法进行了测试，并且在更高的定位精度下获得了显着改善的MAP而没有评估速率的损失。接下来，我们基于一组IoU上限推导出新的边界框回归损失，其更好地匹配IoU最大化的目标，同时仍然提供良好的收敛性质。在这些新颖性之后，我们研究了RoI聚类方案，以提高DeNet \ textit {wide}模型变体的评估速度，并提供各种输入图像尺寸下的定位性能分析。对于MSCOCO和Titan X（Maxwell），我们获得33.6％@ 79Hz和41.8％@ 5Hz的MAP [0.5：0.95]。

##### URL
[https://arxiv.org/abs/1711.00164](https://arxiv.org/abs/1711.00164)

##### PDF
[https://arxiv.org/pdf/1711.00164](https://arxiv.org/pdf/1711.00164)

