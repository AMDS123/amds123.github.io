---
layout: post
title: "Less Memory, Faster Speed: Refining Self-Attention Module for Image Reconstruction"
date: 2019-05-20 11:43:37
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN
author: Zheng Wang, Jianwu Li, Ge Song, Tieling Li
mathjax: true
---

* content
{:toc}

##### Abstract
Self-attention (SA) mechanisms can capture effectively global dependencies in deep neural networks, and have been applied to natural language processing and image processing successfully. However, SA modules for image reconstruction have high time and space complexity, which restrict their applications to higher-resolution images. In this paper, we refine the SA module in self-attention generative adversarial networks (SAGAN) via adapting a non-local operation, revising the connectivity among the units in SA module and re-implementing its computational pattern, such that its time and space complexity is reduced from $\text{O}(n^2)$ to $\text{O}(n)$, but it is still equivalent to the original SA module. Further, we explore the principles behind the module and discover that our module is a special kind of channel attention mechanisms. Experimental results based on two benchmark datasets of image reconstruction, verify that under the same computational environment, two models can achieve comparable effectiveness for image reconstruction, but the proposed one runs faster and takes up less memory space.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08008](http://arxiv.org/abs/1905.08008)

##### PDF
[http://arxiv.org/pdf/1905.08008](http://arxiv.org/pdf/1905.08008)

