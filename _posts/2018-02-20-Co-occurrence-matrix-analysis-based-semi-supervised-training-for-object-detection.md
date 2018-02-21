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
训练使用卷积神经网络（CNN）的对象识别网络中最重要的因素之一是提供带有人工判断的注释数据。特别地，在对象检测或语义分割中，注释过程需要相当大的人力。在本文中，我们提出了一种基于半监督学习（SSL）的对象检测训练方法，该方法利用先前从注释数据集训练过的网络对未注释数据进行自动标记。由于训练网络的推断标签取决于所学习的参数，因此重新训练网络通常没有意义。为了将有价值的推断标签转移给未标记的数据，我们提出了基于共现矩阵分析的重新对齐方法，该方法考虑了估计标签的单热矢量编码以及图像中对象之间的相关性。我们使用MS-COCO检测数据集来验证所提出的SSL方法和可变形神经网络（D-ConvNets）作为基础训练的对象检测器的性能。现有技术的探测器（DConvNets，YOLO v2和单发多盒探测器（SSD））的性能可以通过所提出的SSL方法来改进，而无需使用额外的模型参数或修改网络架构。

##### URL
[http://arxiv.org/abs/1802.06964](http://arxiv.org/abs/1802.06964)

##### PDF
[http://arxiv.org/pdf/1802.06964](http://arxiv.org/pdf/1802.06964)

