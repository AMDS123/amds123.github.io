---
layout: post
title: "Unpaired Image-to-Image Translation with Domain Supervision"
date: 2019-02-11 09:07:30
categories: arXiv_CV
tags: arXiv_CV Attention GAN Face Classification
author: Jianxin Lin, Sen Liu, Yingce Xia, Shuxin Zhao, Tao Qin, Zhibo Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Image-to-image translation has been widely investigated in recent years. Existing approaches are elaborately designed in an unsupervised manner and little attention has been paid to domain information beneath unpaired data. In this work, we treat domain information as explicit supervision and design an unpaired image-to-image translation framework, Domain-supervised GAN (briefly, DosGAN), that takes the first step towards exploration of domain supervision. Instead of representing domain characteristics with different generators in CycleGAN\cite{zhu2017unpaired} or multiple domain codes in StarGAN~\cite{choi2017stargan}, we pre-train a classification network to classify the domain of an image. After pre-training, this network is used to extract domain features of each image by using the output of its second-to-last layer. Such features, together with the latent semantic features extracted by another encoder (shared across different domains), are used to generate an image in the target domain. Experiments on multiple hair color translation, multiple identity translation and conditional edges-to-shoes/handbags demonstrate the effectiveness of our method. In addition, we transfer the domain feature extractor obtained on the Facescrub dataset with domain supervision information, to the CelebA dataset without domain supervision information, and succeed achieving conditional translation with any two images in CelebA, while previous models like StarGAN cannot handle this task. Our code is available at \url{https://github.com/linjx-ustc1106/DosGAN-PyTorch}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03782](http://arxiv.org/abs/1902.03782)

##### PDF
[http://arxiv.org/pdf/1902.03782](http://arxiv.org/pdf/1902.03782)

