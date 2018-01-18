---
layout: post
title: "Semi-supervised FusedGAN for Conditional Image Generation"
date: 2018-01-17 05:07:49
categories: arXiv_CV
tags: arXiv_CV GAN Face
author: Navaneeth Bodla, Gang Hua, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
We present FusedGAN, a deep network for conditional image synthesis with controllable sampling of diverse images. Fidelity, diversity and controllable sampling are the main quality measures of a good image generation model. Most existing models are insufficient in all three aspects. The FusedGAN can perform controllable sampling of diverse images with very high fidelity. We argue that controllability can be achieved by disentangling the generation process into various stages. In contrast to stacked GANs, where multiple stages of GANs are trained separately with full supervision of labeled intermediate images, the FusedGAN has a single stage pipeline with a built-in stacking of GANs. Unlike existing methods, which requires full supervision with paired conditions and images, the FusedGAN can effectively leverage more abundant images without corresponding conditions in training, to produce more diverse samples with high fidelity. We achieve this by fusing two generators: one for unconditional image generation, and the other for conditional image generation, where the two partly share a common latent space thereby disentangling the generation. We demonstrate the efficacy of the FusedGAN in fine grained image generation tasks such as text-to-image, and attribute-to-face generation.

##### Abstract (translated by Google)
我们提供FusedGAN，一个深度网络条件图像合成与可控采样的不同图像。保真度，多样性和可控采样是良好图像生成模型的主要质量指标。现有的大多数模式在三个方面都不够。 FusedGAN可以以高保真度对各种图像进行可控采样。我们认为，可控性可以通过将发电过程分解成不同的阶段来实现。与堆叠的GAN相反，GAN的多个阶段是在完全监督标记的中间图像的情况下分别进行训练的，FusedGAN具有内置GAN堆叠的单级管线。与现有的方法不同，它需要完全监督配对的条件和图像，FusedGAN可以有效地利用更丰富的图像，没有相应的培训条件，以高保真度生产更多样化的样品。我们通过融合两个生成器来实现这一点：一个用于无条件图像生成，另一个用于条件图像生成，其中两个生成器部分共享一个共同的潜在空间，从而解开生成。我们展示了FusedGAN在细粒度图像生成任务（如文本到图像和属性到面部生成）中的功效。

##### URL
[http://arxiv.org/abs/1801.05551](http://arxiv.org/abs/1801.05551)

##### PDF
[http://arxiv.org/pdf/1801.05551](http://arxiv.org/pdf/1801.05551)

