---
layout: post
title: "Online deforestation detection"
date: 2017-04-03 22:40:48
categories: arXiv_CV
tags: arXiv_CV Face Detection
author: Emiliano Diaz
mathjax: true
---

* content
{:toc}

##### Abstract
Deforestation detection using satellite images can make an important contribution to forest management. Current approaches can be broadly divided into those that compare two images taken at similar periods of the year and those that monitor changes by using multiple images taken during the growing season. The CMFDA algorithm described in Zhu et al. (2012) is an algorithm that builds on the latter category by implementing a year-long, continuous, time-series based approach to monitoring images. This algorithm was developed for 30m resolution, 16-day frequency reflectance data from the Landsat satellite. In this work we adapt the algorithm to 1km, 16-day frequency reflectance data from the modis sensor aboard the Terra satellite. The CMFDA algorithm is composed of two submodels which are fitted on a pixel-by-pixel basis. The first estimates the amount of surface reflectance as a function of the day of the year. The second estimates the occurrence of a deforestation event by comparing the last few predicted and real reflectance values. For this comparison, the reflectance observations for six different bands are first combined into a forest index. Real and predicted values of the forest index are then compared and high absolute differences for consecutive observation dates are flagged as deforestation events. Our adapted algorithm also uses the two model framework. However, since the modis 13A2 dataset used, includes reflectance data for different spectral bands than those included in the Landsat dataset, we cannot construct the forest index. Instead we propose two contrasting approaches: a multivariate and an index approach similar to that of CMFDA.

##### Abstract (translated by Google)
利用卫星图像进行森林砍伐检测可以对森林管理做出重要贡献。目前的方法大致可以分为比较一年中同一时期拍摄的两幅图像的那些方法，以及使用生长季节期间拍摄的多幅图像监测变化的方法。 Zhu等人描述的CMFDA算法（2012）是一种基于后一类别的算法，通过实施基于时间序列的连续一年的图像监控方法。该算法是针对Landsat卫星的30米分辨率，16天频率反射率数据而开发的。在这项工作中，我们使算法适应Terra卫星上的modis传感器的1km，16天频率反射率数据。 CMFDA算法由两个以逐个像素为基础拟合的子模型组成。第一个估计表面反射率的数量作为一年的一天的函数。第二个通过比较最后几个预测的和真实的反射率值来估计发生森林砍伐事件。为了进行比较，首先将六个不同波段的反射率观测数据合并为一个森林指数。然后比较森林指数的实际值和预测值，并将连续观测日期的高绝对差值标记为森林砍伐事件。我们改编的算法也使用了两个模型框架。然而，由于使用的13A2数据集包括不同于Landsat数据集中的光谱波段的反射率数据，我们不能构建森林指数。相反，我们提出了两种对比的方法：一种与CMFDA相似的多元和索引方法。

##### URL
[https://arxiv.org/abs/1704.00829](https://arxiv.org/abs/1704.00829)

##### PDF
[https://arxiv.org/pdf/1704.00829](https://arxiv.org/pdf/1704.00829)

