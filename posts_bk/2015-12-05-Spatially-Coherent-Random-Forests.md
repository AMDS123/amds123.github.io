---
layout: post
title: "Spatially Coherent Random Forests"
date: 2015-12-05 10:13:06
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Tal Remez, Shai Avidan
mathjax: true
---

* content
{:toc}

##### Abstract
Spatially Coherent Random Forest (SCRF) extends Random Forest to create spatially coherent labeling. Each split function in SCRF is evaluated based on a traditional information gain measure that is regularized by a spatial coherency term. This way, SCRF is encouraged to choose split functions that cluster pixels both in appearance space and in image space. In particular, we use SCRF to detect contours in images, where contours are taken to be the boundaries between different regions. Each tree in the forest produces a segmentation of the image plane and the boundaries of the segmentations of all trees are aggregated to produce a final hierarchical contour map. We show that this modification improves the performance of regular Random Forest by about 10% on the standard Berkeley Segmentation Datasets. We believe that SCRF can be used in other settings as well.

##### Abstract (translated by Google)
空间相干随机森林（SCRF）扩展随机森林来创建空间相干标记。 SCRF中的每个拆分函数都是基于由空间一致性项调整的传统信息增益度量来评估的。这样，鼓励SCRF选择在外观空间和图像空间中对像素进行聚类的分割函数。特别是，我们使用SCRF来检测图像中的轮廓，轮廓被视为不同区域之间的边界。森林中的每棵树都会产生图像平面的分割，并聚合所有树的分割边界以产生最终的分层等高线图。我们证明这个修改在标准的Berkeley分割数据集上提高了10％的规则随机森林的性能。我们相信SCRF也可以用于其他设置。

##### URL
[https://arxiv.org/abs/1511.02911](https://arxiv.org/abs/1511.02911)

##### PDF
[https://arxiv.org/pdf/1511.02911](https://arxiv.org/pdf/1511.02911)

