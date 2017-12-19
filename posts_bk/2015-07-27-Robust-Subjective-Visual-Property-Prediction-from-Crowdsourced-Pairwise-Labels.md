---
layout: post
title: "Robust Subjective Visual Property Prediction from Crowdsourced Pairwise Labels"
date: 2015-07-27 14:42:17
categories: arXiv_CV
tags: arXiv_CV Sparse Prediction Detection Recognition
author: Yanwei Fu, Timothy M. Hospedales, Tao Xiang, Jiechao Xiong, Shaogang Gong, Yizhou Wang, Yuan Yao
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of estimating subjective visual properties from image and video has attracted increasing interest. A subjective visual property is useful either on its own (e.g. image and video interestingness) or as an intermediate representation for visual recognition (e.g. a relative attribute). Due to its ambiguous nature, annotating the value of a subjective visual property for learning a prediction model is challenging. To make the annotation more reliable, recent studies employ crowdsourcing tools to collect pairwise comparison labels because human annotators are much better at ranking two images/videos (e.g. which one is more interesting) than giving an absolute value to each of them separately. However, using crowdsourced data also introduces outliers. Existing methods rely on majority voting to prune the annotation outliers/errors. They thus require large amount of pairwise labels to be collected. More importantly as a local outlier detection method, majority voting is ineffective in identifying outliers that can cause global ranking inconsistencies. In this paper, we propose a more principled way to identify annotation outliers by formulating the subjective visual property prediction task as a unified robust learning to rank problem, tackling both the outlier detection and learning to rank jointly. Differing from existing methods, the proposed method integrates local pairwise comparison labels together to minimise a cost that corresponds to global inconsistency of ranking order. This not only leads to better detection of annotation outliers but also enables learning with extremely sparse annotations. Extensive experiments on various benchmark datasets demonstrate that our new approach significantly outperforms state-of-the-arts alternatives.

##### Abstract (translated by Google)
从图像和视频估计主观视觉特性的问题引起了越来越多的兴趣。主观视觉属性本身（例如图像和视频兴趣度）或作为视觉识别的中间表示（例如相对属性）是有用的。由于其模棱两可的性质，注释主观视觉属性的价值，以学习预测模型是具有挑战性的。为了使注释更可靠，最近的研究采用众包工具来收集成对比较标签，因为人类注释者在对两个图像/视频（例如，哪一个更有意思）进行排名方面好得多，而不是分别对它们分别赋予绝对值。但是，使用众包的数据也会引入异常值。现有的方法依靠大多数投票来修剪注释的异常值/错误。因此他们需要收集大量的成对标签。更重要的是，作为局部异常值检测方法，大多数投票无法识别可能导致全球排名不一致的异常值。本文通过将主观视觉属性预测任务作为统一的鲁棒性学习问题排序问题，提出了一种更加有效的识别异常值的原理方法，同时攻克了异常检测和学习共同排序问题。与现有方法不同，所提出的方法将局部成对比较标签集成在一起，以最小化与排名顺序的全局不一致相对应的成本。这不仅可以更好地检测注释异常值，还可以使用极其稀疏的注释进行学习。对各种基准数据集的大量实验表明，我们的新方法明显优于最新的替代方案。

##### URL
[https://arxiv.org/abs/1501.06202](https://arxiv.org/abs/1501.06202)

##### PDF
[https://arxiv.org/pdf/1501.06202](https://arxiv.org/pdf/1501.06202)

