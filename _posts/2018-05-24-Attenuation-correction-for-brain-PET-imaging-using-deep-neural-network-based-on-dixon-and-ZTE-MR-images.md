---
layout: post
title: "Attenuation correction for brain PET imaging using deep neural network based on dixon and ZTE MR images"
date: 2018-05-24 20:19:24
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Kuang Gong, Jaewon Yang, Kyungsang Kim, Georges El Fakhri, Youngho Seo, Quanzheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
Positron Emission Tomography (PET) is a functional imaging modality widely used in neuroscience studies. To obtain meaningful quantitative results from PET images, attenuation correction is necessary during image reconstruction. For PET/MR hybrid systems, PET attenuation is challenging as Magnetic Resonance (MR) images do not reflect attenuation coefficients directly. To address this issue, we present deep neural network methods to derive the continuous attenuation coefficients for brain PET imaging from MR images. With only Dixon MR images as the network input, the existing U-net structure was adopted and analysis using forty patient data sets shows it is superior than other Dixon based methods. When both Dixon and zero echo time (ZTE) images are available, we have proposed a modified U-net structure, named GroupU-net, to efficiently make use of both Dixon and ZTE information through group convolution modules when the network goes deeper. Quantitative analysis based on fourteen real patient data sets demonstrates that both network approaches can perform better than the standard methods, and the proposed network structure can further reduce the PET quantification error compared to the U-net structure.

##### Abstract (translated by Google)
正电子发射断层扫描（PET）是一种广泛用于神经科学研究的功能成像模式。为了从PET图像中获得有意义的定量结果，在图像重建期间需要衰减校正。对于PET / MR混合系统，由于磁共振（MR）图像不能直接反映衰减系数，因此PET衰减具有挑战性。为了解决这个问题，我们提出了深度神经网络方法来从MR图像导出脑PET成像的连续衰减系数。只有Dixon MR图像作为网络输入，采用了现有的U-net结构，并且使用四十个患者数据集的分析显示其优于其他基于狄克逊的方法。当Dixon和零回波时间（ZTE）图像都可用时，我们提出了一种改进的U-net结构，名为GroupU-net，当网络更深时，通过组卷积模块有效利用Dixon和ZTE信息。基于14个真实患者数据集的定量分析表明，两种网络方法都可以比标准方法表现更好，并且与U网结构相比，所提出的网络结构可以进一步减少PET量化误差。

##### URL
[http://arxiv.org/abs/1712.06203](http://arxiv.org/abs/1712.06203)

##### PDF
[http://arxiv.org/pdf/1712.06203](http://arxiv.org/pdf/1712.06203)

