---
layout: post
title: "Weakly Supervised Object Detection with Pointwise Mutual Information"
date: 2018-01-26 10:46:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Embedding CNN Classification Prediction Detection
author: Rene Grzeszick, Sebastian Sudholt, Gernot A. Fink
mathjax: true
---

* content
{:toc}

##### Abstract
In this work a novel approach for weakly supervised object detection that incorporates pointwise mutual information is presented. A fully convolutional neural network architecture is applied in which the network learns one filter per object class. The resulting feature map indicates the location of objects in an image, yielding an intuitive representation of a class activation map. While traditionally such networks are learned by a softmax or binary logistic regression (sigmoid cross-entropy loss), a learning approach based on a cosine loss is introduced. A pointwise mutual information layer is incorporated in the network in order to project predictions and ground truth presence labels in a non-categorical embedding space. Thus, the cosine loss can be employed in this non-categorical representation. Besides integrating image level annotations, it is shown how to integrate point-wise annotations using a Spatial Pyramid Pooling layer. The approach is evaluated on the VOC2012 dataset for classification, point localization and weakly supervised bounding box localization. It is shown that the combination of pointwise mutual information and a cosine loss eases the learning process and thus improves the accuracy. The integration of coarse point-wise localizations further improves the results at minimal annotation costs.

##### Abstract (translated by Google)
在这项工作中，提出了一个新的方法弱监督的对象检测，结合点互信息是介绍。一个完全卷积神经网络结构被应用，其中网络学习每个对象类别的一个过滤器。得到的特征图表示图像中对象的位置，产生类激活图的直观表示。传统上，通过softmax或二元logistic回归（sigmoid交叉熵损失）学习这种网络，引入基于余弦损失的学习方法。为了在非分类嵌入空间中投影预测和地面实况存在标签，在网络中并入一个逐点互信息层。因此，在这种非分类表示中可以采用余弦损失。除了集成图像级注释之外，还展示了如何使用Spatial Pyramid Pooling层集成逐点注释。该方法在VOC2012数据集上进行评估，用于分类，点定位和弱监督边界框定位。结果表明，逐点互信息和余弦损失相结合，简化了学习过程，提高了准确率。粗略的按点定位的集成以最小的注释成本进一步提高了结果。

##### URL
[http://arxiv.org/abs/1801.08747](http://arxiv.org/abs/1801.08747)

##### PDF
[http://arxiv.org/pdf/1801.08747](http://arxiv.org/pdf/1801.08747)

