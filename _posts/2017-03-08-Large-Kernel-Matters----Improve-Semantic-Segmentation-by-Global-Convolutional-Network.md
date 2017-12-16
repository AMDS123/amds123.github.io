---
layout: post
title: "Large Kernel Matters -- Improve Semantic Segmentation by Global Convolutional Network"
date: 2017-03-08 06:14:55
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification Prediction
author: Chao Peng, Xiangyu Zhang, Gang Yu, Guiming Luo, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
One of recent trends [30, 31, 14] in network architec- ture design is stacking small filters (e.g., 1x1 or 3x3) in the entire network because the stacked small filters is more ef- ficient than a large kernel, given the same computational complexity. However, in the field of semantic segmenta- tion, where we need to perform dense per-pixel prediction, we find that the large kernel (and effective receptive field) plays an important role when we have to perform the clas- sification and localization tasks simultaneously. Following our design principle, we propose a Global Convolutional Network to address both the classification and localization issues for the semantic segmentation. We also suggest a residual-based boundary refinement to further refine the ob- ject boundaries. Our approach achieves state-of-art perfor- mance on two public benchmarks and significantly outper- forms previous results, 82.2% (vs 80.2%) on PASCAL VOC 2012 dataset and 76.9% (vs 71.8%) on Cityscapes dataset.

##### Abstract (translated by Google)
网络结构设计中最近的一个趋势[30,31,14]是在整个网络中堆叠小型滤波器（例如1x1或3x3），因为堆叠的小型滤波器比大型的内核效率更高计算复杂度。然而，在我们需要执行密集的每像素预测的语义分割领域，我们发现当我们必须执行分类和本地化任务时，大内核（和有效的接受域）扮演着重要的角色同时。遵循我们的设计原则，我们提出了全球卷积网络来解决语义分割的分类和本地化问题。我们还建议基于残差的边界细化来进一步细化物体边界。我们的方法在两个公共基准上达到了最高水平的性能，并且明显优于以前的结果，其中PASCAL VOC 2012数据集的数据集为82.2％（vs 80.2％），Cityscapes数据集的数据集为76.9％（vs 71.8％）。

##### URL
[https://arxiv.org/abs/1703.02719](https://arxiv.org/abs/1703.02719)

##### PDF
[https://arxiv.org/pdf/1703.02719](https://arxiv.org/pdf/1703.02719)

