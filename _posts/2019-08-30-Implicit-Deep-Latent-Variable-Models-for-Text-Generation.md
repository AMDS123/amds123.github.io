---
layout: post
title: "Implicit Deep Latent Variable Models for Text Generation"
date: 2019-08-30 04:12:08
categories: arXiv_CL
tags: arXiv_CL Regularization Text_Generation Style_Transfer Language_Model
author: Le Fang, Chunyuan Li, Jianfeng Gao, Wen Dong, Changyou Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep latent variable models (LVM) such as variational auto-encoder (VAE) have recently played an important role in text generation. One key factor is the exploitation of smooth latent structures to guide the generation. However, the representation power of VAEs is limited due to two reasons: (1) the Gaussian assumption is often made on the variational posteriors; and meanwhile (2) a notorious "posterior collapse" issue occurs. In this paper, we advocate sample-based representations of variational distributions for natural language, leading to implicit latent features, which can provide flexible representation power compared with Gaussian-based posteriors. We further develop an LVM to directly match the aggregated posterior to the prior. It can be viewed as a natural extension of VAEs with a regularization of maximizing mutual information, mitigating the "posterior collapse" issue. We demonstrate the effectiveness and versatility of our models in various text generation scenarios, including language modeling, unaligned style transfer, and dialog response generation. The source code to reproduce our experimental results is available on GitHub.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11527](http://arxiv.org/abs/1908.11527)

##### PDF
[http://arxiv.org/pdf/1908.11527](http://arxiv.org/pdf/1908.11527)

