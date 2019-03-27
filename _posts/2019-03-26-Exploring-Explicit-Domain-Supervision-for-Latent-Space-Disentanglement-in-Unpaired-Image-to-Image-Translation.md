---
layout: post
title: "Exploring Explicit Domain Supervision for Latent Space Disentanglement in Unpaired Image-to-Image Translation"
date: 2019-03-26 03:22:18
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN Face Classification
author: Jianxin Lin, Yingce Xia, Sen Liu, Tao Qin, Zhibo Chen, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Image-to-image translation tasks have been widely investigated with Generative Adversarial Networks (GANs). However, existing approaches are mostly designed in an unsupervised manner while little attention has been paid to domain information within unpaired data. In this paper, we treat domain information as explicit supervision and design an unpaired image-to-image translation framework, Domain-supervised GAN (DosGAN), which takes the first step towards the exploration of explicit domain supervision. In contrast to representing domain characteristics using different generators in CycleGAN or multiple domain codes in StarGAN, we pre-train a classification network to explicitly classify the domain of an image. After pre-training, this network is used to extract the domain-specific features of each image by using the output of its second-to-last layer. Such features, together with the domain-independent features extracted by another encoder (shared across different domains), are used to generate an image in the target domain. Extensive experiments on multiple hair color translation, multiple identity translation, multiple season translation and conditional edges-to-shoes/handbags demonstrate the effectiveness of our method. In addition, we can transfer the domain-specific feature extractor obtained on the Facescrub dataset with domain supervision information to unseen domains, such as faces in the CelebA dataset. We also succeed in achieving conditional translation with any two images in CelebA, while previous models like StarGAN cannot handle this task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03782](http://arxiv.org/abs/1902.03782)

##### PDF
[http://arxiv.org/pdf/1902.03782](http://arxiv.org/pdf/1902.03782)

