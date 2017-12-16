---
layout: post
title: "Weakly-supervised Learning of Mid-level Features for Pedestrian Attribute Recognition and Localization"
date: 2016-11-17 08:20:23
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Classification Detection Relation Recognition
author: Kai Yu, Biao Leng, Zhang Zhang, Dangwei Li, Kaiqi Huang
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art methods treat pedestrian attribute recognition as a multi-label image classification problem. The location information of person attributes is usually eliminated or simply encoded in the rigid splitting of whole body in previous work. In this paper, we formulate the task in a weakly-supervised attribute localization framework. Based on GoogLeNet, firstly, a set of mid-level attribute features are discovered by novelly designed detection layers, where a max-pooling based weakly-supervised object detection technique is used to train these layers with only image-level labels without the need of bounding box annotations of pedestrian attributes. Secondly, attribute labels are predicted by regression of the detection response magnitudes. Finally, the locations and rough shapes of pedestrian attributes can be inferred by performing clustering on a fusion of activation maps of the detection layers, where the fusion weights are estimated as the correlation strengths between each attribute and its relevant mid-level features. Extensive experiments are performed on the two currently largest pedestrian attribute datasets, i.e. the PETA dataset and the RAP dataset. Results show that the proposed method has achieved competitive performance on attribute recognition, compared to other state-of-the-art methods. Moreover, the results of attribute localization are visualized to understand the characteristics of the proposed method.

##### Abstract (translated by Google)
最先进的方法将行人属性识别视为多标签图像分类问题。在以前的工作中，人的属性的位置信息通常被消除或者简单地编码在全身的刚性分裂中。在本文中，我们制定了一个弱监督的属性定位框架的任务。基于GoogLeNet，首先通过新设计的检测层发现一组中间层次的属性特征，其中基于最大池的弱监督目标检测技术仅用图像层次的标签来训练这些层，而不需要行人属性的边界框注释。其次，通过检测响应量的回归来预测属性标签。最后，通过对检测层激活图的融合进行聚类，可以推断出行人属性的位置和粗糙形状，其中融合权重被估计为每个属性与其相关中间特征之间的相关强度。对当前最大的两个行人属性数据集（即，PETA数据集和RAP数据集）执行大量实验。结果表明，与其他一些最先进的方法相比，所提出的方法在属性识别方面已经取得了有竞争力的表现。此外，属性定位的结果被可视化以理解所提出的方法的特征。

##### URL
[https://arxiv.org/abs/1611.05603](https://arxiv.org/abs/1611.05603)

##### PDF
[https://arxiv.org/pdf/1611.05603](https://arxiv.org/pdf/1611.05603)

