---
layout: post
title: "Towards Large-Pose Face Frontalization in the Wild"
date: 2017-08-17 18:12:07
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Deep_Learning Recognition Face_Recognition
author: Xi Yin, Xiang Yu, Kihyuk Sohn, Xiaoming Liu, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
Despite recent advances in face recognition using deep learning, severe accuracy drops are observed for large pose variations in unconstrained environments. Learning pose-invariant features is one solution, but needs expensively labeled large-scale data and carefully designed feature learning algorithms. In this work, we focus on frontalizing faces in the wild under various head poses, including extreme profile views. We propose a novel deep 3D Morphable Model (3DMM) conditioned Face Frontalization Generative Adversarial Network (GAN), termed as FF-GAN, to generate neutral head pose face images. Our framework differs from both traditional GANs and 3DMM based modeling. Incorporating 3DMM into the GAN structure provides shape and appearance priors for fast convergence with less training data, while also supporting end-to-end training. The 3DMM-conditioned GAN employs not only the discriminator and generator loss but also a new masked symmetry loss to retain visual quality under occlusions, besides an identity loss to recover high frequency information. Experiments on face recognition, landmark localization and 3D reconstruction consistently show the advantage of our frontalization method on faces in the wild datasets.

##### Abstract (translated by Google)
尽管最近在使用深度学习的人脸识别方面取得了进展，但是在无约束的环境中观察到大的姿态变化严重的精度下降。学习姿态不变特征是一个解决方案，但需要昂贵的标记大规模数据和精心设计的特征学习算法。在这项工作中，我们专注于在各种头部姿势下将野外的脸部正面化，包括极端的侧面视图。我们提出了一种新的深度3D形变模型（3DMM）条件人脸正面化生成敌对网络（GAN），被称为FF-GAN，以产生中立的头部姿态人脸图像。我们的框架不同于传统的GAN和基于3DMM的建模。将3DMM结合到GAN结构中提供了形状和外观先验，用于以较少的训练数据快速收敛，同时还支持端到端的训练。 3DMM条件下的GAN不仅使用鉴别器和发生器损失，而且还使用一个新的掩蔽对称损失来保持遮挡下的视觉质量，此外还有一个识别损失来恢复高频信息。在人脸识别，地标定位和三维重建上的实验一直证明了我们在野外数据集上的人脸识别方法的优势。

##### URL
[https://arxiv.org/abs/1704.06244](https://arxiv.org/abs/1704.06244)

##### PDF
[https://arxiv.org/pdf/1704.06244](https://arxiv.org/pdf/1704.06244)

