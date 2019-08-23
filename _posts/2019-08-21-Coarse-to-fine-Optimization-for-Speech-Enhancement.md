---
layout: post
title: "Coarse-to-fine Optimization for Speech Enhancement"
date: 2019-08-21 17:51:29
categories: arXiv_SD
tags: arXiv_SD Adversarial GAN Optimization Prediction
author: Jian Yao, Ahmad Al-Dahle
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose the coarse-to-fine optimization for the task of speech enhancement. Cosine similarity loss [1] has proven to be an effective metric to measure similarity of speech signals. However, due to the large variance of the enhanced speech with even the same cosine similarity loss in high dimensional space, a deep neural network learnt with this loss might not be able to predict enhanced speech with good quality. Our coarse-to-fine strategy optimizes the cosine similarity loss for different granularities so that more constraints are added to the prediction from high dimension to relatively low dimension. In this way, the enhanced speech will better resemble the clean speech. Experimental results show the effectiveness of our proposed coarse-to-fine optimization in both discriminative models and generative models. Moreover, we apply the coarse-to-fine strategy to the adversarial loss in generative adversarial network (GAN) and propose dynamic perceptual loss, which dynamically computes the adversarial loss from coarse resolution to fine resolution. Dynamic perceptual loss further improves the accuracy and achieves state-of-the-art results compared with other generative models.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.08044](https://arxiv.org/abs/1908.08044)

##### PDF
[https://arxiv.org/pdf/1908.08044](https://arxiv.org/pdf/1908.08044)

