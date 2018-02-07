---
layout: post
title: "Compressive Light Field Reconstructions using Deep Learning"
date: 2018-02-05 23:00:47
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Mayank Gupta, Arjun Jauhari, Kuldeep Kulkarni, Suren Jayasuriya, Alyosha Molnar, Pavan Turaga
mathjax: true
---

* content
{:toc}

##### Abstract
Light field imaging is limited in its computational processing demands of high sampling for both spatial and angular dimensions. Single-shot light field cameras sacrifice spatial resolution to sample angular viewpoints, typically by multiplexing incoming rays onto a 2D sensor array. While this resolution can be recovered using compressive sensing, these iterative solutions are slow in processing a light field. We present a deep learning approach using a new, two branch network architecture, consisting jointly of an autoencoder and a 4D CNN, to recover a high resolution 4D light field from a single coded 2D image. This network decreases reconstruction time significantly while achieving average PSNR values of 26-32 dB on a variety of light fields. In particular, reconstruction time is decreased from 35 minutes to 6.7 minutes as compared to the dictionary method for equivalent visual quality. These reconstructions are performed at small sampling/compression ratios as low as 8%, allowing for cheaper coded light field cameras. We test our network reconstructions on synthetic light fields, simulated coded measurements of real light fields captured from a Lytro Illum camera, and real coded images from a custom CMOS diffractive light field camera. The combination of compressive light field capture with deep learning allows the potential for real-time light field video acquisition systems in the future.

##### Abstract (translated by Google)
对于空间和角度尺寸的高采样，光场成像的计算处理要求是有限的。单发光场相机通常通过将进入的光线多路复用到2D传感器阵列上来牺牲空间分辨率来对角视点进行取样。虽然这个分辨率可以使用压缩感测来恢复，但是这些迭代解决方案在处理光场时是缓慢的。我们提出了一个深度的学习方法，使用一个新的，两个分支网络架构，由一个自动编码器和一个4D CNN共同组成，从一个编码的二维图像恢复一个高分辨率的4D光场。该网络显着减少重建时间，同时在各种光场上获得26-32dB的平均PSNR值。特别是与同等视觉质量的字典方法相比，重建时间从35分钟减少到6.7分钟。这些重建是以低至8％的小采样/压缩比执行的，允许使用更便宜的编码的光场相机。我们测试合成光场的网络重建，从Lytro Illum摄像机捕获的真实光场的模拟编码测量，以及来自定制CMOS衍射光场相机的实际编码图像。压缩光场捕获与深度学习的结合使得未来实时光场视频采集系统成为可能。

##### URL
[http://arxiv.org/abs/1802.01722](http://arxiv.org/abs/1802.01722)

##### PDF
[http://arxiv.org/pdf/1802.01722](http://arxiv.org/pdf/1802.01722)

