---
layout: post
title: "Class Correlation affects Single Object Localization using Pre-trained ConvNets"
date: 2017-10-27 05:11:01
categories: arXiv_CV
tags: arXiv_CV Classification Relation
author: Pokkalla Harsha Vardhan, Kunal Sekhri, Dipan K. Pal, Marios Savvides
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of object localization has become one of the mainstream problems of vision. Most of the algorithms proposed involve the design for the model to be specifically for localizing objects. In this paper, we explore whether a pre-trained canonical ConvNet (without fine-tuning) trained purely for object classification on one dataset with global image level labels can be used to localize objects in images containing a single instance on a separate dataset while generalizing to novel classes. We propose a simple algorithm involving cropping and blackening out regions in the image space called Explicit Image Space based Search (EISS) for locating the most responsive regions in an image in the context of object localization. EISS brings to light the interesting phenomenon of a ConvNets responding more to features within objects as opposed to object level descriptors, as the classes in the training data get more correlated (visually/semantically similar).

##### Abstract (translated by Google)
物体定位问题已经成为视觉的主流问题之一。所提出的大多数算法都涉及模型的设计，以专门用于对象的本地化。在本文中，我们探讨一个预先训练的规范ConvNet（没有微调）纯粹是否训练纯粹用于一个数据集与全局图像水平标签上的对象分类可以用来本地化包含在单独的数据集上的单个实例的图像中的对象，而泛化到小说类。我们提出了一个简单的算法，涉及在图像空间中裁剪和变黑区域，称为基于显式图像空间的搜索（EISS），用于在对象定位的上下文中定位图像中响应最快的区域。 EISS揭示了一个有趣的现象，即ConvNets更多地响应对象内的特征，而不是对象级描述符，因为训练数据中的类更加相关（视觉/语义相似）。

##### URL
[https://arxiv.org/abs/1710.09685](https://arxiv.org/abs/1710.09685)

##### PDF
[https://arxiv.org/pdf/1710.09685](https://arxiv.org/pdf/1710.09685)

