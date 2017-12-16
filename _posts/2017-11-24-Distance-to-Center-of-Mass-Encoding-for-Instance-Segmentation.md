---
layout: post
title: "Distance to Center of Mass Encoding for Instance Segmentation"
date: 2017-11-24 17:53:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Detection
author: Thomio Watanabe, Denis Wolf
mathjax: true
---

* content
{:toc}

##### Abstract
The instance segmentation can be considered an extension of the object detection problem where bounding boxes are replaced by object contours. Strictly speaking the problem requires to identify each pixel instance and class independently of the artifice used for this mean. The advantage of instance segmentation over the usual object detection lies in the precise delineation of objects improving object localization. Additionally, object contours allow the evaluation of partial occlusion with basic image processing algorithms. This work approaches the instance segmentation problem as an annotation problem and presents a novel technique to encode and decode ground truth annotations. We propose a mathematical representation of instances that any deep semantic segmentation model can learn and generalize. Each individual instance is represented by a center of mass and a field of vectors pointing to it. This encoding technique has been denominated Distance to Center of Mass Encoding (DCME).

##### Abstract (translated by Google)
实例分割可以被认为是边界框被对象轮廓替换的对象检测问题的扩展。严格地说，这个问题需要识别每个像素实例和类别，而不依赖于用于这个意思的技巧。实例分割优于通常的对象检测的优点在于对对象进行精确定位以改善对象定位。另外，物体轮廓允许用基本图像处理算法评估部分遮挡。这项工作接近实例分割问题作为一个注释问题，并提出了一种新的技术来编码和解码地面真实注释。我们提出了任何深度语义分割模型可以学习和概括的实例的数学表示。每个单独的实例由一个质心和一个指向它的向量的字段来表示。这种编码技术已被命名为距离质量编码中心（DCME）。

##### URL
[https://arxiv.org/abs/1711.09060](https://arxiv.org/abs/1711.09060)

##### PDF
[https://arxiv.org/pdf/1711.09060](https://arxiv.org/pdf/1711.09060)

