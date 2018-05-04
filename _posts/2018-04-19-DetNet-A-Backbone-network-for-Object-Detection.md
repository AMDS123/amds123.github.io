---
layout: post
title: "DetNet: A Backbone network for Object Detection"
date: 2018-04-19 06:36:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Image_Classification Classification Detection
author: Zeming Li, Chao Peng, Gang Yu, Xiangyu Zhang, Yangdong Deng, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Recent CNN based object detectors, no matter one-stage methods like YOLO, SSD, and RetinaNe or two-stage detectors like Faster R-CNN, R-FCN and FPN are usually trying to directly finetune from ImageNet pre-trained models designed for image classification. There has been little work discussing on the backbone feature extractor specifically designed for the object detection. More importantly, there are several differences between the tasks of image classification and object detection. 1. Recent object detectors like FPN and RetinaNet usually involve extra stages against the task of image classification to handle the objects with various scales. 2. Object detection not only needs to recognize the category of the object instances but also spatially locate the position. Large downsampling factor brings large valid receptive field, which is good for image classification but compromises the object location ability. Due to the gap between the image classification and object detection, we propose DetNet in this paper, which is a novel backbone network specifically designed for object detection. Moreover, DetNet includes the extra stages against traditional backbone network for image classification, while maintains high spatial resolution in deeper layers. Without any bells and whistles, state-of-the-art results have been obtained for both object detection and instance segmentation on the MSCOCO benchmark based on our DetNet~(4.8G FLOPs) backbone. The code will be released for the reproduction.

##### Abstract (translated by Google)
无论是像YOLO，SSD和RetinaNe这样的一阶段方法，还是像R-CNN，R-FCN和FPN这样的两阶段检测器，最近基于CNN的物体检测器通常都试图从ImageNet预先训练好的模型分类。关于专门设计用于物体检测的主干特征提取器的讨论很少。更重要的是，图像分类和对象检测任务之间存在若干差异。 1.最近的像FPN和RetinaNet这样的对象检测器通常需要额外的阶段来处理图像分类的任务，以处理各种尺度的对象。 2.对象检测不仅需要识别对象实例的类别，还要在空间上定位位置。大的下采样因子带来了大量有效的接受场，这对于图像分类是有利的，但是降低了对象定位能力。由于图像分类与对象检测之间存在差距，本文提出了DetNet，它是专门为物体检测设计的新型骨干网络。此外，DetNet包含了针对传统骨干网络进行图像分类的额外阶段，同时在较深层次中保持高空间分辨率。在没有任何花招的情况下，基于我们的DetNet〜（4.8G FLOPs）主干，MSCOCO基准测试中的对象检测和实例分割都获得了最新的结果。该代码将被发布用于复制。

##### URL
[https://arxiv.org/abs/1804.06215](https://arxiv.org/abs/1804.06215)

##### PDF
[https://arxiv.org/pdf/1804.06215](https://arxiv.org/pdf/1804.06215)

