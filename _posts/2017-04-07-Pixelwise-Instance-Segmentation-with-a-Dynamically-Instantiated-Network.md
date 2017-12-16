---
layout: post
title: "Pixelwise Instance Segmentation with a Dynamically Instantiated Network"
date: 2017-04-07 22:14:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Detection
author: Anurag Arnab, Philip H.S Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation and object detection research have recently achieved rapid progress. However, the former task has no notion of different instances of the same object, and the latter operates at a coarse, bounding-box level. We propose an Instance Segmentation system that produces a segmentation map where each pixel is assigned an object class and instance identity label. Most approaches adapt object detectors to produce segments instead of boxes. In contrast, our method is based on an initial semantic segmentation module, which feeds into an instance subnetwork. This subnetwork uses the initial category-level segmentation, along with cues from the output of an object detector, within an end-to-end CRF to predict instances. This part of our model is dynamically instantiated to produce a variable number of instances per image. Our end-to-end approach requires no post-processing and considers the image holistically, instead of processing independent proposals. Therefore, unlike some related work, a pixel cannot belong to multiple instances. Furthermore, far more precise segmentations are achieved, as shown by our state-of-the-art results (particularly at high IoU thresholds) on the Pascal VOC and Cityscapes datasets.

##### Abstract (translated by Google)
语义分割和对象检测研究近来取得了快速的进展。然而，前一个任务没有关于同一个对象的不同实例的概念，而后一个任务在粗糙的边界框中运行。我们提出一个实例分割系统，该系统产生一个分割图，其中每个像素被分配一个对象类和实例标识符。大多数方法都是使物体检测器来生成分段而不是盒子。相反，我们的方法是基于一个初始的语义分割模块，它馈入一个实例子网络。该子网络在端到端CRF内使用初始类别级别的分段以及来自对象检测器输出的提示来预测实例。我们模型的这一部分是动态实例化的，以便为每个图像生成可变数量的实例。我们的端到端方法不需要后处理，而是整体考虑图像，而不是处理独立的提议。因此，与一些相关的工作不同，像素不能属于多个实例。此外，我们的Pascal VOC和Cityscapes数据集的最新结果（特别是在高IoU阈值下）显示出更精确的分段。

##### URL
[https://arxiv.org/abs/1704.02386](https://arxiv.org/abs/1704.02386)

##### PDF
[https://arxiv.org/pdf/1704.02386](https://arxiv.org/pdf/1704.02386)

