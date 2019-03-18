---
layout: post
title: "Quality-aware Unpaired Image-to-Image Translation"
date: 2019-03-15 07:59:07
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Lei Chen, Le Wu, Zhenzhen Hu, Meng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) have been widely used for the image-to-image translation task. While these models rely heavily on the labeled image pairs, recently some GAN variants have been proposed to tackle the unpaired image translation task. These models exploited supervision at the domain level with a reconstruction process for unpaired image translation. On the other hand, parallel works have shown that leveraging perceptual loss functions based on high level deep features could enhance the generated image quality. Nevertheless, as these GAN-based models either depended on the pretrained deep network structure or relied on the labeled image pairs, they could not be directly applied to the unpaired image translation task. Moreover, despite the improvement of the introduced perceptual losses from deep neural networks, few researchers have explored the possibility of improving the generated image quality from classical image quality measures. To tackle the above two challenges, in this paper, we propose a unified quality-aware GAN-based framework for unpaired image-to-image translation, where a quality-aware loss is explicitly incorporated by comparing each source image and the reconstructed image at the domain level. Specifically, we design two detailed implementations of the quality loss. The first method is based on a classical image quality assessment measure by defining a classical quality-aware loss. The second method proposes an adaptive deep network based loss. Finally, extensive experimental results on many real-world datasets clearly show the quality improvement of our proposed framework, and the superiority of leveraging classical image quality measures for unpaired image translation compared to the deep network based model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06399](http://arxiv.org/abs/1903.06399)

##### PDF
[http://arxiv.org/pdf/1903.06399](http://arxiv.org/pdf/1903.06399)

