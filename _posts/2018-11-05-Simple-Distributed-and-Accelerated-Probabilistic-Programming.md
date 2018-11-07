---
layout: post
title: "Simple, Distributed, and Accelerated Probabilistic Programming"
date: 2018-11-05 23:53:59
categories: arXiv_AI
tags: arXiv_AI Embedding Deep_Learning
author: Dustin Tran, Matthew Hoffman, Dave Moore, Christopher Suter, Srinivas Vasudevan, Alexey Radul, Matthew Johnson, Rif A. Saurous
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a simple, low-level approach for embedding probabilistic programming in a deep learning ecosystem. In particular, we distill probabilistic programming down to a single abstraction---the random variable. Our lightweight implementation in TensorFlow enables numerous applications: a model-parallel variational auto-encoder (VAE) with 2nd-generation tensor processing units (TPUv2s); a data-parallel autoregressive model (Image Transformer) with TPUv2s; and multi-GPU No-U-Turn Sampler (NUTS). For both a state-of-the-art VAE on 64x64 ImageNet and Image Transformer on 256x256 CelebA-HQ, our approach achieves an optimal linear speedup from 1 to 256 TPUv2 chips. With NUTS, we see a 100x speedup on GPUs over Stan and 37x over PyMC3.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.02091](https://arxiv.org/abs/1811.02091)

##### PDF
[https://arxiv.org/pdf/1811.02091](https://arxiv.org/pdf/1811.02091)

