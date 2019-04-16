---
layout: post
title: "MedGAN: Medical Image Translation using GANs"
date: 2019-04-04 14:34:21
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Karim Armanious, Chenming Jiang, Marc Fischer, Thomas Küstner, Konstantin Nikolaou, Sergios Gatidis, Bin Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Image-to-image translation is considered a new frontier in the field of medical image analysis, with numerous potential applications. However, a large portion of recent approaches offers individualized solutions based on specialized task-specific architectures or require refinement through non-end-to-end training. In this paper, we propose a new framework, named MedGAN, for medical image-to-image translation which operates on the image level in an end-to-end manner. MedGAN builds upon recent advances in the field of generative adversarial networks (GANs) by merging the adversarial framework with a new combination of non-adversarial losses. We utilize a discriminator network as a trainable feature extractor which penalizes the discrepancy between the translated medical images and the desired modalities. Moreover, style-transfer losses are utilized to match the textures and fine-structures of the desired target images to the translated images. Additionally, we present a new generator architecture, titled CasNet, which enhances the sharpness of the translated medical outputs through progressive refinement via encoder-decoder pairs. Without any application-specific modifications, we apply MedGAN on three different tasks: PET-CT translation, correction of MR motion artefacts and PET image denoising. Perceptual analysis by radiologists and quantitative evaluations illustrate that the MedGAN outperforms other existing translation approaches.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.06397](https://arxiv.org/abs/1806.06397)

##### PDF
[https://arxiv.org/pdf/1806.06397](https://arxiv.org/pdf/1806.06397)

