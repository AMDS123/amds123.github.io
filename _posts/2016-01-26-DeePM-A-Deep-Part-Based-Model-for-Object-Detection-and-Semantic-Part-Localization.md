---
layout: post
title: "DeePM: A Deep Part-Based Model for Object Detection and Semantic Part Localization"
date: 2016-01-26 09:14:31
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Jun Zhu, Xianjie Chen, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a deep part-based model (DeePM) for symbiotic object detection and semantic part localization. For this purpose, we annotate semantic parts for all 20 object categories on the PASCAL VOC 2012 dataset, which provides information on object pose, occlusion, viewpoint and functionality. DeePM is a latent graphical model based on the state-of-the-art R-CNN framework, which learns an explicit representation of the object-part configuration with flexible type sharing (e.g., a sideview horse head can be shared by a fully-visible sideview horse and a highly truncated sideview horse with head and neck only). For comparison, we also present an end-to-end Object-Part (OP) R-CNN which learns an implicit feature representation for jointly mapping an image ROI to the object and part bounding boxes. We evaluate the proposed methods for both the object and part detection performance on PASCAL VOC 2012, and show that DeePM consistently outperforms OP R-CNN in detecting objects and parts. In addition, it obtains superior performance to Fast and Faster R-CNNs in object detection.

##### Abstract (translated by Google)
在本文中，我们提出了一个基于深度部分的模型（DeePM）共生对象检测和语义部分定位。为此，我们为PASCAL VOC 2012数据集上的所有20个对象类别注释语义部分，提供关于对象姿态，遮挡，视点和功能的信息。 DeePM是基于最先进的R-CNN框架的潜在的图形模型，通过灵活的类型共享学习了对象部分配置的显式表示（例如，可见的侧视马和只有头颈的高度截断的侧视马）。为了比较，我们还提出了端到端的对象部分（OP）R-CNN，其学习用于将图像ROI联合映射到对象和部分边界框的隐式特征表示。我们评估了在PASCAL VOC 2012上对物体和零件检测性能提出的方法，并且表明DeePM在检测物体和零件方面始终优于OP R-CNN。另外，它在物体检测中获得了快速和快速R-CNN的优越性能。

##### URL
[https://arxiv.org/abs/1511.07131](https://arxiv.org/abs/1511.07131)

##### PDF
[https://arxiv.org/pdf/1511.07131](https://arxiv.org/pdf/1511.07131)

