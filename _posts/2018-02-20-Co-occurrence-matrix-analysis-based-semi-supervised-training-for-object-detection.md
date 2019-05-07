---
layout: post
title: "Co-occurrence matrix analysis-based semi-supervised training for object detection"
date: 2018-02-20 04:39:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Semantic_Segmentation Detection Relation Recognition
author: Min-Kook Choi, Jaehyeong Park, Jihun Jung, Heechul Jung, Jin-Hee Lee, Woong Jae Won, Woo Young Jung, Jincheol Kim, Soon Kwon
mathjax: true
---

* content
{:toc}

##### Abstract
One of the most important factors in training object recognition networks using convolutional neural networks (CNNs) is the provision of annotated data accompanying human judgment. Particularly, in object detection or semantic segmentation, the annotation process requires considerable human effort. In this paper, we propose a semi-supervised learning (SSL)-based training methodology for object detection, which makes use of automatic labeling of un-annotated data by applying a network previously trained from an annotated dataset. Because an inferred label by the trained network is dependent on the learned parameters, it is often meaningless for re-training the network. To transfer a valuable inferred label to the unlabeled data, we propose a re-alignment method based on co-occurrence matrix analysis that takes into account one-hot-vector encoding of the estimated label and the correlation between the objects in the image. We used an MS-COCO detection dataset to verify the performance of the proposed SSL method and deformable neural networks (D-ConvNets) as an object detector for basic training. The performance of the existing state-of-the-art detectors (DConvNets, YOLO v2, and single shot multi-box detector (SSD)) can be improved by the proposed SSL method without using the additional model parameter or modifying the network architecture.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.06964](https://arxiv.org/abs/1802.06964)

##### PDF
[https://arxiv.org/pdf/1802.06964](https://arxiv.org/pdf/1802.06964)

