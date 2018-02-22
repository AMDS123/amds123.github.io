---
layout: post
title: "Multiclass Weighted Loss for Instance Segmentation of Cluttered Cells"
date: 2018-02-21 08:41:48
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Fidel A. Guerrero-Pena, Pedro D. Marrero Fernandez, Tsang Ing Ren, Mary Yui, Ellen Rothenberg, Alexandre Cunha
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new multiclass weighted loss function for instance segmentation of cluttered cells. We are primarily motivated by the need of developmental biologists to quantify and model the behavior of blood T-cells which might help us in understanding their regulation mechanisms and ultimately help researchers in their quest for developing an effective immuno-therapy cancer treatment. Segmenting individual touching cells in cluttered regions is challenging as the feature distribution on shared borders and cell foreground are similar thus difficulting discriminating pixels into proper classes. We present two novel weight maps applied to the weighted cross entropy loss function which take into account both class imbalance and cell geometry. Binary ground truth training data is augmented so the learning model can handle not only foreground and background but also a third touching class. This framework allows training using U-Net. Experiments with our formulations have shown superior results when compared to other similar schemes, outperforming binary class models with significant improvement of boundary adequacy and instance detection. We validate our results on manually annotated microscope images of T-cells.

##### Abstract (translated by Google)
我们提出了一种新的多类加权损失函数，用于对杂乱单元进行实例分割。我们的主要动机是发育生物学家需要量化和模拟血液T细胞的行为，这可能有助于我们理解其调节机制，并最终帮助研究人员寻求开发有效的免疫疗法癌症治疗。在混乱区域中分割单独的触摸单元是具有挑战性的，因为共享边界和单元前景上的特征分布相似，因此将区分像素划分为适当的类别。我们提出了两个新颖的权重图应用于加权交叉熵损失函数，其中考虑了类别不平衡和单元几何。二进制地面真实训练数据增加了，所以学习模型不仅可以处理前景和背景，还可以处理第三个触摸类。该框架允许使用U-Net进行培训。与其他类似方案相比，我们的配方实验显示出优异的结果，优于二元类模型，边界充分性和实例检测显着改善。我们验证了我们在T细胞手动注释的显微镜图像上的结果。

##### URL
[http://arxiv.org/abs/1802.07465](http://arxiv.org/abs/1802.07465)

##### PDF
[http://arxiv.org/pdf/1802.07465](http://arxiv.org/pdf/1802.07465)

