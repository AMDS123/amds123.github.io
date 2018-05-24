---
layout: post
title: "SNIPER: Efficient Multi-Scale Training"
date: 2018-05-23 17:38:27
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Classification Detection Recognition
author: Bharat Singh, Mahyar Najibi, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
We present SNIPER, an algorithm for performing efficient multi-scale training in instance level visual recognition tasks. Instead of processing every pixel in an image pyramid, SNIPER processes context regions around ground-truth instances (referred to as chips) at the appropriate scale. For background sampling, these context-regions are generated using proposals extracted from a region proposal network trained with a short learning schedule. Hence, the number of chips generated per image during training adaptively changes based on the scene complexity. SNIPER only processes 30% more pixels compared to the commonly used single scale training at 800x1333 pixels on the COCO dataset. But, it also observes samples from extreme resolutions of the image pyramid, like 1400x2000 pixels. As SNIPER operates on resampled low resolution chips (512x512 pixels), it can have a batch size as large as 20 on a single GPU even with a ResNet-101 backbone. Therefore it can benefit from batch-normalization during training without the need for synchronizing batch-normalization statistics across GPUs. SNIPER brings training of instance level recognition tasks like object detection closer to the protocol for image classification and suggests that the commonly accepted guideline that it is important to train on high resolution images for instance level visual recognition tasks might not be correct. Our implementation based on Faster-RCNN with a ResNet-101 backbone obtains an mAP of 47.6% on the COCO dataset for bounding box detection and can process 5 images per second with a single GPU.

##### Abstract (translated by Google)
我们提出SNIPER，一种用于在实例级视觉识别任务中执行高效多尺度训练的算法。 SNIPER不是处理图像金字塔中的每个像素，而是以适当的比例处理地面真实情况（称为芯片）周围的上下文区域。对于背景抽样，这些上下文区域是使用从短期学习计划培训的区域提案网络提取的提案生成的。因此，训练期间每个图像产生的码片的数量基于场景复杂度自适应地改变。与COCO数据集上800x1333像素的常用单尺度训练相比，SNIPER只能处理多30％的像素。但是，它也观察来自图像金字塔的极端分辨率的样本，如1400x2000像素。由于SNIPER在重采样低分辨率芯片（512x512像素）上运行，即使使用ResNet-101主干，单个GPU上的批量大小也可能高达20。因此，它可以在培训期间从批处理标准化中受益，而无需同步跨GPU的批处理标准化统计。 SNIPER将实例级别识别任务（如对象检测）的训练带入图像分类协议更接近的地方，并建议普遍接受的指导方针是在高分辨率图像上训练实例级视觉识别任务，这一点很重要。我们基于带有ResNet-101骨干的Faster-RCNN的实现在COCO数据集上获得了47.6％的边界框检测mAP，并且每秒可以使用一个GPU处理5幅图像。

##### URL
[http://arxiv.org/abs/1805.09300](http://arxiv.org/abs/1805.09300)

##### PDF
[http://arxiv.org/pdf/1805.09300](http://arxiv.org/pdf/1805.09300)

