---
layout: post
title: "Spatial Variational Auto-Encoding via Matrix-Variate Normal Distributions"
date: 2019-01-22 17:48:22
categories: arXiv_CV
tags: arXiv_CV
author: Zhengyang Wang, Hao Yuan, Shuiwang Ji
mathjax: true
---

* content
{:toc}

##### Abstract
The key idea of variational auto-encoders (VAEs) resembles that of traditional auto-encoder models in which spatial information is supposed to be explicitly encoded in the latent space. However, the latent variables in VAEs are vectors, which can be interpreted as multiple feature maps of size 1x1. Such representations can only convey spatial information implicitly when coupled with powerful decoders. In this work, we propose spatial VAEs that use feature maps of larger size as latent variables to explicitly capture spatial information. This is achieved by allowing the latent variables to be sampled from matrix-variate normal (MVN) distributions whose parameters are computed from the encoder network. To increase dependencies among locations on latent feature maps and reduce the number of parameters, we further propose spatial VAEs via low-rank MVN distributions. Experimental results show that the proposed spatial VAEs outperform original VAEs in capturing rich structural and spatial information.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1705.06821](http://arxiv.org/abs/1705.06821)

##### PDF
[http://arxiv.org/pdf/1705.06821](http://arxiv.org/pdf/1705.06821)

