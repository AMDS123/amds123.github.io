---
layout: post
title: "Context Tricks for Cheap Semantic Segmentation"
date: 2015-02-17 18:08:53
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Thanapong Intharah, Gabriel J. Brostow
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate semantic labeling of image pixels is difficult because intra-class variability is often greater than inter-class variability. In turn, fast semantic segmentation is hard because accurate models are usually too complicated to also run quickly at test-time. Our experience with building and running semantic segmentation systems has also shown a reasonably obvious bottleneck on model complexity, imposed by small training datasets. We therefore propose two simple complementary strategies that leverage context to give better semantic segmentation, while scaling up or down to train on different-sized datasets. As easy modifications for existing semantic segmentation algorithms, we introduce Decorrelated Semantic Texton Forests, and the Context Sensitive Image Level Prior. The proposed modifications are tested using a Semantic Texton Forest (STF) system, and the modifications are validated on two standard benchmark datasets, MSRC-21 and PascalVOC-2010. In Python based comparisons, our system is insignificantly slower than STF at test-time, yet produces superior semantic segmentations overall, with just push-button training.

##### Abstract (translated by Google)
图像像素的精确语义标记是困难的，因为类内变异性通常大于类间变化性。反过来，快速的语义分割是很难的，因为准确的模型通常太复杂，不能在测试时间快速运行。我们在构建和运行语义分割系统方面的经验也显示出由小型训练数据集引起的模型复杂性的一个相当明显的瓶颈。因此，我们提出两个简单的互补策略，利用上下文来提供更好的语义分割，同时向上或向下扩展以训练不同大小的数据集。作为对现有语义分割算法的简单修改，我们引入了Decorrelated Semantic Texton Forests和Context Sensitive Image Level Prior。所提出的修改使用语义Texton森林（STF）系统进行测试，修改在两个标准基准数据集MSRC-21和PascalVOC-2010上进行了验证。在基于Python的比较中，我们的系统在测试时间比STF慢得多，但是只需按下按钮训练就能产生出色的语义分割。

##### URL
[https://arxiv.org/abs/1502.04983](https://arxiv.org/abs/1502.04983)

##### PDF
[https://arxiv.org/pdf/1502.04983](https://arxiv.org/pdf/1502.04983)

