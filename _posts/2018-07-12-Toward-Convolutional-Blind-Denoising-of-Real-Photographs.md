---
layout: post
title: "Toward Convolutional Blind Denoising of Real Photographs"
date: 2018-07-12 15:52:17
categories: arXiv_CV
tags: arXiv_CV CNN Quantitative
author: Shi Guo, Zifei Yan, Kai Zhang, Wangmeng Zuo, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Despite their success in Gaussian denoising, deep convolutional neural networks (CNNs) are still very limited on real noisy photographs, and may even perform worse than the representative traditional methods such as BM3D and K-SVD. In order to improve the robustness and practicability of deep denoising models, this paper presents a convolutional blind denoising network (CBDNet) by incorporating network architecture, noise modeling, and asymmetric learning. Our CBDNet is comprised of a noise estimation subnetwork and a denoising subnetwork, and is trained using a more realistic noise model by considering both signal-dependent noise and in-camera processing pipeline. Motivated by the asymmetric sensitivity of non-blind denoisers (e.g., BM3D) to noise estimation error, the asymmetric learning is presented on the noise estimation subnetwork to suppress more on under-estimation of noise level. To make the learned model applicable to real photographs, both synthetic images based on realistic noise model and real noisy photographs with nearly noise-free images are incorporated to train our CBDNet. The results on three datasets of real noisy photographs clearly demonstrate the superiority of our CBDNet over the state-of-the-art denoisers in terms of quantitative metrics and visual quality. The code and models will be publicly available at https://github.com/GuoShi28/CBDNet.

##### Abstract (translated by Google)
尽管它们在高斯去噪方面取得了成功，但深度卷积神经网络（CNN）仍然在真实噪声照片上非常有限，甚至可能比BM3D和K-SVD等代表性的传统方法表现更差。为了提高深度去噪模型的鲁棒性和实用性，本文提出了一种卷积盲去噪网络（CBDNet），它结合了网络架构，噪声建模和非对称学习。我们的CBDNet由噪声估计子网和去噪子网组成，并通过考虑信号相关噪声和相机内处理流水线，使用更逼真的噪声模型进行训练。受非盲消音器（例如BM3D）对噪声估计误差的不对称灵敏度的影响，在噪声估计子网上呈现非对称学习以抑制噪声水平的低估。为了使学习的模型适用于真实照片，基于真实噪声模型的合成图像和具有几乎无噪声图像的真实噪声照片被合并以训练我们的CBDNet。真实嘈杂照片的三个数据集的结果清楚地证明了我们的CBDNet在定量指标和视觉质量方面优于现有技术的降噪器。代码和模型将在https://github.com/GuoShi28/CBDNet上公开。

##### URL
[http://arxiv.org/abs/1807.04686](http://arxiv.org/abs/1807.04686)

##### PDF
[http://arxiv.org/pdf/1807.04686](http://arxiv.org/pdf/1807.04686)

