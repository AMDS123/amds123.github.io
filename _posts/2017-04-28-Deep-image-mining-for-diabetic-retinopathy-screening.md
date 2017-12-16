---
layout: post
title: "Deep image mining for diabetic retinopathy screening"
date: 2017-04-28 07:57:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Segmentation Classification Deep_Learning Prediction Detection
author: Gwenolé Quellec, Katia Charrière, Yassine Boudi, Béatrice Cochener, Mathieu Lamard
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning is quickly becoming the leading methodology for medical image analysis. Given a large medical archive, where each image is associated with a diagnosis, efficient pathology detectors or classifiers can be trained with virtually no expert knowledge about the target pathologies. However, deep learning algorithms, including the popular ConvNets, are black boxes: little is known about the local patterns analyzed by ConvNets to make a decision at the image level. A solution is proposed in this paper to create heatmaps showing which pixels in images play a role in the image-level predictions. In other words, a ConvNet trained for image-level classification can be used to detect lesions as well. A generalization of the backpropagation method is proposed in order to train ConvNets that produce high-quality heatmaps. The proposed solution is applied to diabetic retinopathy (DR) screening in a dataset of almost 90,000 fundus photographs from the 2015 Kaggle Diabetic Retinopathy competition and a private dataset of almost 110,000 photographs (e-ophtha). For the task of detecting referable DR, very good detection performance was achieved: $A_z = 0.954$ in Kaggle's dataset and $A_z = 0.949$ in e-ophtha. Performance was also evaluated at the image level and at the lesion level in the DiaretDB1 dataset, where four types of lesions are manually segmented: microaneurysms, hemorrhages, exudates and cotton-wool spots. The proposed detector outperforms recent algorithms trained to detect those lesions specifically, as well as competing heatmap generation algorithms for ConvNets. This detector is part of the Messidor system for mobile eye pathology screening. Because it does not rely on expert knowledge or manual segmentation for detecting relevant patterns, the proposed solution is a promising image mining tool, which has the potential to discover new biomarkers in images.

##### Abstract (translated by Google)
深度学习正在迅速成为医学图像分析的领先方法。给定一个大的医疗档案，其中每个图像与诊断相关联，有效的病理学检测器或分类器可以训练，实际上没有关于目标病理的专业知识。然而，包括流行的ConvNets在内的深度学习算法是黑盒子，对于ConvNets在图像层面做出决策分析的局部模式知之甚少。本文提出了一种解决方案来创建热图，显示图像中哪些像素在图像级预测中发挥作用。换句话说，为图像级分类训练的ConvNet也可用于检测病变。为了训练产生高质量热图的ConvNets，提出了反向传播方法的推广。所提出的解决方案被应用于来自2015年Kaggle糖尿病视网膜病变竞赛的近9万张眼底照片和近110,000张照片（e-ophtha）的私人数据集的糖尿病视网膜病变（DR）筛选。为了检测可参考的DR，检测性能非常好：Kaggle数据集$ A_z = 0.954 $，e-ophtha $ A_z = 0.949 $。还在DiaretDB1数据集的图像水平和病变水平评估了性能，其中四种类型的病变是手动分割的：微动脉瘤，出血，渗出物和棉花斑点。所提出的检测器优于近期经过训练的检测这些病变的算法，以及针对ConvNets的竞争性热图生成算法。该检测器是Messidor系统的一部分，用于移动眼病理检查。因为它不依赖于专家知识或手动分割来检测相关图案，所提出的解决方案是有前途的图像挖掘工具，其具有发现图像中新的生物标志物的潜力。

##### URL
[https://arxiv.org/abs/1610.07086](https://arxiv.org/abs/1610.07086)

##### PDF
[https://arxiv.org/pdf/1610.07086](https://arxiv.org/pdf/1610.07086)

