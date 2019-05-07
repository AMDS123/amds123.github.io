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


##### URL
[https://arxiv.org/abs/1704.04503](https://arxiv.org/abs/1704.04503)

##### PDF
[https://arxiv.org/pdf/1704.04503](https://arxiv.org/pdf/1704.04503)

