---
layout: post
title: "Regularizing Deep Hashing Networks Using GAN Generated Fake Images"
date: 2018-09-02 16:24:44
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Adversarial GAN
author: Libing Geng, Yan Pan, Jikai Chen, Hanjiang Lai
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep-networks-based hashing (deep hashing) has become a leading approach for large-scale image retrieval. It aims to learn a compact bitwise representation for images via deep networks, so that similar images are mapped to nearby hash codes. Since a deep network model usually has a large number of parameters, it may probably be too complicated for the training data we have, leading to model over-fitting. To address this issue, in this paper, we propose a simple two-stage pipeline to learn deep hashing models, by regularizing the deep hashing networks using fake images. The first stage is to generate fake images from the original training set without extra data, via a generative adversarial network (GAN). In the second stage, we propose a deep architec- ture to learn hash functions, in which we use a maximum-entropy based loss to incorporate the newly created fake images by the GAN. We show that this loss acts as a strong regularizer of the deep architecture, by penalizing low-entropy output hash codes. This loss can also be interpreted as a model ensemble by simultaneously training many network models with massive weight sharing but over different training sets. Empirical evaluation results on several benchmark datasets show that the proposed method has superior performance gains over state-of-the-art hashing methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.09466](https://arxiv.org/abs/1803.09466)

##### PDF
[https://arxiv.org/e-print/1803.09466](https://arxiv.org/e-print/1803.09466)

