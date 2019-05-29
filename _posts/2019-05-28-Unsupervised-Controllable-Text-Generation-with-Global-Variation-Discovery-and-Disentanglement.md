---
layout: post
title: "Unsupervised Controllable Text Generation with Global Variation Discovery and Disentanglement"
date: 2019-05-28 17:49:47
categories: arXiv_CL
tags: arXiv_CL Sentiment Text_Generation Style_Transfer
author: Peng Xu, Yanshuai Cao, Jackie Chi Kit Cheung
mathjax: true
---

* content
{:toc}

##### Abstract
Existing controllable text generation systems rely on annotated attributes, which greatly limits their capabilities and applications. In this work, we make the first successful attempt to use VAEs to achieve controllable text generation without supervision. We do so by decomposing the latent space of the VAE into two parts: one incorporates structural constraints to capture dominant global variations implicitly present in the data, e.g., sentiment or topic; the other is unstructured and is used for the reconstruction of the source sentences. With the enforced structural constraint, the underlying global variations will be discovered and disentangled during the training of the VAE. The structural constraint also provides a natural recipe for mitigating posterior collapse for the structured part, which cannot be fully resolved by the existing techniques. On the task of text style transfer, our unsupervised approach achieves significantly better performance than previous supervised approaches. By showcasing generation with finer-grained control including Cards-Against-Humanity-style topic transitions within a sentence, we demonstrate that our model can perform controlled text generation in a more flexible way than existing methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11975](https://arxiv.org/abs/1905.11975)

##### PDF
[https://arxiv.org/pdf/1905.11975](https://arxiv.org/pdf/1905.11975)

