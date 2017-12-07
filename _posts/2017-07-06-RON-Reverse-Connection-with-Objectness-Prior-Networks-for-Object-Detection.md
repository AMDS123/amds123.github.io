---
layout: post
title: "RON: Reverse Connection with Objectness Prior Networks for Object Detection"
date: 2017-07-06 08:53:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Tao Kong, Fuchun Sun, Anbang Yao, Huaping Liu, Ming Lu, Yurong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
We present RON, an efficient and effective framework for generic object detection. Our motivation is to smartly associate the best of the region-based (e.g., Faster R-CNN) and region-free (e.g., SSD) methodologies. Under fully convolutional architecture, RON mainly focuses on two fundamental problems: (a) multi-scale object localization and (b) negative sample mining. To address (a), we design the reverse connection, which enables the network to detect objects on multi-levels of CNNs. To deal with (b), we propose the objectness prior to significantly reduce the searching space of objects. We optimize the reverse connection, objectness prior and object detector jointly by a multi-task loss function, thus RON can directly predict final detection results from all locations of various feature maps. Extensive experiments on the challenging PASCAL VOC 2007, PASCAL VOC 2012 and MS COCO benchmarks demonstrate the competitive performance of RON. Specifically, with VGG-16 and low resolution 384X384 input size, the network gets 81.3% mAP on PASCAL VOC 2007, 80.7% mAP on PASCAL VOC 2012 datasets. Its superiority increases when datasets become larger and more difficult, as demonstrated by the results on the MS COCO dataset. With 1.5G GPU memory at test phase, the speed of the network is 15 FPS, 3X faster than the Faster R-CNN counterpart.

##### Abstract (translated by Google)
我们提供RON，一个通用对象检测的高效和有效的框架。我们的动机是巧妙地将基于地区的最佳（例如更快的R-CNN）和无地区（例如，SSD）方法关联起来。在完全卷积结构下，RON主要关注两个基本问题：（a）多尺度目标定位和（b）负样本挖掘​​。为了解决（a），我们设计了反向连接，它使网络能够检测多级CNN上的对象。为了处理（b），我们在大大减少对象的搜索空间之前提出了对象。我们通过多任务丢失函数联合优化反向连接，对象先验和目标检测器，从而可以直接预测各个特征映射中各个位置的最终检测结果。在具有挑战性的PASCAL VOC 2007，PASCAL VOC 2012和MS COCO基准上的大量实验证明了RON的竞争力。具体来说，在VGG-16和低分辨率384X384输入大小的情况下，PASCAL VOC 2007上网络获得81.3％mAP，PASCAL VOC 2012数据集获得80.7％mAP。 MSCOCO数据集的结果显示，数据集越来越大，越来越困难，其优势越来越明显。在测试阶段使用1.5G GPU内存，网络速度为15 FPS，比R-CNN速度快3倍。

##### URL
[https://arxiv.org/abs/1707.01691](https://arxiv.org/abs/1707.01691)

##### PDF
[https://arxiv.org/pdf/1707.01691](https://arxiv.org/pdf/1707.01691)

