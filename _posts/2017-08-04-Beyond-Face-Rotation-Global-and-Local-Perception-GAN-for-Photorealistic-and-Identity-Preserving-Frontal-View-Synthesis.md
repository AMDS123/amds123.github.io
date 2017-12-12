---
layout: post
title: "Beyond Face Rotation: Global and Local Perception GAN for Photorealistic and Identity Preserving Frontal View Synthesis"
date: 2017-08-04 03:44:37
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Inference Deep_Learning Recognition Face_Recognition
author: Rui Huang, Shu Zhang, Tianyu Li, Ran He
mathjax: true
---

* content
{:toc}

##### Abstract
Photorealistic frontal view synthesis from a single face image has a wide range of applications in the field of face recognition. Although data-driven deep learning methods have been proposed to address this problem by seeking solutions from ample face data, this problem is still challenging because it is intrinsically ill-posed. This paper proposes a Two-Pathway Generative Adversarial Network (TP-GAN) for photorealistic frontal view synthesis by simultaneously perceiving global structures and local details. Four landmark located patch networks are proposed to attend to local textures in addition to the commonly used global encoder-decoder network. Except for the novel architecture, we make this ill-posed problem well constrained by introducing a combination of adversarial loss, symmetry loss and identity preserving loss. The combined loss function leverages both frontal face distribution and pre-trained discriminative deep face models to guide an identity preserving inference of frontal views from profiles. Different from previous deep learning methods that mainly rely on intermediate features for recognition, our method directly leverages the synthesized identity preserving image for downstream tasks like face recognition and attribution estimation. Experimental results demonstrate that our method not only presents compelling perceptual results but also outperforms state-of-the-art results on large pose face recognition.

##### Abstract (translated by Google)
从单人脸图像合成照片级正面视图，在人脸识别领域有着广泛的应用。虽然已经提出了数据驱动的深度学习方法来通过从充足的人脸数据寻求解决方案来解决这个问题，但是这个问题仍然是具有挑战性的，因为它本质上是不健康的。本文通过同时感知全局结构和局部细节，提出了一种双路径生成对抗网络（TP-GAN），用于逼真的正面视图合成。除了常用的全局编码器 - 解码器网络之外，还提出了四个具有地标的贴片网络来关注本地纹理。除了新颖的架构，我们通过引入对抗性损失，对称性损失和身份保持损失的组合来使这个不适定的问题受到很好的约束。联合损失函数利用正面人脸分布和预训练的区分深度人脸模型来指导人脸正面视图的身份保持推断。与以往主要依靠中间特征进行识别的深度学习方法不同，本方法直接利用合成的身份保持图像进行人脸识别和归因估计等下游任务。实验结果表明，我们的方法不仅提出了令人信服的感知结果，而且在大型姿态人脸识别上也超越了最先进的结果。

##### URL
[https://arxiv.org/abs/1704.04086](https://arxiv.org/abs/1704.04086)

##### PDF
[https://arxiv.org/pdf/1704.04086](https://arxiv.org/pdf/1704.04086)

