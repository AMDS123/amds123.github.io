---
layout: post
title: "CatGAN: Coupled Adversarial Transfer for Domain Generation"
date: 2017-11-24 09:34:53
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN
author: Shanshan Wang, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a Coupled adversarial transfer GAN (CatGAN), an efficient solution to domain alignment. The basic principles of CatGAN focus on the domain generation strategy for adaptation which is motivated by the generative adversarial net (GAN) and the adversarial discriminative domain adaptation (ADDA). CatGAN is structured by shallow multilayer perceptrons (MLPs) for adversarial domain adaptation. The CatGAN comprises of two slim and symmetric subnetworks, which then formulates a coupled adversarial learning framework. With such symmetry, the input images from source/target domain can be fed into the MLP network for target/source domain generation, supervised by the coupled discriminators for confrontation. Notablely, each generator contains GAN loss and domain loss to guarantee the simple network work well. The content fidelity term aims at preserving the domain specific knowledge during generation. Another finding is that the class-wise CatGAN is an effective alternative to conditional GAN without label constraint in generative learning. We show experimentally that the proposed model achieves competitive performance with state-of-the art approaches.

##### Abstract (translated by Google)
本文介绍了一种耦合对抗转移GAN（CatGAN），一种有效的域对齐解决方案。 CatGAN的基本原理集中在由生成对抗网（GAN）和敌对区分性域适应（ADDA）驱动的适应性域生成策略上。 CatGAN由浅层多层感知器（MLPs）构建，用于对抗领域适应。 CatGAN包含两个细长而对称的子网络，然后制定一个耦合的敌对学习框架。有了这样的对称性，来自源/目标域的输入图像可以被馈送到用于目标/源域生成的MLP网络中，由耦合的鉴别器进行监视以进行对抗。值得注意的是，每个发生器都包含GAN丢失和域损失，以保证简单的网络工作。内容保真度术语旨在保存在生成​​过程中的领域特定知识。另一个发现是，类生成CatGAN是有条件GAN的有效替代，在生成学习中没有标签约束。我们通过实验表明，所提出的模型通过最先进的方法实现了竞争性的表现。

##### URL
[https://arxiv.org/abs/1711.08904](https://arxiv.org/abs/1711.08904)

##### PDF
[https://arxiv.org/pdf/1711.08904](https://arxiv.org/pdf/1711.08904)

