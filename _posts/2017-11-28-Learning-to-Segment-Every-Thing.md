---
layout: post
title: "Learning to Segment Every Thing"
date: 2017-11-28 16:05:24
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Ronghang Hu, Piotr Dollár, Kaiming He, Trevor Darrell, Ross Girshick
mathjax: true
---

* content
{:toc}

##### Abstract
Existing methods for object instance segmentation require all training instances to be labeled with segmentation masks. This requirement makes it expensive to annotate new categories and has restricted instance segmentation models to ~100 well-annotated classes. The goal of this paper is to propose a new partially supervised training paradigm, together with a novel weight transfer function, that enables training instance segmentation models over a large set of categories for which all have box annotations, but only a small fraction have mask annotations. These contributions allow us to train Mask R-CNN to detect and segment 3000 visual concepts using box annotations from the Visual Genome dataset and mask annotations from the 80 classes in the COCO dataset. We carefully evaluate our proposed approach in a controlled study on the COCO dataset. This work is a first step towards instance segmentation models that have broad comprehension of the visual world.

##### Abstract (translated by Google)
用于对象实例分割的现有方法要求所有训练实例都用分割掩模标记。这个要求使得注解新的类别变得很昂贵，并且将实例分割模型限制到约100个注释良好的类。本文的目的是提出一种新的部分监督的训练范式，加上一种新颖的权重传递函数，使得训练实例分割模型能够在大量的类别上进行训练，这些类别都有框注释，但只有一小部分具有屏蔽注释。通过这些贡献，我们可以训练Mask R-CNN，使用Visual Genome数据集中的Box注释和COCO数据集中80个类的掩码注释来检测和分割3000个视觉概念。我们在COCO数据集的对照研究中仔细评估了我们提出的方法。这项工作是对广泛理解视觉世界的实例细分模型的第一步。

##### URL
[https://arxiv.org/abs/1711.10370](https://arxiv.org/abs/1711.10370)

##### PDF
[https://arxiv.org/pdf/1711.10370](https://arxiv.org/pdf/1711.10370)

