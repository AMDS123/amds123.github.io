---
layout: post
title: "Spatial Semantic Regularisation for Large Scale Object Detection"
date: 2015-10-10 15:15:45
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Detection Relation
author: Damian Mrowca, Marcus Rohrbach, Judy Hoffman, Ronghang Hu, Kate Saenko, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Large scale object detection with thousands of classes introduces the problem of many contradicting false positive detections, which have to be suppressed. Class-independent non-maximum suppression has traditionally been used for this step, but it does not scale well as the number of classes grows. Traditional non-maximum suppression does not consider label- and instance-level relationships nor does it allow an exploitation of the spatial layout of detection proposals. We propose a new multi-class spatial semantic regularisation method based on affinity propagation clustering, which simultaneously optimises across all categories and all proposed locations in the image, to improve both the localisation and categorisation of selected detection proposals. Constraints are shared across the labels through the semantic WordNet hierarchy. Our approach proves to be especially useful in large scale settings with thousands of classes, where spatial and semantic interactions are very frequent and only weakly supervised detectors can be built due to a lack of bounding box annotations. Detection experiments are conducted on the ImageNet and COCO dataset, and in settings with thousands of detected categories. Our method provides a significant precision improvement by reducing false positives, while simultaneously improving the recall.

##### Abstract (translated by Google)
数千个类别的大规模物体检测引入了许多矛盾的假阳性检测问题，这些检测必须被抑制。传统上，类独立非最大抑制用于这一步，但是随着类的数量增长，它不能很好地扩展。传统的非最大抑制不考虑标签和实例级别的关系，也不允许利用检测建议的空间布局。我们提出了一种新的基于亲和力传播聚类的多类空间语义正则化方法，该方法同时对图像中所有类别和所有提出的位置进行优化，以改善所选检测方案的定位和分类。约束是通过语义WordNet层次结构在标签之间共享的。我们的方法在数以千计的类的大规模设置中被证明是特别有用的，其中空间和语义交互非常频繁，并且由于缺少边界框注释，只能建立弱监督的检测器。在ImageNet和COCO数据集上进行检测实验，并在数千个检测类别的设置中进行。我们的方法通过减少误报，同时提高召回率，显着提高精度。

##### URL
[https://arxiv.org/abs/1510.02949](https://arxiv.org/abs/1510.02949)

##### PDF
[https://arxiv.org/pdf/1510.02949](https://arxiv.org/pdf/1510.02949)

