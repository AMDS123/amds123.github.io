---
layout: post
title: "Fast Segmentation of Left Ventricle in CT Images by Explicit Shape Regression using Random Pixel Difference Features"
date: 2015-07-28 14:07:05
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Peng Sun, Haoyin Zhou, Devon Lundine, James K. Min, Guanglei Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, machine learning has been successfully applied to model-based left ventricle (LV) segmentation. The general framework involves two stages, which starts with LV localization and is followed by boundary delineation. Both are driven by supervised learning techniques. When compared to previous non-learning-based methods, several advantages have been shown, including full automation and improved accuracy. However, the speed is still slow, in the order of several seconds, for applications involving a large number of cases or case loads requiring real-time performance. In this paper, we propose a fast LV segmentation algorithm by joint localization and boundary delineation via training explicit shape regressor with random pixel difference features. Tested on 3D cardiac computed tomography (CT) image volumes, the average running time of the proposed algorithm is 1.2 milliseconds per case. On a dataset consisting of 139 CT volumes, a 5-fold cross validation shows the segmentation error is $1.21 \pm 0.11$ for LV endocardium and $1.23 \pm 0.11$ millimeters for epicardium. Compared with previous work, the proposed method is more stable (lower standard deviation) without significant compromise to the accuracy.

##### Abstract (translated by Google)
最近，机器学习已经成功应用于基于模型的左心室（LV）分割。总体框架涉及两个阶段，从LV本地化开始，然后是边界划定。两者都是由监督学习技术驱动的。与以前的基于非学习的方法相比，已经显示了一些优势，包括全自动化和提高的准确性。然而，对于需要实时性能的大量案例或案例负载的应用来说，速度仍然是几秒钟的缓慢时间。在本文中，我们通过训练具有随机像素差异特征的显式形状回归器，提出了一种快速的低分割算法，通过联合定位和边界描述。对三维心脏计算机断层扫描（CT）图像体积进行测试，算法平均运行时间为1.2毫秒。在由139个CT体积组成的数据集上，5倍交叉验证显示LV心内膜的分割误差为1.21美元/分钟0.11美元，心外膜的分割误差为1.23美元/分钟0.11美元/毫米。与以前的工作相比，所提出的方法更加稳定（较低的标准偏差），而不会显着影响精度。

##### URL
[https://arxiv.org/abs/1507.07508](https://arxiv.org/abs/1507.07508)

##### PDF
[https://arxiv.org/pdf/1507.07508](https://arxiv.org/pdf/1507.07508)

