---
layout: post
title: "Unsupervised Image Noise Modeling with Self-Consistent GAN"
date: 2019-06-13 15:45:46
categories: arXiv_CV
tags: arXiv_CV Super_Resolution GAN Deep_Learning
author: Hanshu Yan, Vincent Tan, Wenhan Yang, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Noise modeling lies in the heart of many image processing tasks. However, existing deep learning methods for noise modeling generally require clean and noisy image pairs for model training; these image pairs are difficult to obtain in many realistic scenarios. To ameliorate this problem, we propose a self-consistent GAN (SCGAN), that can directly extract noise maps from noisy images, thus enabling unsupervised noise modeling. In particular, the SCGAN introduces three novel self-consistent constraints that are complementary to one another, viz.: the noise model should produce a zero response over a clean input; the noise model should return the same output when fed with a specific pure noise input; and the noise model also should re-extract a pure noise map if the map is added to a clean image. These three constraints are simple yet effective. They jointly facilitate unsupervised learning of a noise model for various noise types. To demonstrate its wide applicability, we deploy the SCGAN on three image processing tasks including blind image denoising, rain streak removal, and noisy image super-resolution. The results demonstrate the effectiveness and superiority of our method over the state-of-the-art methods on a variety of benchmark datasets, even though the noise types vary significantly and paired clean images are not available.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05762](https://arxiv.org/abs/1906.05762)

##### PDF
[https://arxiv.org/pdf/1906.05762](https://arxiv.org/pdf/1906.05762)

