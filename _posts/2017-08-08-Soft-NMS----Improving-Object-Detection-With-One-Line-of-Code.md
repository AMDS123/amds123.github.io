---
layout: post
title: "Soft-NMS -- Improving Object Detection With One Line of Code"
date: 2017-08-08 17:49:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Navaneeth Bodla, Bharat Singh, Rama Chellappa, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
Non-maximum suppression is an integral part of the object detection pipeline. First, it sorts all detection boxes on the basis of their scores. The detection box M with the maximum score is selected and all other detection boxes with a significant overlap (using a pre-defined threshold) with M are suppressed. This process is recursively applied on the remaining boxes. As per the design of the algorithm, if an object lies within the predefined overlap threshold, it leads to a miss. To this end, we propose Soft-NMS, an algorithm which decays the detection scores of all other objects as a continuous function of their overlap with M. Hence, no object is eliminated in this process. Soft-NMS obtains consistent improvements for the coco-style mAP metric on standard datasets like PASCAL VOC 2007 (1.7% for both R-FCN and Faster-RCNN) and MS-COCO (1.3% for R-FCN and 1.1% for Faster-RCNN) by just changing the NMS algorithm without any additional hyper-parameters. Using Deformable-RFCN, Soft-NMS improves state-of-the-art in object detection from 39.8% to 40.9% with a single model. Further, the computational complexity of Soft-NMS is the same as traditional NMS and hence it can be efficiently implemented. Since Soft-NMS does not require any extra training and is simple to implement, it can be easily integrated into any object detection pipeline. Code for Soft-NMS is publicly available on GitHub (this http URL).

##### Abstract (translated by Google)
非最大抑制是对象检测流水线的一个组成部分。首先，根据分数排序所有检测框。选择具有最大分数的检测框M，并且抑制与M具有显着重叠（使用预定阈值）的所有其他检测框。这个过程被递归地应用在其余的盒子上。按照算法的设计，如果一个对象位于预定义的重叠阈值内，就会导致错过。为此，我们提出Soft-NMS算法，该算法将所有其他对象的检测分数衰减为与M重叠的连续函数。因此，在这个过程中没有任何对象被消除。软NMS获得用于在标准数据集等PASCAL VOC 2007椰油样式映射度量（1.7％两种R-FCN和更快-RCNN）和MS-COCO（1.3％的R-FCN和Faster- 1.1％一致的改进RCNN），只需更改NMS算法，不需要任何额外的超参数。使用Deformable-RFCN，Soft-NMS使用单一模型将对象检测的最新技术从39.8％提高到了40.9％。此外，Soft-NMS的计算复杂度与传统的NMS相同，因此可以有效实施。由于Soft-NMS不需要额外的培训，而且易于实施，因此可以轻松地将其集成到任何物体检测管道中。 Soft-NMS的代码在GitHub（这个http URL）上公开发布。

##### URL
[https://arxiv.org/abs/1704.04503](https://arxiv.org/abs/1704.04503)

##### PDF
[https://arxiv.org/pdf/1704.04503](https://arxiv.org/pdf/1704.04503)

