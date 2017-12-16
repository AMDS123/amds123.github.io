---
layout: post
title: "Improving Consistency and Correctness of Sequence Inpainting using Semantically Guided Generative Adversarial Network"
date: 2017-11-17 08:10:08
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN Face Quantitative
author: Avisek Lahiri, Arnav Jain, Prabir Kumar Biswas, Pabitra Mitra
mathjax: true
---

* content
{:toc}

##### Abstract
Contemporary benchmark methods for image inpainting are based on deep generative models and specifically leverage adversarial loss for yielding realistic reconstructions. However, these models cannot be directly applied on image/video sequences because of an intrinsic drawback- the reconstructions might be independently realistic, but, when visualized as a sequence, often lacks fidelity to the original uncorrupted sequence. The fundamental reason is that these methods try to find the best matching latent space representation near to natural image manifold without any explicit distance based loss. In this paper, we present a semantically conditioned Generative Adversarial Network (GAN) for sequence inpainting. The conditional information constrains the GAN to map a latent representation to a point in image manifold respecting the underlying pose and semantics of the scene. To the best of our knowledge, this is the first work which simultaneously addresses consistency and correctness of generative model based inpainting. We show that our generative model learns to disentangle pose and appearance information; this independence is exploited by our model to generate highly consistent reconstructions. The conditional information also aids the generator network in GAN to produce sharper images compared to the original GAN formulation. This helps in achieving more appealing inpainting performance. Though generic, our algorithm was targeted for inpainting on faces. When applied on CelebA and Youtube Faces datasets, the proposed method results in a significant improvement over the current benchmark, both in terms of quantitative evaluation (Peak Signal to Noise Ratio) and human visual scoring over diversified combinations of resolutions and deformations.

##### Abstract (translated by Google)
当前的图像修复基准方法基于深度生成模型，特别是利用对抗性损失来产生逼真的重建。然而，由于内在的缺点，这些模型不能直接应用于图像/视频序列 - 重建可能是独立现实的，但是当被视为一个序列时，往往缺乏对原始未破坏序列的保真度。根本的原因是这些方法试图找到自然图像流形附近的最佳匹配潜在空间表示，没有任何明确的基于距离的损失。在本文中，我们提出了语义条件生成敌对网络（GAN）序列修复。条件信息限制GAN将潜在表示映射到图像流形中关于场景的底层姿态和语义的点。就我们所知，这是第一个同时处理基于生成模型的修复的一致性和正确性的工作。我们显示我们的生成模型学习解开姿势和外观信息;这种独立性被我们的模型利用来产生高度一致的重建。条件信息也有助于GAN中的发生器网络与原来的GAN公式相比产生更清晰的图像。这有助于实现更具吸引力的修补性能。虽然通用，我们的算法是针对面部修补。当应用于CelebA和Youtube Faces数据集时，所提出的方法在定量评估（峰值信噪比）和通过分辨率和变形的多种组合的人类视觉评分两方面都比当前基准有显着改善。

##### URL
[https://arxiv.org/abs/1711.06106](https://arxiv.org/abs/1711.06106)

##### PDF
[https://arxiv.org/pdf/1711.06106](https://arxiv.org/pdf/1711.06106)

