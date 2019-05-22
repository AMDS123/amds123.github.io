---
layout: post
title: "Toward Learning a Unified Many-to-Many Mapping for Diverse Image Translation"
date: 2019-05-21 17:35:57
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Wenju Xu, Shawn Keshmiri, Guanghui Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Image-to-image translation, which translates input images to a different domain with a learned one-to-one mapping, has achieved impressive success in recent years. The success of translation mainly relies on the network architecture to reserve the structural information while modify the appearance slightly at the pixel level through adversarial training. Although these networks are able to learn the mapping, the translated images are predictable without exclusion. It is more desirable to diversify them using image-to-image translation by introducing uncertainties, i.e., the generated images hold potential for variations in colors and textures in addition to the general similarity to the input images, and this happens in both the target and source domains. To this end, we propose a novel generative adversarial network (GAN) based model, InjectionGAN, to learn a many-to-many mapping. In this model, the input image is combined with latent variables, which comprise of domain-specific attribute and unspecific random variations. The domain-specific attribute indicates the target domain of the translation, while the unspecific random variations introduce uncertainty into the model. A unified framework is proposed to regroup these two parts and obtain diverse generations in each domain. Extensive experiments demonstrate that the diverse generations have high quality for the challenging image-to-image translation tasks where no pairing information of the training dataset exits. Both quantitative and qualitative results prove the superior performance of InjectionGAN over the state-of-the-art approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08766](http://arxiv.org/abs/1905.08766)

##### PDF
[http://arxiv.org/pdf/1905.08766](http://arxiv.org/pdf/1905.08766)

