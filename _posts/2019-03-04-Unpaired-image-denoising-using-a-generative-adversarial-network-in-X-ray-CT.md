---
layout: post
title: "Unpaired image denoising using a generative adversarial network in X-ray CT"
date: 2019-03-04 06:01:42
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Deep_Learning
author: Hyoung Suk Park, Jineon Baek, Sun Kyoung You, Jae Kyu Choi, Jin Keun Seo
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a deep learning-based denoising method for noisy low-dose computerized tomography (CT) images in the absence of paired training data. The proposed method uses a fidelity-embedded generative adversarial network (GAN) to learn a denoising function from unpaired training data of low-dose CT (LDCT) and standard-dose CT (SDCT) images, where the denoising function is the optimal generator in the GAN framework. Given an optimal discriminator in the GAN, the generator is optimized by minimizing a weighted sum of two losses: the Kullback-Leibler divergence between an SDCT data distribution and a generated distribution, and the $\ell_2$ loss between the LDCT image and the corresponding generated images (or denoised image). The experimental results show that the proposed deep-learning method with unpaired datasets performs comparably to a method using paired datasets. Clinical experiment was also performed to show the validity of the proposed method for non-Gaussian noise arising in the low-dose X-ray CT.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06257](http://arxiv.org/abs/1903.06257)

##### PDF
[http://arxiv.org/pdf/1903.06257](http://arxiv.org/pdf/1903.06257)

