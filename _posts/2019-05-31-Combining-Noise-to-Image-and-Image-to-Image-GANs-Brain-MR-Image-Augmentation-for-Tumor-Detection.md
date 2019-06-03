---
layout: post
title: "Combining Noise-to-Image and Image-to-Image GANs: Brain MR Image Augmentation for Tumor Detection"
date: 2019-05-31 08:14:19
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Classification Detection VQA
author: Changhee Han, Leonardo Rundo, Ryosuke Araki, Yudai Nagano, Yujiro Furukawa, Giancarlo Mauri, Hideki Nakayama, Hideaki Hayashi
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) can achieve excellent computer-assisted diagnosis performance, relying on sufficient annotated training data. Unfortunately, most medical imaging datasets, often collected from various scanners, are small and fragmented. In this context, as a Data Augmentation (DA) technique, Generative Adversarial Networks (GANs) can synthesize realistic/diverse additional training images to fill the data lack in the real image distribution; researchers have improved classification by augmenting images with noise-to-image (e.g., random noise samples to diverse pathological images) or image-to-image GANs (e.g., a benign image to a malignant one). Yet, no research has reported results combining (i) noise-to-image GANs and image-to-image GANs or (ii) GANs and other deep generative models, for further performance boost. Therefore, to maximize the DA effect with the GAN combinations, we propose a two-step GAN-based DA that generates and refines brain MR images with/without tumors separately: (i) Progressive Growing of GANs (PGGANs), multi-stage noise-to-image GAN for high-resolution image generation, first generates realistic/diverse 256 x 256 images--even a physician cannot accurately distinguish them from real ones via Visual Turing Test; (ii) UNsupervised Image-to-image Translation or SimGAN, image-to-image GAN combining GANs/Variational AutoEncoders or using a GAN loss for DA, further refines the texture/shape of the PGGAN-generated images similarly to the real ones. We thoroughly investigate CNN-based tumor classification results, also considering the influence of pre-training on ImageNet and discarding weird-looking GAN-generated images. The results show that, when combined with classic DA, our two-step GAN-based DA can significantly outperform the classic DA alone, in tumor detection (i.e., boosting sensitivity from 93.63% to 97.53%) and also in other tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13456](http://arxiv.org/abs/1905.13456)

##### PDF
[http://arxiv.org/pdf/1905.13456](http://arxiv.org/pdf/1905.13456)

