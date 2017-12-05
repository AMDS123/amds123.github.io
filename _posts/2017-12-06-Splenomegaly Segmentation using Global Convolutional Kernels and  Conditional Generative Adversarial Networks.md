---
layout: post
title: 'Splenomegaly Segmentation using Global Convolutional Kernels and  Conditional Generative Adversarial Networks'
date: 2017-12-06 00:53:25
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN CNN
author: Yuankai Huo, Zhoubing Xu, Shunxing Bao, Camilo Bermudez, Andrew J. Plassard, Jiaqi Liu, Yuang Yao, Albert Assad, Richard G. Abramson, Bennett A. Landman
---

* content
{:toc}

##### Abstract
Spleen volume estimation using automated image segmentation technique may be used to detect splenomegaly (abnormally enlarged spleen) on Magnetic Resonance Imaging (MRI) scans. In recent years, Deep Convolutional Neural Networks (DCNN) segmentation methods have demonstrated advantages for abdominal organ segmentation. However, variations in both size and shape of the spleen on MRI images may result in large false positive and false negative labeling when deploying DCNN based methods. In this paper, we propose the Splenomegaly Segmentation Network (SSNet) to address spatial variations when segmenting extraordinarily large spleens. SSNet was designed based on the framework of image-to-image conditional generative adversarial networks (cGAN). Specifically, the Global Convolutional Network (GCN) was used as the generator to reduce false negatives, while the Markovian discriminator (PatchGAN) was used to alleviate false positives. A cohort of clinically acquired 3D MRI scans (both T1 weighted and T2 weighted) from patients with splenomegaly were used to train and test the networks. The experimental results demonstrated that a mean Dice coefficient of 0.9260 and a median Dice coefficient of 0.9262 using SSNet on independently tested MRI volumes of patients with splenomegaly.

##### Abstract (translated by Google)
使用自动图像分割技术的脾脏体积估计可用于在磁共振成像（MRI）扫描中检测脾肿大（异常增大的脾脏）。近年来，深度卷积神经网络（DCNN）分割方法已经证明了腹部器官分割的优点。然而，在部署基于DCNN的方法时，MRI图像上的脾的大小和形状的变化可能导致大的假阳性和假阴性标记。在本文中，我们提出了脾脏分割网络（SSNet）来解决在分割非常大的脾脏时的空间变化。 SSNet是基于图像到图像条件生成对抗网络（cGAN）的框架设计的。具体而言，全球卷积网络（GCN）被用作发生器来减少漏报，而马尔可夫鉴别器（PatchGAN）被用来减轻误报。使用来自脾肿大患者的临床采集的三维MRI扫描队列（T1加权和T2加权）用于训练和测试网络。实验结果显示，在独立测试的脾肿大患者的MRI体积上，使用SSNet的平均Dice系数为0.9260，中位Dice系数为0.9262。

##### URL
[https://arxiv.org/abs/1712.00542](https://arxiv.org/abs/1712.00542)

