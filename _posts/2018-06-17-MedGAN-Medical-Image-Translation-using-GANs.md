---
layout: post
title: "MedGAN: Medical Image Translation using GANs"
date: 2018-06-17 15:45:10
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Karim Armanious, Chenming Yang, Marc Fischer, Thomas K&#xfc;stner, Konstantin Nikolaou, Sergios Gatidis, Bin Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Image-to-image translation is considered a next frontier in the field of medical image analysis, with numerous potential applications. However, recent advances in this field offer individualized solutions by utilizing specialized architectures which are task specific or by suffering from limited capacities and thus requiring refinement through non end-to-end training. In this paper, we propose a novel general purpose framework for medical image-to-image translation, titled MedGAN, which operates in an end-to-end manner on the image level. MedGAN builds upon recent advances in the field of generative adversarial networks(GANs) by combining the adversarial framework with a unique combination of non-adversarial losses which captures the high and low frequency components of the desired target modality. Namely, we utilize a discriminator network as a trainable feature extractor which penalizes the discrepancy between the translated medical images and the desired modalities in the pixel and perceptual sense. Moreover, style-transfer losses are utilized to match the textures and fine-structures of the desired target images to the outputs. Additionally, we present a novel generator architecture, titled CasNet, which enhances the sharpness of the translated medical outputs through progressive refinement via encoder decoder pairs. To demonstrate the effectiveness of our approach, we apply MedGAN on three novel and challenging applications: PET-CT translation, correction of MR motion artefacts and PET image denoising. Qualitative and quantitative comparisons with state-of-the-art techniques have emphasized the superior performance of the proposed framework. MedGAN can be directly applied as a general framework for future medical translation tasks.

##### Abstract (translated by Google)
图像到图像的转换被认为是医学图像分析领域的下一个前沿，有许多潜在的应用。然而，该领域的最新进展通过利用专门架构来提供个性化解决方案，这些架构是特定任务或受限能力，因此需要通过非端到端培训进行改进。在本文中，我们提出了一种用于医学图像到图像翻译的新型通用框架，标题为MedGAN，它在图像层面上以端到端的方式进行操作。 MedGAN以生成对抗网络（GAN）领域的最新进展为基础，将对抗性框架与非对抗性损失的独特组合相结合，捕捉所需目标模态的高频和低频分量。也就是说，我们利用鉴别器网络作为可训练的特征提取器，其惩罚翻译后的医学图像与像素和感知意义中期望的模态之间的差异。此外，风格转移损失被用来匹配所需目标图像的纹理和精细结构到输出。此外，我们提出了一种新颖的发生器架构，标题为CasNet，它通过经由编码器解码器对的渐进式细化增强了翻译的医疗输出的清晰度。为了证明我们方法的有效性，我们将MedGAN应用于三种新颖且具有挑战性的应用：PET-CT平移，MR运动伪像的校正和PET图像去噪。与最新技术的定性和定量比较强调了所提议的框架的优越性能。 MedGAN可以直接应用为未来医学翻译任务的一般框架。

##### URL
[http://arxiv.org/abs/1806.06397](http://arxiv.org/abs/1806.06397)

##### PDF
[http://arxiv.org/pdf/1806.06397](http://arxiv.org/pdf/1806.06397)

