---
layout: post
title: "Face Detection with End-to-End Integration of a ConvNet and a 3D Model"
date: 2016-08-29 14:57:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Classification Detection Face_Detection
author: Yunzhu Li, Benyuan Sun, Tianfu Wu, Yizhou Wang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method for face detection in the wild, which integrates a ConvNet and a 3D mean face model in an end-to-end multi-task discriminative learning framework. The 3D mean face model is predefined and fixed (e.g., we used the one provided in the AFLW dataset). The ConvNet consists of two components: (i) The face pro- posal component computes face bounding box proposals via estimating facial key-points and the 3D transformation (rotation and translation) parameters for each predicted key-point w.r.t. the 3D mean face model. (ii) The face verification component computes detection results by prun- ing and refining proposals based on facial key-points based configuration pooling. The proposed method addresses two issues in adapting state- of-the-art generic object detection ConvNets (e.g., faster R-CNN) for face detection: (i) One is to eliminate the heuristic design of prede- fined anchor boxes in the region proposals network (RPN) by exploit- ing a 3D mean face model. (ii) The other is to replace the generic RoI (Region-of-Interest) pooling layer with a configuration pooling layer to respect underlying object structures. The multi-task loss consists of three terms: the classification Softmax loss and the location smooth l1 -losses [14] of both the facial key-points and the face bounding boxes. In ex- periments, our ConvNet is trained on the AFLW dataset only and tested on the FDDB benchmark with fine-tuning and on the AFW benchmark without fine-tuning. The proposed method obtains very competitive state-of-the-art performance in the two benchmarks.

##### Abstract (translated by Google)
本文提出了一种在野外进行人脸检测的方法，该方法在端到端的多任务判别式学习框架中集成了ConvNet和三维平均人脸模型。三维平均人脸模型是预定义的并且是固定的（例如，我们使用了在AFLW数据集中提供的模型）。 ConvNet由两部分组成：（i）面部提议部分通过估计面部关键点和每个预测关键点w.r.t的3D变换（旋转和平移）参数来计算面部边界框建议。三维平均人脸模型。 （ii）面部验证组件通过基于基于面部关键点的配置池来修剪和改进建议来计算检测结果。所提出的方法解决了在适应用于人脸检测的最先进的通用对象检测通信网络（例如更快的R-CNN）方面的两个问题：（i）一个是消除区域中的预定锚箱的启发式设计建议网络（RPN）通过利用三维平均人脸模型。 （ii）另一种方法是用配置池层替换通用的RoI（Region-of-Interest）池层来尊重基础对象结构。多任务丢失由三个项组成：分类Softmax损失和位置光滑l1损失[14]的面部关键点和面部边界框。在实验中，我们的ConvNet仅在AFLW数据集上进行了培训，并在FDDB基准测试中进行了微调和AFW基准测试，而无需进行微调。所提出的方法在两个基准中获得非常有竞争力的最新性能。

##### URL
[https://arxiv.org/abs/1606.00850](https://arxiv.org/abs/1606.00850)

##### PDF
[https://arxiv.org/pdf/1606.00850](https://arxiv.org/pdf/1606.00850)

