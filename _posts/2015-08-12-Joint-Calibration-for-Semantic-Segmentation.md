---
layout: post
title: "Joint Calibration for Semantic Segmentation"
date: 2015-08-12 14:20:08
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised Semantic_Segmentation Classification Prediction
author: Holger Caesar, Jasper Uijlings, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation is the task of assigning a class-label to each pixel in an image. We propose a region-based semantic segmentation framework which handles both full and weak supervision, and addresses three common problems: (1) Objects occur at multiple scales and therefore we should use regions at multiple scales. However, these regions are overlapping which creates conflicting class predictions at the pixel-level. (2) Class frequencies are highly imbalanced in realistic datasets. (3) Each pixel can only be assigned to a single class, which creates competition between classes. We address all three problems with a joint calibration method which optimizes a multi-class loss defined over the final pixel-level output labeling, as opposed to simply region classification. Our method outperforms the state-of-the-art on the popular SIFT Flow [18] dataset in both the fully and weakly supervised setting by a considerably margin (+6% and +10%, respectively).

##### Abstract (translated by Google)
语义分割是为图像中的每个像素分配类标签的任务。我们提出了一个基于区域的语义分割框架，它可以处理全面的和弱的监督，并且解决了三个常见的问题：（1）对象出现在多个尺度上，因此我们应该使用多个尺度的区域。但是，这些区域重叠，从而在像素级产生相互冲突的类别预测。 （2）实际数据集中班级频率高度失衡。 （3）每个像素只能分配给一个班级，这就造成了班级之间的竞争。我们用一种联合校准方法来解决所有这三个问题，该方法优化了在最终像素级输出标签上定义的多级丢失，而不是简单的区域分类。我们的方法在流行的SIFT Flow [18]数据集中的表现优于现有技术，在完全和弱监督环境下都有相当大的差距（分别为+ 6％和+ 10％）。

##### URL
[https://arxiv.org/abs/1507.01581](https://arxiv.org/abs/1507.01581)

##### PDF
[https://arxiv.org/pdf/1507.01581](https://arxiv.org/pdf/1507.01581)

