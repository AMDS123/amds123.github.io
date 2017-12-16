---
layout: post
title: "Automatic segmentation of the intracranialvolume in fetal MR images"
date: 2017-07-31 14:44:38
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Quantitative
author: N. Khalili, P. Moeskops, N.H.P. Claessens, S. Scherpenzeel, E. Turk, R. de Heus, M.J.N.L. Benders, M.A. Viergever, J.P.W. Pluim, I. Išgum
mathjax: true
---

* content
{:toc}

##### Abstract
MR images of the fetus allow non-invasive analysis of the fetal brain. Quantitative analysis of fetal brain development requires automatic brain tissue segmentation that is typically preceded by segmentation of the intracranial volume (ICV). This is challenging because fetal MR images visualize the whole moving fetus and in addition partially visualize the maternal body. This paper presents an automatic method for segmentation of the ICV in fetal MR images. The method employs a multi-scale convolutional neural network in 2D slices to enable learning spatial information from larger context as well as detailed local information. The method is developed and evaluated with 30 fetal T2-weighted MRI scans (average age $33.2\pm1.2$ weeks postmenstrual age). The set contains $10$ scans acquired in axial, $10$ in coronal and $10$ in sagittal imaging planes. A reference standard was defined in all images by manual annotation of the intracranial volume in $10$ equidistantly distributed slices. The automatic analysis was performed by training and testing the network using scans acquired in the representative imaging plane as well as combining the training data from all imaging planes. On average, the automatic method achieved Dice coefficients of 0.90 for the axial images, 0.90 for the coronal images and 0.92 for the sagittal images. Combining the training sets resulted in average Dice coefficients of 0.91 for the axial images, 0.95 for the coronal images, and 0.92 for the sagittal images. The results demonstrate that the evaluated method achieved good performance in extracting ICV in fetal MR scans regardless of the imaging plane.

##### Abstract (translated by Google)
胎儿的MR图像允许胎儿脑的非侵入性分析。胎儿大脑发育的定量分析需要自动脑组织分割，通常在颅内容积（ICV）的分割之前。这是具有挑战性的，因为胎儿MR图像显现整个移动的胎儿并且另外部分地可视化母体。本文提出了一种自动分割ICV胎儿MR图像的方法。该方法在二维切片中使用多尺度卷积神经网络以使得能够从较大的上下文中学习空间信息以及详细的本地信息。该方法的开发和评估与胎儿的T2加权MRI扫描（平均年龄33.2 \ pm1.2月经后年龄）。该套件包含轴向获得的10美元扫描，冠状图像10美元和矢量成像飞机10美元。在所有图像中通过以10美元的等距分布切片手动标注颅内容积来定义参考标准。自动分析是通过使用在代表性成像平面中采集的扫描来训练和测试网络以及将来自所有成像平面的训练数据进行组合来执行的。平均而言，自动方法对于轴向图像实现了0.90的Dice系数，对于冠状图像实现了0.90的Dice系数，对于矢状图像实现了0.92的Dice系数。结合训练集导致轴向图像的平均Dice系数为0.91，冠状图像为0.95，矢状图像为0.92。结果表明，评估的方法取得了良好的性能提取ICV的胎儿磁共振扫描无论成像平面。

##### URL
[https://arxiv.org/abs/1708.02282](https://arxiv.org/abs/1708.02282)

##### PDF
[https://arxiv.org/pdf/1708.02282](https://arxiv.org/pdf/1708.02282)

