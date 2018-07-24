---
layout: post
title: "SiGAN: Siamese Generative Adversarial Network for Identity-Preserving Face Hallucination"
date: 2018-07-22 21:18:38
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Recognition
author: Chih-Chung Hsu, Chia-Wen Lin, Weng-Tai Su, Gene Cheung
mathjax: true
---

* content
{:toc}

##### Abstract
Despite generative adversarial networks (GANs) can hallucinate photo-realistic high-resolution (HR) faces from low-resolution (LR) faces, they cannot guarantee preserving the identities of hallucinated HR faces, making the HR faces poorly recognizable. To address this problem, we propose a Siamese GAN (SiGAN) to reconstruct HR faces that visually resemble their corresponding identities. On top of a Siamese network, the proposed SiGAN consists of a pair of two identical generators and one discriminator. We incorporate reconstruction error and identity label information in the loss function of SiGAN in a pairwise manner. By iteratively optimizing the loss functions of the generator pair and discriminator of SiGAN, we cannot only achieve photo-realistic face reconstruction, but also ensures the reconstructed information is useful for identity recognition. Experimental results demonstrate that SiGAN significantly outperforms existing face hallucination GANs in objective face verification performance, while achieving photo-realistic reconstruction. Moreover, for input LR faces from unknown identities who are not included in training, SiGAN can still do a good job.

##### Abstract (translated by Google)
尽管生成对抗网络（GAN）可以使低分辨率（LR）面部的照片般逼真的高分辨率（HR）面部产生幻觉，但它们无法保证保留幻觉HR面部的身份，使得HR面临着难以识别的问题。为了解决这个问题，我们提出了一个Siamese GAN（SiGAN）来重建HR面部，这些面部在视觉上类似于它们的相应身份。在暹罗网络之上，拟议的SiGAN由一对两个相同的发生器和一个鉴别器组成。我们以成对的方式将重建误差和身份标签信息合并到SiGAN的损失函数中。通过迭代优化生成器对和SiGAN鉴别器的损失函数，不仅可以实现照片真实的人脸重建，而且可以保证重构信息对身份识别有用。实验结果表明，SiGAN在客观面验证性能方面明显优于现有的面部幻觉GAN，同时实现了光学真实的重建。此外，对于未包含在训练中的未知身份的输入LR面部，SiGAN仍然可以做得很好。

##### URL
[http://arxiv.org/abs/1807.08370](http://arxiv.org/abs/1807.08370)

##### PDF
[http://arxiv.org/pdf/1807.08370](http://arxiv.org/pdf/1807.08370)

