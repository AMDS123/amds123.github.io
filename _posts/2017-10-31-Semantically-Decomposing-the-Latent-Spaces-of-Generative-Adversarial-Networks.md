---
layout: post
title: "Semantically Decomposing the Latent Spaces of Generative Adversarial Networks"
date: 2017-10-31 18:00:05
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face
author: Chris Donahue, Zachary C. Lipton, Akshay Balsubramani, Julian McAuley
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new algorithm for training generative adversarial networks that jointly learns latent codes for both identities (e.g. individual humans) and observations (e.g. specific photographs). By fixing the identity portion of the latent codes, we can generate diverse images of the same subject, and by fixing the observation portion, we can traverse the manifold of subjects while maintaining contingent aspects such as lighting and pose. Our algorithm features a pairwise training scheme in which each sample from the generator consists of two images with a common identity code. Corresponding samples from the real dataset consist of two distinct photographs of the same subject. In order to fool the discriminator, the generator must produce pairs that are photorealistic, distinct, and appear to depict the same individual. We augment both the DCGAN and BEGAN approaches with Siamese discriminators to facilitate pairwise training. Experiments with human judges and an off-the-shelf face verification system demonstrate our algorithm's ability to generate convincing, identity-matched photographs.

##### Abstract (translated by Google)
我们提出了一种新的训练生成对抗网络的算法，它们共同学习身份（例如个人）和观察（例如特定照片）的潜在代码。通过固定潜在代码的同一性部分，我们可以生成同一主题的不同图像，通过固定观察部分，我们可以在维持诸如照明和姿势等特殊方面的情况下遍历主体的多样性。我们的算法具有成对训练方案，其中来自发生器的每个样本由具有共同身份代码的两个图像组成。来自真实数据集的相应样本由相同主题的两张截然不同的照片组成。为了欺骗鉴别者，发生器必须产生真实的，不同的，并且似乎描绘同一个人的对。我们用连体鉴别器来增强DCGAN和BEGAN方法，以便于成对训练。使用人工判断和现成的人脸验证系统的实验证明了我们的算法能够生成令人信服的，身份匹配的照片。

##### URL
[https://arxiv.org/abs/1705.07904](https://arxiv.org/abs/1705.07904)

##### PDF
[https://arxiv.org/pdf/1705.07904](https://arxiv.org/pdf/1705.07904)

