---
layout: post
title: "Automatic segmentation of MR brain images with a convolutional neural network"
date: 2017-04-11 14:15:07
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Quantitative
author: Pim Moeskops, Max A. Viergever, Adriënne M. Mendrik, Linda S. de Vries, Manon J.N.L. Benders, Ivana Išgum
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic segmentation in MR brain images is important for quantitative analysis in large-scale studies with images acquired at all ages. This paper presents a method for the automatic segmentation of MR brain images into a number of tissue classes using a convolutional neural network. To ensure that the method obtains accurate segmentation details as well as spatial consistency, the network uses multiple patch sizes and multiple convolution kernel sizes to acquire multi-scale information about each voxel. The method is not dependent on explicit features, but learns to recognise the information that is important for the classification based on training data. The method requires a single anatomical MR image only. The segmentation method is applied to five different data sets: coronal T2-weighted images of preterm infants acquired at 30 weeks postmenstrual age (PMA) and 40 weeks PMA, axial T2- weighted images of preterm infants acquired at 40 weeks PMA, axial T1-weighted images of ageing adults acquired at an average age of 70 years, and T1-weighted images of young adults acquired at an average age of 23 years. The method obtained the following average Dice coefficients over all segmented tissue classes for each data set, respectively: 0.87, 0.82, 0.84, 0.86 and 0.91. The results demonstrate that the method obtains accurate segmentations in all five sets, and hence demonstrates its robustness to differences in age and acquisition protocol.

##### Abstract (translated by Google)
MR脑图像中的自动分割对于在所有年龄段获得的图像的大规模研究中的定量分析是重要的。本文提出了一种使用卷积神经网络将MR脑图像自动分割成许多组织类别的方法。为了保证该方法获得准确的分割细节和空间一致性，网络使用多个补丁大小和多个卷积核大小来获取关于每个体素的多尺度信息。该方法不依赖于显式特征，而是基于训练数据学习识别对于分类重要的信息。该方法仅需要单个解剖MR图像。该分割方法应用于五个不同的数据集：在30周龄（PMA）和40周PMA获得的早产儿的冠状面T2加权像，在40周PMA时获得的早产儿轴向T2加权像，轴向T1-平均年龄为70岁的老年人的加权图像以及平均年龄为23岁的年轻人的T1加权图像。该方法分别针对每个数据组获得了以下所有分割组织类别的平均Dice系数：0.87,0.82,0.84,0.86和0.91。结果表明，该方法在所有五组中均获得准确的分割，从而证明了其对年龄和采集协议差异的稳健性。

##### URL
[https://arxiv.org/abs/1704.03295](https://arxiv.org/abs/1704.03295)

##### PDF
[https://arxiv.org/pdf/1704.03295](https://arxiv.org/pdf/1704.03295)

