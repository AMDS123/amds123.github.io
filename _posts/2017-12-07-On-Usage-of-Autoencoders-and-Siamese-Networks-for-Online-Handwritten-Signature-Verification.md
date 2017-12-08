---
layout: post
title: "On Usage of Autoencoders and Siamese Networks for Online Handwritten Signature Verification"
date: 2017-12-07 18:55:42
categories: arXiv_CV
tags: arXiv_CV
author: Kian Ahrabian, Bagher Babaali
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel writer-independent global feature extraction framework for the task of automatic signature verification which aims to make robust systems for automatically distinguishing negative and positive samples. Our method consists of an autoencoder for modeling the sample space into a fixed length latent space and a Siamese Network for classifying the fixed-length samples obtained from the autoencoder based on the reference samples of a subject as being "Genuine" or "Forged." We evaluated our proposed framework using SigWiComp2013 Japanese and GPDSsyntheticOnLineOffLineSignature dataset. On the SigWiComp2013 Japanese dataset, we achieved 8.65% EER that means 1.2% relative improvement compared to the best-reported result. Furthermore, on the GPDSsyntheticOnLineOffLineSignature dataset, we achieved average EERs of 0.13%, 0.12%, 0.21% and 0.25% respectively for 150, 300, 1000 and 2000 test subjects which indicates improvement of relative EER on the best-reported result by 95.67%, 95.26%, 92.9% and 91.52% respectively. Apart from the accuracy gain, because of the nature of our proposed framework which is based on neural networks and consequently is as simple as some consecutive matrix multiplications, it has less computational cost than conventional methods such as DTW and could be used concurrently on devices such as GPU, TPU, etc.

##### Abstract (translated by Google)
在本文中，我们针对自动签名验证的任务提出了一种独立于书写器的全局特征提取框架，其目标是使得用于自动区分负样本和正样本的鲁棒系统成为可能。我们的方法包括一个用于将样本空间建模成固定长度的潜在空间的自动编码器和一个连接网络，用于根据主题的参考样本将自动编码器获得的固定长度样本分类为“正版”或“伪造”。我们使用SigWiComp2013 Japanese和GPDSsyntheticOnLineOffLineSignature数据集评估了我们提出的框架。在SigWiComp2013日本数据集中，我们实现了8.65％的EER，相对于最佳报告结果，相对改善了1.2％。此外，在GPDS合成线上的在线签名数据集中，150,300,1000和2000个测试对象的平均EER分别为0.13％，0.12％，0.21％和0.25％，表明最佳报告结果的相对EER提高了95.67％分别为95.26％，92.9％和91.52％。除了准确性增益外，由于我们提出的基于神经网络的框架的性质，因此与一些连续的矩阵乘法一样简单，与传统方法如DTW相比具有更少的计算成本，并且可以同时用于设备如GPU，TPU等

##### URL
[http://arxiv.org/abs/1712.02781](http://arxiv.org/abs/1712.02781)

##### PDF
[http://arxiv.org/pdf/1712.02781](http://arxiv.org/pdf/1712.02781)

