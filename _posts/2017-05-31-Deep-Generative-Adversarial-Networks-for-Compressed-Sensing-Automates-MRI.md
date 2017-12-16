---
layout: post
title: "Deep Generative Adversarial Networks for Compressed Sensing Automates MRI"
date: 2017-05-31 19:12:14
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN
author: Morteza Mardani, Enhao Gong, Joseph Y. Cheng, Shreyas Vasanawala, Greg Zaharchuk, Marcus Alley, Neil Thakur, Song Han, William Dally, John M. Pauly, Lei Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Magnetic resonance image (MRI) reconstruction is a severely ill-posed linear inverse task demanding time and resource intensive computations that can substantially trade off {\it accuracy} for {\it speed} in real-time imaging. In addition, state-of-the-art compressed sensing (CS) analytics are not cognizant of the image {\it diagnostic quality}. To cope with these challenges we put forth a novel CS framework that permeates benefits from generative adversarial networks (GAN) to train a (low-dimensional) manifold of diagnostic-quality MR images from historical patients. Leveraging a mixture of least-squares (LS) GANs and pixel-wise $\ell_1$ cost, a deep residual network with skip connections is trained as the generator that learns to remove the {\it aliasing} artifacts by projecting onto the manifold. LSGAN learns the texture details, while $\ell_1$ controls the high-frequency noise. A multilayer convolutional neural network is then jointly trained based on diagnostic quality images to discriminate the projection quality. The test phase performs feed-forward propagation over the generator network that demands a very low computational overhead. Extensive evaluations are performed on a large contrast-enhanced MR dataset of pediatric patients. In particular, images rated based on expert radiologists corroborate that GANCS retrieves high contrast images with detailed texture relative to conventional CS, and pixel-wise schemes. In addition, it offers reconstruction under a few milliseconds, two orders of magnitude faster than state-of-the-art CS-MRI schemes.

##### Abstract (translated by Google)
磁共振成像（MRI）重建是一种严重病态的线性逆向任务，要求时间和资源密集型计算，可以在实时成像中实质性地折衷{\ it}的速度。此外，最先进的压缩感知（CS）分析并不了解图像的诊断质量。为了应对这些挑战，我们提出了一种新型的CS框架，它渗透了生成对抗网络（GAN）的益处，以训练来自历史患者的（低维）多种诊断质量的MR图像。通过利用最小二乘（LS）GAN和像素成本的混合，将具有跳跃连接的深度残留网络作为发生器通过投影到流形上来学习去除混叠伪像。 LSGAN学习纹理细节，而$ \ ell_1 $控制高频噪音。然后基于诊断质量图像联合训练多层卷积神经网络以区分投影质量。测试阶段在发生器网络上执行前馈传播，这要求非常低的计算开销。对儿科患者的大对比增强MR数据集进行广泛的评估。具体而言，基于专家放射科医生评级的图像证实，GANCS相对于传统的CS和像素方案检索具有详细纹理的高对比度图像。此外，它在几毫秒内提供重建，比现有技术的CS-MRI方案快两个数量级。

##### URL
[https://arxiv.org/abs/1706.00051](https://arxiv.org/abs/1706.00051)

##### PDF
[https://arxiv.org/pdf/1706.00051](https://arxiv.org/pdf/1706.00051)

