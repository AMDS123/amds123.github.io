---
layout: post
title: "A flexible model for training action localization with varying levels of supervision"
date: 2018-06-29 09:56:41
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization Detection
author: Guilhem Ch&#xe9;ron, Jean-Baptiste Alayrac, Ivan Laptev, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
Spatio-temporal action detection in videos is typically addressed in a fully-supervised setup with manual annotation of training videos required at every frame. Since such annotation is extremely tedious and prohibits scalability, there is a clear need to minimize the amount of manual supervision. In this work we propose a unifying framework that can handle and combine varying types of less-demanding weak supervision. Our model is based on discriminative clustering and integrates different types of supervision as constraints on the optimization. We investigate applications of such a model to training setups with alternative supervisory signals ranging from video-level class labels over temporal points or sparse action bounding boxes to the full per-frame annotation of action bounding boxes. Experiments on the challenging UCF101-24 and DALY datasets demonstrate competitive performance of our method at a fraction of supervision used by previous methods. The flexibility of our model enables joint learning from data with different levels of annotation. Experimental results demonstrate a significant gain by adding a few fully supervised examples to otherwise weakly labeled videos.

##### Abstract (translated by Google)
视频中的时空动作检测通常在完全监督的设置中进行解决，并且每帧需要手动标注培训视频。由于这种注释非常繁琐并且禁止可扩展性，因此显然需要最小化手动监督的量。在这项工作中，我们提出了一个统一的框架，可以处理和结合不同类型的要求不高的弱监督。我们的模型基于歧视性聚类，并将不同类型的监督作为优化的约束条件。我们调查这种模型的应用程序与训练设置替代监督信号范围从时间点或稀疏动作边界框视频级别标签到动作边界框的全帧每个注释。在具有挑战性的UCF101-24和DALY数据集上的实验证明了我们的方法在以前方法使用的一小部分监督下的竞争性能。我们模型的灵活性使得能够从具有不同注释级别的数据中进行联合学习。实验结果表明，通过在其他弱标签视频中添加一些完全监督的示例可以获得显着的收益。

##### URL
[http://arxiv.org/abs/1806.11328](http://arxiv.org/abs/1806.11328)

##### PDF
[http://arxiv.org/pdf/1806.11328](http://arxiv.org/pdf/1806.11328)

