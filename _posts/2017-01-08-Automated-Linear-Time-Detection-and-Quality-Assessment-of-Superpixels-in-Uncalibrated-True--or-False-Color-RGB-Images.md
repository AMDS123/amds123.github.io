---
layout: post
title: "Automated Linear-Time Detection and Quality Assessment of Superpixels in Uncalibrated True- or False-Color RGB Images"
date: 2017-01-08 11:09:59
categories: arXiv_CV
tags: arXiv_CV QA Inference Quantitative Detection
author: Andrea Baraldi, Dirk Tiede, Stefan Lang
mathjax: true
---

* content
{:toc}

##### Abstract
Capable of automated near real time superpixel detection and quality assessment in an uncalibrated monitor typical red green blue (RGB) image, depicted in either true or false colors, an original low level computer vision (CV) lightweight computer program, called RGB Image Automatic Mapper (RGBIAM), is designed and implemented. Constrained by the Calibration Validation (CalVal) requirements of the Quality Assurance Framework for Earth Observation (QA4EO) guidelines, RGBIAM requires as mandatory an uncalibrated RGB image pre processing first stage, consisting of an automated statistical model based color constancy algorithm. The RGBIAM hybrid inference pipeline comprises: (I) a direct quantitative to nominal (QN) RGB variable transform, where RGB pixel values are mapped onto a prior dictionary of color names, equivalent to a static polyhedralization of the RGB cube. Prior color naming is the deductive counterpart of inductive vector quantization (VQ), whose typical VQ error function to minimize is a root mean square error (RMSE). In the output multi level color map domain, superpixels are automatically detected in linear time as connected sets of pixels featuring the same color label. (II) An inverse nominal to quantitative (NQ) RGB variable transform, where a superpixelwise constant RGB image approximation is generated in linear time to assess a VQ error image. The hybrid direct and inverse RGBIAM QNQ transform is: (i) general purpose, data and application independent. (ii) Automated, i.e., it requires no user machine interaction. (iii) Near real time, with a computational complexity increasing linearly with the image size. (iv) Implemented in tile streaming mode, to cope with massive images. Collected outcome and process quality indicators, including degree of automation, computational efficiency, VQ rate and VQ error, are consistent with theoretical expectations.

##### Abstract (translated by Google)
能够在未校准的监视器上实现近实时自动超像素检测和质量评估典型的红绿蓝（RGB）图像，以真或假颜色描绘，原始低级计算机视觉（CV）轻量级计算机程序，称为RGB图像自动映射器（RGBIAM）被设计和实现。由于受到地球观测质量保证框架（QA4EO）准则的校准验证（CalVal）要求的限制，RGBIAM要求第一阶段的未经校准的RGB图像预处理，包括基于自动统计模型的颜色恒常算法。 RGBIAM混合推理流水线包括：（I）直接量化到标称（QN）RGB变量变换，其中RGB像素值被映射到颜色名称的先前字典，相当于RGB立方体的静态多面体化。先前的颜色命名是归纳矢量量化（VQ）的演绎对应，其典型的VQ误差函数最小化是均方根误差（RMSE）。在输出的多级彩色地图域中，超线性像素以线性时间自动检测为具有相同颜色标签的连接的像素组。 （II）对于定量（NQ）RGB变量变换的反向标称，其中在线性时间内生成超像素恒定的RGB图像近似以评估VQ误差图像。混合直接和逆RGBIAM QNQ变换是：（i）通用，数据和应用程序无关的。 （ii）自动化的，即它不需要用户机器交互。 （iii）近实时，计算复杂度随着图像大小线性增加。 （iv）以瓦片流模式实施，以应对大量图像。收集的结果和过程质量指标，包括自动化程度，计算效率，VQ率和VQ误差，都符合理论预期。

##### URL
[https://arxiv.org/abs/1701.01940](https://arxiv.org/abs/1701.01940)

##### PDF
[https://arxiv.org/pdf/1701.01940](https://arxiv.org/pdf/1701.01940)

