---
layout: post
title: "Analysis and Optimization of Loss Functions for Multiclass, Top-k, and Multilabel Classification"
date: 2016-12-12 13:20:09
categories: arXiv_CV
tags: arXiv_CV Image_Classification Optimization Classification
author: Maksim Lapin, Matthias Hein, Bernt Schiele
mathjax: true
---

* content
{:toc}

##### Abstract
Top-k error is currently a popular performance measure on large scale image classification benchmarks such as ImageNet and Places. Despite its wide acceptance, our understanding of this metric is limited as most of the previous research is focused on its special case, the top-1 error. In this work, we explore two directions that shed more light on the top-k error. First, we provide an in-depth analysis of established and recently proposed single-label multiclass methods along with a detailed account of efficient optimization algorithms for them. Our results indicate that the softmax loss and the smooth multiclass SVM are surprisingly competitive in top-k error uniformly across all k, which can be explained by our analysis of multiclass top-k calibration. Further improvements for a specific k are possible with a number of proposed top-k loss functions. Second, we use the top-k methods to explore the transition from multiclass to multilabel learning. In particular, we find that it is possible to obtain effective multilabel classifiers on Pascal VOC using a single label per image for training, while the gap between multiclass and multilabel methods on MS COCO is more significant. Finally, our contribution of efficient algorithms for training with the considered top-k and multilabel loss functions is of independent interest.

##### Abstract (translated by Google)
Top-k错误是目前在大型图像分类基准（如ImageNet和Places）上流行的性能指标。尽管被广泛接受，但我们对这一指标的理解是有限的，因为以前的大部分研究都集中在其特殊情况 - 前1个错误。在这项工作中，我们探索两个方向，揭示了top-k错误。首先，我们对建立和最近提出的单标签多类方法进行了深入分析，并详细介绍了有效的优化算法。我们的结果表明，softmax损失和平滑的多类SVM在所有k中统一的top-k误差是令人惊讶的，这可以通过我们对多类top-k校准的分析来解释。对于特定的k值的进一步改进对于许多提议的top-k损失函数是可能的。其次，我们使用top-k方法来探索从多类到多标的学习过渡。特别是，我们发现有可能获得有效的多标签帕斯卡VOC分类器使用单个标签每个图像进行培训，而多标签和多标签方法之间的空白MS COCO更为重要。最后，我们对考虑top-k和multilabel损失函数的高效算法的训练贡献是独立的。

##### URL
[https://arxiv.org/abs/1612.03663](https://arxiv.org/abs/1612.03663)

##### PDF
[https://arxiv.org/pdf/1612.03663](https://arxiv.org/pdf/1612.03663)

