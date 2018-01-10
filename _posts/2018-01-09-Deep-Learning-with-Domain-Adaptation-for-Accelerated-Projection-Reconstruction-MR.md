---
layout: post
title: "Deep Learning with Domain Adaptation for Accelerated Projection-Reconstruction MR"
date: 2018-01-09 04:28:28
categories: arXiv_CV
tags: arXiv_CV GAN Deep_Learning
author: Yo Seob Han, Jaejun Yoo, Jong Chul Ye
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: The radial k-space trajectory is a well-established sampling trajectory used in conjunction with magnetic resonance imaging. However, the radial k-space trajectory requires a large number of radial lines for high-resolution reconstruction. Increasing the number of radial lines causes longer acquisition time, making it more difficult for routine clinical use. On the other hand, if we reduce the number of radial lines, streaking artifact patterns are unavoidable. To solve this problem, we propose a novel deep learning approach with domain adaptation to restore high-resolution MR images from under-sampled k-space data. 
 Methods: The proposed deep network removes the streaking artifacts from the artifact corrupted images. To address the situation given the limited available data, we propose a domain adaptation scheme that employs a pre-trained network using a large number of x-ray computed tomography (CT) or synthesized radial MR datasets, which is then fine-tuned with only a few radial MR datasets. 
 Results: The proposed method outperforms existing compressed sensing algorithms, such as the total variation and PR-FOCUSS methods. In addition, the calculation time is several orders of magnitude faster than the total variation and PR-FOCUSS methods.Moreover, we found that pre-training using CT or MR data from similar organ data is more important than pre-training using data from the same modality for different organ. 
 Conclusion: We demonstrate the possibility of a domain-adaptation when only a limited amount of MR data is available. The proposed method surpasses the existing compressed sensing algorithms in terms of the image quality and computation time.

##### Abstract (translated by Google)
目的：径向k空间轨迹是与磁共振成像结合使用的公认的采样轨迹。然而，径向k空间轨迹需要大量的径向线来进行高分辨率重建。增加径向线的数量会导致更长的采集时间，使得常规临床使用更加困难。另一方面，如果我们减少径向线的数量，裸奔伪影模式是不可避免的。为了解决这个问题，我们提出了一种新的深度学习方法的领域适应从欠采样的k空间数据恢复高分辨率的MR图像。
 方法：提出的深度网络从纹理损坏的图像中去除了条纹伪影。为了解决现有数据有限的情况，我们提出了一种领域适应方案，该方案使用大量的X射线计算机断层扫描（CT）或合成的径向MR数据集采用预先训练的网络，然后仅用微调一些径向MR数据集。
 结果：所提出的方法优于现有的压缩感知算法，如总变差和PR-FOCUSS方法。另外，计算时间比总变差和PR-FOCUSS方法快几个数量级。另外，我们发现使用来自类似器官数据的CT或MR数据的预训练比使用来自对于不同的器官也是一样的。
 结论：当只有有限的MR数据可用时，我们展示了域适应的可能性。所提出的方法在图像质量和计算时间方面优于现有的压缩感知算法。

##### URL
[http://arxiv.org/abs/1703.01135](http://arxiv.org/abs/1703.01135)

##### PDF
[http://arxiv.org/pdf/1703.01135](http://arxiv.org/pdf/1703.01135)

