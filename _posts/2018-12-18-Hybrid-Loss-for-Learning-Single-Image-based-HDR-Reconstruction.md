---
layout: post
title: "Hybrid Loss for Learning Single-Image-based HDR Reconstruction"
date: 2018-12-18 01:57:27
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge
author: Kenta Moriwaki, Ryota Yoshihashi, Rei Kawakami, Shaodi You, Takeshi Naemura
mathjax: true
---

* content
{:toc}

##### Abstract
This paper tackles high-dynamic-range (HDR) image reconstruction given only a single low-dynamic-range (LDR) image as input. While the existing methods focus on minimizing the mean-squared-error (MSE) between the target and reconstructed images, we minimize a hybrid loss that consists of perceptual and adversarial losses in addition to HDR-reconstruction loss. The reconstruction loss instead of MSE is more suitable for HDR since it puts more weight on both over- and under- exposed areas. It makes the reconstruction faithful to the input. Perceptual loss enables the networks to utilize knowledge about objects and image structure for recovering the intensity gradients of saturated and grossly quantized areas. Adversarial loss helps to select the most plausible appearance from multiple solutions. The hybrid loss that combines all the three losses is calculated in logarithmic space of image intensity so that the outputs retain a large dynamic range and meanwhile the learning becomes tractable. Comparative experiments conducted with other state-of-the-art methods demonstrated that our method produces a leap in image quality.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07134](http://arxiv.org/abs/1812.07134)

##### PDF
[http://arxiv.org/pdf/1812.07134](http://arxiv.org/pdf/1812.07134)

