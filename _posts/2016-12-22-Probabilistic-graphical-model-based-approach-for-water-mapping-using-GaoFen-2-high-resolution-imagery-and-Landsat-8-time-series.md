---
layout: post
title: "Probabilistic graphical model based approach for water mapping using GaoFen-2 high resolution imagery and Landsat 8 time series"
date: 2016-12-22 02:59:54
categories: arXiv_CV
tags: arXiv_CV Classification
author: Luyan Ji, Jie Wang, Xiurui Geng, Peng Gong
mathjax: true
---

* content
{:toc}

##### Abstract
The objective of this paper is to evaluate the potential of Gaofen-2 (GF-2) high resolution multispectral sensor (MS) and panchromatic (PAN) imagery on water mapping. Difficulties of water mapping on high resolution data includes: 1) misclassification between water and shadows or other low-reflectance ground objects, which is mostly caused by the spectral similarity within the given band range; 2) small water bodies with size smaller than the spatial resolution of MS image. To solve the confusion between water and low-reflectance objects, the Landsat 8 time series with two shortwave infrared (SWIR) bands is added because water has extremely strong absorption in SWIR. In order to integrate the three multi-sensor, multi-resolution data sets, the probabilistic graphical model (PGM) is utilized here with conditional probability distribution defined mainly based on the size of each object. For comparison, results from the SVM classifier on the PCA fused and MS data, thresholding method on the PAN image, and water index method on the Landsat data are computed. The confusion matrices are calculated for all the methods. The results demonstrate that the PGM method can achieve the best performance with the highest overall accuracy. Moreover, small rivers can also be extracted by adding weight on the PAN result in PGM. Finally, the post-classification procedure is applied on the PGM result to further exclude misclassification in shadow and water-land boundary regions. Accordingly, the producer's, user's and overall accuracy are all increased, indicating the effectiveness of our method.

##### Abstract (translated by Google)
本文的目的是评估高分2（GF-2）高分辨率多光谱传感器（MS）和全色（PAN）图像在水体测绘上的潜力。高分辨率数据水映射困难包括：1）水阴影或其他低反射率地物之间的错误分类，主要是由于给定谱带范围内的光谱相似性造成的; 2）尺寸小于MS图像的空间分辨率的小水体。为了解决水与低反射率物体之间的混淆，增加了两个短波红外（SWIR）波段的Landsat 8时间序列，因为水对SWIR有极强的吸收。为了集成三个多传感器，多分辨率的数据集，这里使用概率图模型（PGM），其中主要基于每个对象的大小来定义条件概率分布。为了进行比较，计算了PCA融合后的SVM分类器和MS数据的结果，PAN图像上的阈值化方法和Landsat数据上的水分指数法。计算所有方法的混淆矩阵。结果表明，PGM方法可以达到最高的整体精度。此外，小河流也可以通过在PGM上的PAN结果加权来提取。最后，对PGM结果应用后分类程序，进一步排除阴影和水陆边界区域的错误分类。相应地，生产者，用户和整体的准确性都提高了，说明了我们方法的有效性。

##### URL
[https://arxiv.org/abs/1612.07801](https://arxiv.org/abs/1612.07801)

##### PDF
[https://arxiv.org/pdf/1612.07801](https://arxiv.org/pdf/1612.07801)

