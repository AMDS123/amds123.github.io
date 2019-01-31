---
layout: post
title: "Latent Normalizing Flows for Discrete Sequences"
date: 2019-01-29 21:05:46
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Zachary M. Ziegler, Alexander M. Rush
mathjax: true
---

* content
{:toc}

##### Abstract
Normalizing flows have been shown to be a powerful class of generative models for continuous random variables, giving both strong performance and the potential for non-autoregressive generation. These benefits are also desired when modeling discrete random variables such as text, but directly applying normalizing flows to discrete sequences poses significant additional challenges. We propose a generative model which jointly learns a normalizing flow-based distribution in the latent space and a stochastic mapping to an observed discrete space. In this setting, we find that it is crucial for the flow-based distribution to be highly multimodal. To capture this property, we propose several normalizing flow architectures to maximize model flexibility. Experiments consider common discrete sequence tasks of character-level language modeling and polyphonic music generation. Our results indicate that an autoregressive flow-based model can match the performance of a comparable autoregressive baseline, and a non-autoregressive flow-based model can improve generation speed with a penalty to performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10548](http://arxiv.org/abs/1901.10548)

##### PDF
[http://arxiv.org/pdf/1901.10548](http://arxiv.org/pdf/1901.10548)

