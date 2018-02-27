---
layout: post
title: "Multi-Evidence Filtering and Fusion for Multi-Label Classification, Object Detection and Semantic Segmentation Based on Weakly Supervised Learning"
date: 2018-02-26 02:07:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Weakly_Supervised Image_Classification Semantic_Segmentation Classification Prediction Detection Recognition
author: Weifeng Ge, Sibei Yang, Yizhou Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised object detection and semantic segmentation require object or even pixel level annotations. When there exist image level labels only, it is challenging for weakly supervised algorithms to achieve accurate predictions. The accuracy achieved by top weakly supervised algorithms is still significantly lower than their fully supervised counterparts. In this paper, we propose a novel weakly supervised curriculum learning pipeline for multi-label object recognition, detection and semantic segmentation. In this pipeline, we first obtain intermediate object localization and pixel labeling results for the training images, and then use such results to train task-specific deep networks in a fully supervised manner. The entire process consists of four stages, including object localization in the training images, filtering and fusing object instances, pixel labeling for the training images, and task-specific network training. To obtain clean object instances in the training images, we propose a novel algorithm for filtering, fusing and classifying object instances collected from multiple solution mechanisms. In this algorithm, we incorporate both metric learning and density-based clustering to filter detected object instances. Experiments show that our weakly supervised pipeline achieves state-of-the-art results in multi-label image classification as well as weakly supervised object detection and very competitive results in weakly supervised semantic segmentation on MS-COCO, PASCAL VOC 2007 and PASCAL VOC 2012.

##### Abstract (translated by Google)
监督对象检测和语义分割需要对象或甚至像素级别的注释。当仅存在图像级标签时，弱监督算法实现精确预测是具有挑战性的。顶级弱监督算法所实现的精度仍然明显低于完全监督的算法。在本文中，我们提出了一种用于多标签对象识别，检测和语义分割的弱监督课程学习管道。在这个流水线中，我们首先获得训练图像的中间对象定位和像素标记结果，然后使用这些结果以完全监督的方式训练任务特定的深度网络。整个过程包括四个阶段，包括训练图像中的对象定位，对象实例的过滤和融合，训练图像的像素标记以及特定于任务的网络训练。为了在训练图像中获得干净的对象实例，我们提出了一种用于过滤，融合和分类从多个解决方案机制收集的对象实例的新算法。在这个算法中，我们结合了度量学习和基于密度的聚类来过滤检测到的对象实例。实验表明，我们的弱监督流水线实现了多标签图像分类方面的最新成果，以及弱监督对象检测和MS-COCO，PASCAL VOC 2007和PASCAL VOC 2012的弱监督语义分割的非常有竞争力的结果。

##### URL
[http://arxiv.org/abs/1802.09129](http://arxiv.org/abs/1802.09129)

##### PDF
[http://arxiv.org/pdf/1802.09129](http://arxiv.org/pdf/1802.09129)

