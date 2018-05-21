---
layout: post
title: "An Unsupervised Approach to Solving Inverse Problems using Generative Adversarial Networks"
date: 2018-05-18 15:23:01
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN Deep_Learning
author: Rushil Anirudh, Jayaraman J. Thiagarajan, Bhavya Kailkhura, Timo Bremer
mathjax: true
---

* content
{:toc}

##### Abstract
Solving inverse problems continues to be a challenge in a wide array of applications ranging from deblurring, image inpainting, source separation etc. Most existing techniques solve such inverse problems by either explicitly or implicitly finding the inverse of the model. The former class of techniques require explicit knowledge of the measurement process which can be unrealistic, and rely on strong analytical regularizers to constrain the solution space, which often do not generalize well. The latter approaches have had remarkable success in part due to deep learning, but require a large collection of source-observation pairs, which can be prohibitively expensive. In this paper, we propose an unsupervised technique to solve inverse problems with generative adversarial networks (GANs). Using a pre-trained GAN in the space of source signals, we show that one can reliably recover solutions to under determined problems in a `blind' fashion, i.e., without knowledge of the measurement process. We solve this by making successive estimates on the model and the solution in an iterative fashion. We show promising results in three challenging applications -- blind source separation, image deblurring, and recovering an image from its edge map, and perform better than several baselines.

##### Abstract (translated by Google)
解决逆问题在去模糊，图像修复，源分离等广泛的应用中仍然是一个挑战。大多数现有技术通过显式或隐式地找到模型的逆来解决这样的逆问题。前一类技术需要对测量过程有明确的了解，这种测量过程可能不现实，并依靠强大的分析调节器来约束解决方案空间，而这往往不能很好地推广。后一种方法取得了显着的成功，部分原因在于深入的学习，但需要大量的源观察对，这些对可能过于昂贵。在本文中，我们提出了一种无监督技术来解决生成对抗网络（GAN）的逆问题。在源信号空间中使用预先训练好的GAN，我们表明，人们可以可靠地以“盲”的方式恢复所确定的问题的解决方案，即不知道测量过程。我们通过以迭代方式对模型和解决方案进行连续估计来解决这个问题。我们在三个具有挑战性的应用中展示了有希望的结果 - 盲源分离，图像去模糊，以及从其边缘映射中恢复图像，并且比几个基线执行得更好。

##### URL
[http://arxiv.org/abs/1805.07281](http://arxiv.org/abs/1805.07281)

##### PDF
[http://arxiv.org/pdf/1805.07281](http://arxiv.org/pdf/1805.07281)

