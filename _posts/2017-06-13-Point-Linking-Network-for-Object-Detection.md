---
layout: post
title: "Point Linking Network for Object Detection"
date: 2017-06-13 05:04:37
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Xinggang Wang, Kaibing Chen, Zilong Huang, Cong Yao, Wenyu Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection is a core problem in computer vision. With the development of deep ConvNets, the performance of object detectors has been dramatically improved. The deep ConvNets based object detectors mainly focus on regressing the coordinates of bounding box, e.g., Faster-R-CNN, YOLO and SSD. Different from these methods that considering bounding box as a whole, we propose a novel object bounding box representation using points and links and implemented using deep ConvNets, termed as Point Linking Network (PLN). Specifically, we regress the corner/center points of bounding-box and their links using a fully convolutional network; then we map the corner points and their links back to multiple bounding boxes; finally an object detection result is obtained by fusing the multiple bounding boxes. PLN is naturally robust to object occlusion and flexible to object scale variation and aspect ratio variation. In the experiments, PLN with the Inception-v2 model achieves state-of-the-art single-model and single-scale results on the PASCAL VOC 2007, the PASCAL VOC 2012 and the COCO detection benchmarks without bells and whistles. The source code will be released.

##### Abstract (translated by Google)
目标检测是计算机视觉中的核心问题。随着深度通信网络的发展，物体探测器的性能得到了显着提高。基于ConvNets的深度目标检测器主要着眼于回归边界框的坐标，例如Faster-R-CNN，YOLO和SSD。与这些考虑边界框整体的方法不同，我们提出了一种新的使用点和链接的对象边界框表示方法，并使用深度网络（Point Linking Network，PLN）实现。具体来说，我们使用完全卷积网络来回归边界框和它们的链接的角点/中心点;然后我们将角点和它们的链接映射回多个边界框;最后通过对多个边界框进行融合得到目标检测结果。 PLN对于物体遮挡自然是强健的，并且灵活地适应物体的尺度变化和纵横比变化。在实验中，使用Inception-v2模型的PLN在PASCAL VOC 2007，PASCAL VOC 2012和无COCO检测基准上获得了最先进的单模型和单尺度结果。源代码将被释放。

##### URL
[https://arxiv.org/abs/1706.03646](https://arxiv.org/abs/1706.03646)

##### PDF
[https://arxiv.org/pdf/1706.03646](https://arxiv.org/pdf/1706.03646)

