---
layout: post
title: "Image De-raining Using a Conditional Generative Adversarial Network"
date: 2017-02-04 16:12:45
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization Classification Quantitative Detection
author: He Zhang, Vishwanath Sindagi, Vishal M. Patel
mathjax: true
---

* content
{:toc}

##### Abstract
Severe weather conditions such as rain and snow adversely affect the visual quality of images captured under such conditions thus rendering them useless for further usage and sharing. In addition, such degraded images drastically affect performance of vision systems. Hence, it is important to solve the problem of single image de-raining/de-snowing. However, this is a difficult problem to solve due to its inherent ill-posed nature. Existing approaches attempt to introduce prior information to convert it into a well-posed problem. In this paper, we investigate a new point of view in addressing the single image de-raining problem. Instead of focusing only on deciding what is a good prior or a good framework to achieve good quantitative and qualitative performance, we also ensure that the de-rained image itself does not degrade the performance of a given computer vision algorithm such as detection and classification. In other words, the de-rained result should be indistinguishable from its corresponding clear image to a given discriminator. This criterion can be directly incorporated into the optimization framework by using the recently introduced conditional generative adversarial networks (GANs). To minimize artifacts introduced by GANs and ensure better visual quality, a new refined loss function is introduced. Based on this, we propose a novel single image de-raining method called Image De-raining Conditional General Adversarial Network (ID-CGAN), which considers quantitative, visual and also discriminative performance into the objective function. Experiments evaluated on synthetic images and real images show that the proposed method outperforms many recent state-of-the-art single image de-raining methods in terms of quantitative and visual performance.

##### Abstract (translated by Google)
恶劣的天气条件，例如雨雪，对在这样的条件下拍摄的图像的视觉质量产生不利影响，从而使得它们无法用于进一步的使用和共享。另外，这种退化的图像严重影响视觉系统的性能。因此，解决单张图像的降雪/除雪问题是非常重要的。但是，由于其内在的病态性质，这是一个难以解决的问题。现有的方法试图引入先验信息，将其转化为适当的问题。在本文中，我们调查了解决单个图像衰减问题的新观点。我们不仅仅关注于决定什么是一个好的先验或者良好的框架，以实现良好的定量和定性的表现，而且还确保了衰落的图像本身不会降低诸如检测和分类的给定计算机视觉算法的性能。换句话说，降噪后的结果应该与其相应的清晰图像区分开来。这个标准可以通过使用最近引入的条件生成对抗网络（GAN）直接并入到优化框架中。为了最大限度地减少由GAN引入的伪影并确保更好的视觉质量，引入了新的精细损失函数。在此基础上，提出了一种新的基于图像降噪的条件通用对抗网络（ID-CGAN）的单幅图像降噪方法，该方法将定量，可视和判别性能考虑为目标函数。在合成图像和真实图像上评估的实验表明，所提出的方法在定量和视觉性能方面胜过了许多近来的最先进的单个图像衰减方法。

##### URL
[https://arxiv.org/abs/1701.05957](https://arxiv.org/abs/1701.05957)

##### PDF
[https://arxiv.org/pdf/1701.05957](https://arxiv.org/pdf/1701.05957)

