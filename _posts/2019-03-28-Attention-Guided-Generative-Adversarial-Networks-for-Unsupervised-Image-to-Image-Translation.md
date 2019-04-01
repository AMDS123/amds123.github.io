---
layout: post
title: "Attention-Guided Generative Adversarial Networks for Unsupervised Image-to-Image Translation"
date: 2019-03-28 22:59:47
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN Quantitative
author: Hao Tang, Dan Xu, Nicu Sebe, Yan Yan
mathjax: true
---

* content
{:toc}

##### Abstract
The state-of-the-art approaches in Generative Adversarial Networks (GANs) are able to learn a mapping function from one image domain to another with unpaired image data. However, these methods often produce artifacts and can only be able to convert low-level information, but fail to transfer high-level semantic part of images. The reason is mainly that generators do not have the ability to detect the most discriminative semantic part of images, which thus makes the generated images with low-quality. To handle the limitation, in this paper we propose a novel Attention-Guided Generative Adversarial Network (AGGAN), which can detect the most discriminative semantic object and minimize changes of unwanted part for semantic manipulation problems without using extra data and models. The attention-guided generators in AGGAN are able to produce attention masks via a built-in attention mechanism, and then fuse the input image with the attention mask to obtain a target image with high-quality. Moreover, we propose a novel attention-guided discriminator which only considers attended regions. The proposed AGGAN is trained by an end-to-end fashion with an adversarial loss, cycle-consistency loss, pixel loss and attention loss. Both qualitative and quantitative results demonstrate that our approach is effective to generate sharper and more accurate images than existing models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.12296](http://arxiv.org/abs/1903.12296)

##### PDF
[http://arxiv.org/pdf/1903.12296](http://arxiv.org/pdf/1903.12296)

