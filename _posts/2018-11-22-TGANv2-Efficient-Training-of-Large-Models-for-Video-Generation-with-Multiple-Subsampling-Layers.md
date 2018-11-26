---
layout: post
title: "TGANv2: Efficient Training of Large Models for Video Generation with Multiple Subsampling Layers"
date: 2018-11-22 17:31:26
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Masaki Saito, Shunta Saito
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel method to efficiently train a Generative Adversarial Network (GAN) on high dimensional samples. The key idea is to introduce a differentiable subsampling layer which appropriately reduces the dimensionality of intermediate feature maps in the generator during training. In general, generators require large memory and computational costs in the latter stages of the network as the feature maps become larger, though the latter stages have relatively fewer parameters than the earlier stages. It makes training large models for video generation difficult due to the limited computational resource. We solve this problem by introducing a method that gradually reduces the dimensionality of feature maps in the generator with multiple subsampling layers. We also propose a network (Temporal GAN v2) with such layers and perform video generation experiments. As a consequence, our model trained on the UCF101 dataset at $192 \times 192$ pixels achieves an Inception Score (IS) of 24.34, which shows a significant improvement over the previous state-of-the-art score of 14.56.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09245](http://arxiv.org/abs/1811.09245)

##### PDF
[http://arxiv.org/pdf/1811.09245](http://arxiv.org/pdf/1811.09245)

