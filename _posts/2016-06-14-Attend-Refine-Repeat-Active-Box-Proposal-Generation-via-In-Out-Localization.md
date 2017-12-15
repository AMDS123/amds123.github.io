---
layout: post
title: "Attend Refine Repeat: Active Box Proposal Generation via In-Out Localization"
date: 2016-06-14 16:35:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Prediction Detection
author: Spyros Gidaris, Nikos Komodakis
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of computing category agnostic bounding box proposals is utilized as a core component in many computer vision tasks and thus has lately attracted a lot of attention. In this work we propose a new approach to tackle this problem that is based on an active strategy for generating box proposals that starts from a set of seed boxes, which are uniformly distributed on the image, and then progressively moves its attention on the promising image areas where it is more likely to discover well localized bounding box proposals. We call our approach AttractioNet and a core component of it is a CNN-based category agnostic object location refinement module that is capable of yielding accurate and robust bounding box predictions regardless of the object category. We extensively evaluate our AttractioNet approach on several image datasets (i.e. COCO, PASCAL, ImageNet detection and NYU-Depth V2 datasets) reporting on all of them state-of-the-art results that surpass the previous work in the field by a significant margin and also providing strong empirical evidence that our approach is capable to generalize to unseen categories. Furthermore, we evaluate our AttractioNet proposals in the context of the object detection task using a VGG16-Net based detector and the achieved detection performance on COCO manages to significantly surpass all other VGG16-Net based detectors while even being competitive with a heavily tuned ResNet-101 based detector. Code as well as box proposals computed for several datasets are available at:: this https URL

##### Abstract (translated by Google)
计算类别不可知边界框提议的问题被用作许多计算机视觉任务的核心部分，因此近来引起了很多关注。在这项工作中，我们提出了一种新的方法来解决这个问题，这个方法是基于一个积极的策略来生成盒子提议，从一组种子盒子开始，它们在图像上均匀分布，然后逐渐将注意力转移到有希望的图像上更有可能发现本地化的边界框提案的区域。我们把我们的方法称为AttractioNet，它的一个核心组件是基于CNN的类别不可知的对象位置细化模块，无论对象类别如何，它都能够产生精确和可靠的边界框预测。我们在几个图像数据集（即COCO，PASCAL，ImageNet检测和NYU-Depth V2数据集）上对我们的AttractioNet方法进行了广泛的评估，报告了所有这些数据集的最新结果，也提供了强有力的经验证据表明我们的方法能够推广到看不见的类别。此外，我们使用基于VGG16-Net的检测器评估我们的AttractioNet方案，使用基于VGG16-Net的检测器实现对象检测任务，并且在COCO上实现的检测性能能够显着超越所有其他基于VGG16-Net的检测器，甚至可以与经过严格调整的ResNet-基于101的检测器。代码以及为多个数据集计算的方框提议可在:: this https URL处获得

##### URL
[https://arxiv.org/abs/1606.04446](https://arxiv.org/abs/1606.04446)

##### PDF
[https://arxiv.org/pdf/1606.04446](https://arxiv.org/pdf/1606.04446)

