---
layout: post
title: "HyperNet: Towards Accurate Region Proposal Generation and Joint Object Detection"
date: 2016-04-03 06:52:14
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Tao Kong, Anbang Yao, Yurong Chen, Fuchun Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Almost all of the current top-performing object detection networks employ region proposals to guide the search for object instances. State-of-the-art region proposal methods usually need several thousand proposals to get high recall, thus hurting the detection efficiency. Although the latest Region Proposal Network method gets promising detection accuracy with several hundred proposals, it still struggles in small-size object detection and precise localization (e.g., large IoU thresholds), mainly due to the coarseness of its feature maps. In this paper, we present a deep hierarchical network, namely HyperNet, for handling region proposal generation and object detection jointly. Our HyperNet is primarily based on an elaborately designed Hyper Feature which aggregates hierarchical feature maps first and then compresses them into a uniform space. The Hyper Features well incorporate deep but highly semantic, intermediate but really complementary, and shallow but naturally high-resolution features of the image, thus enabling us to construct HyperNet by sharing them both in generating proposals and detecting objects via an end-to-end joint training strategy. For the deep VGG16 model, our method achieves completely leading recall and state-of-the-art object detection accuracy on PASCAL VOC 2007 and 2012 using only 100 proposals per image. It runs with a speed of 5 fps (including all steps) on a GPU, thus having the potential for real-time processing.

##### Abstract (translated by Google)
几乎所有当前性能最好的对象检测网络都使用区域提议来指导对象实例的搜索。最先进的区域建议方法通常需要几千个建议才能获得高回忆，从而损害了检测效率。虽然最新的区域提议网络方法在数百个提案中获得了有希望的检测准确性，但其仍然在小尺寸目标检测和精确定位（例如，大的IoU阈值）方面挣扎，主要是由于其特征图的粗糙。在本文中，我们提出了一个深层次的网络，即HyperNet，共同处理区域建议生成和对象检测。我们的HyperNet主要基于一个精心设计的超级特征，它先集合了分级特征映射，然后将它们压缩到一个统一的空间。超级特性很好地融入了深层的，但高度语义的，中间但真正互补的，浅的，但自然高分辨率的图像特征，从而使我们能够构建HyperNet，通过共享它们来生成提案和通过端到端检测对象联合培训战略。对于深VGG16模型，我们的方法在PASCAL VOC 2007和2012上仅使用每个图像100个方案，实现了领先的召回率和最先进的目标检测精度。它在GPU上运行速度为5 fps（包括所有步骤），因此具有实时处理的潜力。

##### URL
[https://arxiv.org/abs/1604.00600](https://arxiv.org/abs/1604.00600)

