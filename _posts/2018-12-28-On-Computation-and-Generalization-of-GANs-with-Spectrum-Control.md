---
layout: post
title: "On Computation and Generalization of GANs with Spectrum Control"
date: 2018-12-28 07:17:55
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Image_Generation
author: Haoming Jiang, Zhehui Chen, Minshuo Chen, Feng Liu, Dingding Wang, Tuo Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs), though powerful, is hard to train. Several recent works (brock2016neural,miyato2018spectral) suggest that controlling the spectra of weight matrices in the discriminator can significantly improve the training of GANs. Motivated by their discovery, we propose a new framework for training GANs, which allows more flexible spectrum control (e.g., making the weight matrices of the discriminator have slow singular value decays). Specifically, we propose a new reparameterization approach for the weight matrices of the discriminator in GANs, which allows us to directly manipulate the spectra of the weight matrices through various regularizers and constraints, without intensively computing singular value decompositions. Theoretically, we further show that the spectrum control improves the generalization ability of GANs. Our experiments on CIFAR-10, STL-10, and ImageNet datasets confirm that compared to other methods, our proposed method is capable of generating images with competitive quality by utilizing spectral normalization and encouraging the slow singular value decay.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.10912](https://arxiv.org/abs/1812.10912)

##### PDF
[https://arxiv.org/pdf/1812.10912](https://arxiv.org/pdf/1812.10912)

