---
layout: post
title: "Segmentation and Classification of Cine-MR Images Using Fully Convolutional Networks and Handcrafted Features"
date: 2017-09-11 07:54:23
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Relation
author: M. Hossein Eybposh, Mohammad Haghir Ebrahim-Abadi, Mohammad Jalilpour-Monesi, Seyed Saman Saboksayr
mathjax: true
---

* content
{:toc}

##### Abstract
Three-dimensional cine-MRI is of crucial importance for assessing the cardiac function. Features that describe the anatomy and function of cardiac structures (e.g. Left Ventricle (LV), Right Ventricle (RV), and Myocardium(MC)) are known to have significant diagnostic value and can be computed from 3D cine-MR images. However, these features require precise segmentation of cardiac structures. Among the fully automated segmentation methods, Fully Convolutional Networks (FCN) with Skip Connections have shown robustness in medical segmentation problems. In this study, we develop a complete pipeline for classification of subjects with cardiac conditions based on 3D cine-MRI. For the segmentation task, we develop a 2D FCN and introduce Parallel Paths (PP) as a way to exploit the 3D information of the cine-MR image. For the classification task, 125 features were extracted from the segmented structures, describing their anatomy and function. Next, a two-stage pipeline for feature selection using the LASSO method is developed. A subset of 20 features is selected for classification. Each subject is classified using an ensemble of Logistic Regression, Multi-Layer Perceptron, and Support Vector Machine classifiers through majority voting. The Dice Coefficient for segmentation was 0.95+-0.03, 0.89+-0.13, and 0.90+-0.03 for LV, RV, and MC respectively. The 8-fold cross validation accuracy for the classification task was 95.05% and 92.77% based on ground truth and the proposed methods segmentations respectively. The results show that the PPs increase the segmentation accuracy, by exploiting the spatial relations. Moreover, the classification algorithm and the features showed discriminability while keeping the sensitivity to segmentation error as low as possible.

##### Abstract (translated by Google)
三维电影MRI对评估心脏功能至关重要。描述心脏结构（例如左心室（LV），右心室（RV）和心肌（MC））的解剖学和功能的特征已知具有显着的诊断价值并且可以从3D电影MR图像计算。但是，这些功能需要精确分割心脏结构。在全自动分割方法中，具有跳过连接的全卷积网络（FCN）在医学分割问题中显示出鲁棒性。在这项研究中，我们开发了一个完整的基于3D电影MRI的心脏病分类流程。对于分割任务，我们开发了二维FCN并引入了并行路径（PP）作为利用电影MR图像三维信息的一种方法。对于分类任务，从分割结构中提取125个特征，描述它们的解剖结构和功能。接下来，开发了使用LASSO方法进行特征选择的两级流水线。选择20个特征的子集用于分类。通过多数投票，使用Logistic回归，多层感知器和支持向量机分类器的集合对每个主题进行分类。对于LV，RV和MC，分割的骰子系数分别为0.95±0.03,0.89±0.13和0.90±0.03。分类任务的8倍交叉验证准确率分别为95.05％和92.77％。结果表明，PPs通过利用空间关系提高了分割的准确性。此外，分类算法和特征表现出可辨性，同时尽可能保持对分割误差的敏感性。

##### URL
[https://arxiv.org/abs/1709.02565](https://arxiv.org/abs/1709.02565)

##### PDF
[https://arxiv.org/pdf/1709.02565](https://arxiv.org/pdf/1709.02565)

