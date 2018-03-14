---
layout: post
title: "Correction by Projection: Denoising Images with Generative Adversarial Networks"
date: 2018-03-12 19:30:01
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN
author: Subarna Tripathi, Zachary C. Lipton, Truong Q. Nguyen
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) transform low-dimensional latent vectors into visually plausible images. If the real dataset contains only clean images, then ostensibly, the manifold learned by the GAN should contain only clean images. In this paper, we propose to denoise corrupted images by finding the nearest point on the GAN manifold, recovering latent vectors by minimizing distances in image space. We first demonstrate that given a corrupted version of an image that truly lies on the GAN manifold, we can approximately recover the latent vector and denoise the image, obtaining significantly higher quality, comparing with BM3D. Next, we demonstrate that latent vectors recovered from noisy images exhibit a consistent bias. By subtracting this bias before projecting back to image space, we improve denoising results even further. Finally, even for unseen images, our method performs better at denoising better than BM3D. Notably, the basic version of our method (without bias correction) requires no prior knowledge on the noise variance. To achieve the highest possible denoising quality, the best performing signal processing based methods, such as BM3D, require an estimate of the blur kernel.

##### Abstract (translated by Google)
生成对抗网络（GAN）将低维潜在向量转换成视觉上合理的图像。如果真正的数据集只包含干净的图像，那么表面上看，由GAN学习的流形应该只包含干净的图像。在本文中，我们提出通过在GAN流形上找到最近点来消除被破坏的图像，通过最小化图像空间中的距离来恢复潜在向量。我们首先证明，给定一个真正位于GAN流形上的图像的损坏版本，我们可以近似恢复潜在向量并对图像进行去噪，与BM3D相比，我们可以获得更高的质量。接下来，我们证明从噪声图像中恢复的潜在载体表现出一致的偏见。通过在投影回图像空间之前减去该偏差，我们可以进一步改善去噪结果。最后，即使对于看不见的图像，我们的方法的去噪效果也比BM3D更好。值得注意的是，我们的方法的基本版本（没有偏差校正）不需要关于噪声方差的先验知识。为了实现尽可能高的去噪质量，基于最佳性能的基于信号处理的方法（如BM3D）需要估计模糊核。

##### URL
[http://arxiv.org/abs/1803.04477](http://arxiv.org/abs/1803.04477)

##### PDF
[http://arxiv.org/pdf/1803.04477](http://arxiv.org/pdf/1803.04477)

