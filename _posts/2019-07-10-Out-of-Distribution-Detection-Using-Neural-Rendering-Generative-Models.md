---
layout: post
title: "Out-of-Distribution Detection Using Neural Rendering Generative Models"
date: 2019-07-10 08:32:53
categories: arXiv_CV
tags: arXiv_CV Knowledge Detection
author: Yujia Huang, Sihui Dai, Tan Nguyen, Richard G. Baraniuk, Anima Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
Out-of-distribution (OoD) detection is a natural downstream task for deep generative models, due to their ability to learn the input probability distribution. There are mainly two classes of approaches for OoD detection using deep generative models, viz., based on likelihood measure and the reconstruction loss. However, both approaches are unable to carry out OoD detection effectively, especially when the OoD samples have smaller variance than the training samples. For instance, both flow based and VAE models assign higher likelihood to images from SVHN when trained on CIFAR-10 images. We use a recently proposed generative model known as neural rendering model (NRM) and derive metrics for OoD. We show that NRM unifies both approaches since it provides a likelihood estimate and also carries out reconstruction in each layer of the neural network. Among various measures, we found the joint likelihood of latent variables to be the most effective one for OoD detection. Our results show that when trained on CIFAR-10, lower likelihood (of latent variables) is assigned to SVHN images. Additionally, we show that this metric is consistent across other OoD datasets. To the best of our knowledge, this is the first work to show consistently lower likelihood for OoD data with smaller variance with deep generative models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04572](http://arxiv.org/abs/1907.04572)

##### PDF
[http://arxiv.org/pdf/1907.04572](http://arxiv.org/pdf/1907.04572)

