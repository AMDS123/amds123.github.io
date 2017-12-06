---
layout: post
title: "Lifting Object Detection Datasets into 3D"
date: 2016-07-31 09:49:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection Recognition
author: Joao Carreira, Sara Vicente, Lourdes Agapito, Jorge Batista
mathjax: true
---

* content
{:toc}

##### Abstract
While data has certainly taken the center stage in computer vision in recent years, it can still be difficult to obtain in certain scenarios. In particular, acquiring ground truth 3D shapes of objects pictured in 2D images remains a challenging feat and this has hampered progress in recognition-based object reconstruction from a single image. Here we propose to bypass previous solutions such as 3D scanning or manual design, that scale poorly, and instead populate object category detection datasets semi-automatically with dense, per-object 3D reconstructions, bootstrapped from:(i) class labels, (ii) ground truth figure-ground segmentations and (iii) a small set of keypoint annotations. Our proposed algorithm first estimates camera viewpoint using rigid structure-from-motion and then reconstructs object shapes by optimizing over visual hull proposals guided by loose within-class shape similarity assumptions. The visual hull sampling process attempts to intersect an object's projection cone with the cones of minimal subsets of other similar objects among those pictured from certain vantage points. We show that our method is able to produce convincing per-object 3D reconstructions and to accurately estimate cameras viewpoints on one of the most challenging existing object-category detection datasets, PASCAL VOC. We hope that our results will re-stimulate interest on joint object recognition and 3D reconstruction from a single image.

##### Abstract (translated by Google)
尽管近年来数据已经占据了计算机视觉的中心位置，但在某些情况下仍然很难获得。特别是，获取2D图像中描绘的物体的地面真实3D形状仍然是一个具有挑战性的专长，这妨碍了从单个图像的基于识别的物体重建的进展。在这里，我们建议绕过以前的解决方案，如3D扫描或手动设计，缩放比较差，而是用对象类别检测数据集半自动地密集，按对象三维重建，从（i）类标签，（ii）地面真实图形分割和（iii）一小组关键点注释。我们提出的算法首先使用刚体运动结构估计摄像机视点，然后通过优化视觉外壳建议来重建物体形状，所述视觉外壳建议由松散的类内形状相似性假设引导。视觉船体采样过程试图将物体的投影锥体与其他类似物体的最小子集的圆锥体相交在某些有利位置。我们表明，我们的方法能够产生令人信服的每个对象的三维重建，并准确估计最具挑战性的现有对象类别检测数据集之一，PASCAL VOC的相机观点。我们希望我们的结果能够从单个图像中重新激发对联合对象识别和三维重建的兴趣。

##### URL
[https://arxiv.org/abs/1503.06465](https://arxiv.org/abs/1503.06465)

