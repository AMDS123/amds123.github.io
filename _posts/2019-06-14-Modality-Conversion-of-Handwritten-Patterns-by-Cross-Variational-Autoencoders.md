---
layout: post
title: "Modality Conversion of Handwritten Patterns by Cross Variational Autoencoders"
date: 2019-06-14 11:53:39
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Taichi Sumi, Brian Kenji Iwana, Hideaki Hayashi, Seiichi Uchida
mathjax: true
---

* content
{:toc}

##### Abstract
This research attempts to construct a network that can convert online and offline handwritten characters to each other. The proposed network consists of two Variational Auto-Encoders (VAEs) with a shared latent space. The VAEs are trained to generate online and offline handwritten Latin characters simultaneously. In this way, we create a cross-modal VAE (Cross-VAE). During training, the proposed Cross-VAE is trained to minimize the reconstruction loss of the two modalities, the distribution loss of the two VAEs, and a novel third loss called the space sharing loss. This third, space sharing loss is used to encourage the modalities to share the same latent space by calculating the distance between the latent variables. Through the proposed method mutual conversion of online and offline handwritten characters is possible. In this paper, we demonstrate the performance of the Cross-VAE through qualitative and quantitative analysis.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.06142](https://arxiv.org/abs/1906.06142)

##### PDF
[https://arxiv.org/pdf/1906.06142](https://arxiv.org/pdf/1906.06142)

