---
layout: post
title: "Freehand Ultrasound Image Simulation with Spatially-Conditioned Generative Adversarial Networks"
date: 2017-07-17 20:48:28
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Yipeng Hu, Eli Gibson, Li-Lin Lee, Weidi Xie, Dean C. Barratt, Tom Vercauteren, J. Alison Noble
mathjax: true
---

* content
{:toc}

##### Abstract
Sonography synthesis has a wide range of applications, including medical procedure simulation, clinical training and multimodality image registration. In this paper, we propose a machine learning approach to simulate ultrasound images at given 3D spatial locations (relative to the patient anatomy), based on conditional generative adversarial networks (GANs). In particular, we introduce a novel neural network architecture that can sample anatomically accurate images conditionally on spatial position of the (real or mock) freehand ultrasound probe. To ensure an effective and efficient spatial information assimilation, the proposed spatially-conditioned GANs take calibrated pixel coordinates in global physical space as conditioning input, and utilise residual network units and shortcuts of conditioning data in the GANs' discriminator and generator, respectively. Using optically tracked B-mode ultrasound images, acquired by an experienced sonographer on a fetus phantom, we demonstrate the feasibility of the proposed method by two sets of quantitative results: distances were calculated between corresponding anatomical landmarks identified in the held-out ultrasound images and the simulated data at the same locations unseen to the networks; a usability study was carried out to distinguish the simulated data from the real images. In summary, we present what we believe are state-of-the-art visually realistic ultrasound images, simulated by the proposed GAN architecture that is stable to train and capable of generating plausibly diverse image samples.

##### Abstract (translated by Google)
超声合成具有广泛的应用，包括医疗程序模拟，临床培训和多模态图像配准。在本文中，我们提出了一种机器学习方法，在给定的三维空间位置（相对于病人解剖结构）基于条件生成对抗网络（GAN）模拟超声图像。特别是，我们引入了一种新的神经网络架构，可以在（真实或模拟）徒手超声探头的空间位置上有条件地对解剖学上精确的图像进行采样。为了保证有效的空间信息同化，所提出的空间调节GAN将全局物理空间中的校准像素坐标作为调节输入，并分别在GAN的鉴别器和发生器中利用剩余网络单元和调节数据的快捷方式。使用由有经验的超声医师在胎儿体模上采集的光学跟踪B型超声图像，我们通过两组定量结果来证明所提出的方法的可行性：计算出在所保持的超声图像中识别的相应解剖标志与在相同位置的模拟数据不可见于网络;进行可用性研究以区分模拟数据与真实图像。总之，我们提出了我们认为是最先进的视觉逼真的超声图像，由建议的GAN架构模拟，是稳定的训练和能够产生振振有别的图像样本。

##### URL
[https://arxiv.org/abs/1707.05392](https://arxiv.org/abs/1707.05392)

##### PDF
[https://arxiv.org/pdf/1707.05392](https://arxiv.org/pdf/1707.05392)

