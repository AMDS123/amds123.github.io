---
layout: post
title: "Syntax-Infused Variational Autoencoder for Text Generation"
date: 2019-06-05 22:48:08
categories: arXiv_CL
tags: arXiv_CL Text_Generation
author: Xinyuan Zhang, Yi Yang, Siyang Yuan, Dinghan Shen, Lawrence Carin
mathjax: true
---

* content
{:toc}

##### Abstract
We present a syntax-infused variational autoencoder (SIVAE), that integrates sentences with their syntactic trees to improve the grammar of generated sentences. Distinct from existing VAE-based text generative models, SIVAE contains two separate latent spaces, for sentences and syntactic trees. The evidence lower bound objective is redesigned correspondingly, by optimizing a joint distribution that accommodates two encoders and two decoders. SIVAE works with long short-term memory architectures to simultaneously generate sentences and syntactic trees. Two versions of SIVAE are proposed: one captures the dependencies between the latent variables through a conditional prior network, and the other treats the latent variables independently such that syntactically-controlled sentence generation can be performed. Experimental results demonstrate the generative superiority of SIVAE on both reconstruction and targeted syntactic evaluations. Finally, we show that the proposed models can be used for unsupervised paraphrasing given different syntactic tree templates.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02181](http://arxiv.org/abs/1906.02181)

##### PDF
[http://arxiv.org/pdf/1906.02181](http://arxiv.org/pdf/1906.02181)

