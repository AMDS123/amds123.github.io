---
layout: post
title: "Deep Learning with Domain Adaptation for Accelerated Projection Reconstruction MR"
date: 2017-03-03 12:49:36
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Yo Seob Han, Jaejun Yoo, Jong Chul Ye
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: A radial k-space trajectory is one of well-established sampling trajectory in magnetic resonance imaging. However, the radial k-space trajectory requires a large number of radial lines for high-resolution reconstruction. Increasing the number of lines causes longer sampling times, making it more difficult for routine clinical use. If we reduce the radial lines to reduce the sampling time, streaking artifact patterns are unavoidable. To solve this problem, we propose a novel deep learning approach to reconstruct high-resolution MR images from the under-sampled k-space data. Methods: The proposed deep network estimates the streaking artifacts. Once the streaking artifacts are estimated, an artifact-free image is then obtained by subtracting the estimated streaking artifacts from the distorted image. In the case of the limited number of available radial acquisition data, we apply a domain adaptation scheme, which first pre-trains the network with a large number of x-ray computed tomography (CT) data sets and then fine-tunes it with only a few MR data sets. Results: The proposed deep learning method shows better performance than the existing compressed sensing algorithms, such as total variation and PR-FOCUSS. In addition, the calculation time is several order of magnitude faster than total variation and PR-FOCUSS methods. Conclusion: The proposed deep learning method surpasses the image quality as well as the computation times against the existing compressed sensing algorithms. In addition, we demonstrate the possibilities of domain-adaptation approach when a limited number of MR data is available.

##### Abstract (translated by Google)
目的：径向k-空间轨迹是磁共振成像中公认的采样轨迹之一。然而，径向k空间轨迹需要大量的径向线来进行高分辨率重建。增加线数会导致更长的采样时间，使得常规临床使用更加困难。如果我们减少径向线以减少采样时间，则条纹伪影模式是不可避免的。为了解决这个问题，我们提出了一种新的深度学习方法来从低采样的k空间数据重建高分辨率的MR图像。方法：拟议的深度网络估计裸奔伪影。一旦条纹伪影被估计，然后通过从畸变图像中减去估计的条纹伪影来获得无伪像的图像。在有限数量的可用径向采集数据的情况下，我们应用了一个域自适应方案，它首先用大量的X射线计算机断层扫描（CT）数据集预训练网络，然后仅用一些磁共振数据集。结果：提出的深度学习方法比现有的压缩感知算法，如总变差和PR-FOCUSS，表现出更好的性能。另外，计算时间比总变差和PR-FOCUSS方法快几个数量级。结论：针对现有的压缩感知算法，所提出的深度学习方法超过了图像质量以及计算时间。另外，当有限数量的MR数据可用时，我们展示了域适应方法的可能性。

##### URL
[https://arxiv.org/abs/1703.01135](https://arxiv.org/abs/1703.01135)

##### PDF
[https://arxiv.org/pdf/1703.01135](https://arxiv.org/pdf/1703.01135)

