---
layout: post
title: "Retinal Vessel Segmentation Based on Conditional Deep Convolutional Generative Adversarial Networks"
date: 2018-05-11 02:17:04
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN CNN
author: Yun Jiang, Ning Tan
mathjax: true
---

* content
{:toc}

##### Abstract
The segmentation of retinal vessels is of significance for doctors to diagnose the fundus diseases. However, existing methods have various problems in the segmentation of the retinal vessels, such as insufficient segmentation of retinal vessels, weak anti-noise interference ability, and sensitivity to lesions, etc. Aiming to the shortcomings of existed methods, this paper proposes the use of conditional deep convolutional generative adversarial networks to segment the retinal vessels. We mainly improve the network structure of the generator. The introduction of the residual module at the convolutional layer for residual learning makes the network structure sensitive to changes in the output, as to better adjust the weight of the generator. In order to reduce the number of parameters and calculations, using a small convolution to halve the number of channels in the input signature before using a large convolution kernel. By used skip connection to connect the output of the convolutional layer with the output of the deconvolution layer to avoid low-level information sharing. By verifying the method on the DRIVE and STARE datasets, the segmentation accuracy rate is 96.08% and 97.71%, the sensitivity reaches 82.74% and 85.34% respectively, and the F-measure reaches 82.08% and 85.02% respectively. The sensitivity is 4.82% and 2.4% higher than that of R2U-Net.

##### Abstract (translated by Google)
视网膜血管的分割对于医生诊断眼底疾病具有重要意义。然而，现有方法在视网膜血管分割中存在着视网膜血管分割不足，抗噪声干扰能力弱，对病变敏感等问题。针对现有方法存在的不足，本文提出使用有条件的深度卷积生成对抗网络来分割视网膜血管。我们主要改进发电机的网络结构。在卷积层引入剩余模块进行残留学习，使网络结构对输出变化敏感，从而更好地调整发生器的重量。为了减少参数和计算次数，在使用大型卷积核之前，使用小卷积将输入签名中的通道数减半。通过使用跳过连接将卷积层的输出与解卷积层的输出连接起来，以避免低层次的信息共享。通过对DRIVE和STARE数据集上的方法进行验证，分割准确率分别为96.08％和97.71％，灵敏度分别达到82.74％和85.34％，F值分别达到82.08％和85.02％。灵敏度比R2U-Net高4.82％和2.4％。

##### URL
[http://arxiv.org/abs/1805.04224](http://arxiv.org/abs/1805.04224)

##### PDF
[http://arxiv.org/pdf/1805.04224](http://arxiv.org/pdf/1805.04224)

