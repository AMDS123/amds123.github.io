---
layout: post
title: "Texture Classification of MR Images of the Brain in ALS using CoHOG"
date: 2017-09-25 16:50:45
categories: arXiv_CV
tags: arXiv_CV Knowledge Classification
author: G M Mashrur E Elahi, Sanjay Kalra, Yee-Hong Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Texture analysis is a well-known research topic in computer vision and image processing and has many applications. Gradient-based texture methods have become popular in classification problems. For the first time we extend a well-known gradient-based method, Co-occurrence Histograms of Oriented Gradients (CoHOG) to extract texture features from 2D Magnetic Resonance Images (MRI). Unlike the original CoHOG method, we use the whole image instead of sub-regions for feature calculation. Also, we use a larger neighborhood size. Gradient orientations of the image pixels are calculated using Sobel, Gaussian Derivative (GD) and Local Frequency Descriptor Gradient (LFDG) operators. The extracted feature vector size is very large and classification using a large number of similar features does not provide the best results. In our proposed method, for the first time to our best knowledge, only a minimum number of significant features are selected using area under the receiver operator characteristic (ROC) curve (AUC) thresholds with <= 0.01. In this paper, we apply the proposed method to classify Amyotrophic Lateral Sclerosis (ALS) patients from the controls. It is observed that selected texture features from downsampled images are significantly different between patients and controls. These features are used in a linear support vector machine (SVM) classifier to determine the classification accuracy. Optimal sensitivity and specificity are also calculated. Three different cohort datasets are used in the experiments. The performance of the proposed method using three gradient operators and two different neighborhood sizes is analyzed. Region based analysis is performed to demonstrate that significant changes between patients and controls are limited to the motor cortex.

##### Abstract (translated by Google)
纹理分析是计算机视觉和图像处理领域的一个着名研究课题，具有很多应用价值。基于梯度的纹理方法在分类问题中变得流行。我们首次扩展了一个众所周知的基于梯度的方法，定向梯度共生直方图（CoHOGO）来从二维磁共振图像（MRI）中提取纹理特征。与原始CoHOG方法不同，我们使用整个图像而不是子区域进行特征计算。此外，我们使用较大的邻域大小。使用Sobel，高斯微分（GD）和局部频率描述符梯度（LFDG）算子来计算图像像素的梯度方向。提取的特征矢量的大小非常大，并且使用大量类似特征的分类不能提供最好的结果。在我们提出的方法中，第一次据我们所知，在受试者特征（ROC）曲线（AUC）阈值<0.01的情况下，仅使用面积来选择最小数目的显着特征。在本文中，我们运用所提出的方法对肌萎缩侧索硬化（ALS）患者进行分类。据观察，来自下采样图像的选定纹理特征在患者和对照之间显着不同。这些特征用于线性支持向量机（SVM）分类器中以确定分类准确性。还计算最佳灵敏度和特异性。实验中使用了三个不同的队列数据集。分析了利用三个梯度算子和两个不同邻域大小的方法的性能。进行基于区域的分析以证明患者和对照之间的显着变化仅限于运动皮质。

##### URL
[https://arxiv.org/abs/1703.02589](https://arxiv.org/abs/1703.02589)

##### PDF
[https://arxiv.org/e-print/1703.02589](https://arxiv.org/e-print/1703.02589)

