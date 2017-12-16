---
layout: post
title: "Accelerating GMM-based patch priors for image restoration: Three ingredients for a 100$times$ speed-up"
date: 2017-10-23 07:39:35
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Knowledge Optimization
author: Shibin Parameswaran (UC San Diego), Charles-Alban Deledalle (IMB, UC San Diego), Loïc Denis (UJM, IOGS), Truong Q. Nguyen (UC San Diego)
mathjax: true
---

* content
{:toc}

##### Abstract
Image restoration methods aim to recover the underlying clean image from corrupted observations. The Expected Patch Log-likelihood (EPLL) algorithm is a powerful image restoration method that uses a Gaussian mixture model (GMM) prior on the patches of natural images. Although it is very effective for restoring images, its high runtime complexity makes EPLL ill-suited for most practical applications. In this paper, we propose three approximations to the original EPLL algorithm. The resulting algorithm, which we call the fast-EPLL (FEPLL), attains a dramatic speed-up of two orders of magnitude over EPLL while incurring a negligible drop in the restored image quality (less than 0.5 dB). We demonstrate the efficacy and versatility of our algorithm on a number of inverse problems such as denoising, deblurring, super-resolution, inpainting and devignetting. To the best of our knowledge, FEPLL is the first algorithm that can competitively restore a 512x512 pixel image in under 0.5s for all the degradations mentioned above without specialized code optimizations such as CPU parallelization or GPU implementation.

##### Abstract (translated by Google)
图像恢复方法的目的是从损坏的观察中恢复底层的干净图像。预期修补对数似然（EPLL）算法是一种功能强大的图像恢复方法，在自然图像斑块之前使用高斯混合模型（GMM）。尽管对于恢复映像非常有效，但其高运行时复杂性使得EPLL不适合于大多数实际应用。在本文中，我们提出了三个近似原来的EPLL算法。由此产生的算法（我们称之为快速EPLL（FEPLL））在EPLL上实现了两个数量级的显着加速，而在恢复的图像质量（小于0.5 dB）上下降可以忽略不计。我们证明了我们的算法在多项反例如去噪，去模糊，超分辨率，修补和偏移等问题上的有效性和多功能性。据我们所知，FEPLL是第一个算法，可以在0.5s以内竞争恢复512x512像素的图像，而不需要特殊的代码优化，如CPU并行化或GPU实现。

##### URL
[https://arxiv.org/abs/1710.08124](https://arxiv.org/abs/1710.08124)

##### PDF
[https://arxiv.org/pdf/1710.08124](https://arxiv.org/pdf/1710.08124)

