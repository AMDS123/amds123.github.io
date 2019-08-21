---
layout: post
title: "Learning Feature-to-Feature Translator by Alternating Back-Propagation for Generative Zero-Shot Learning"
date: 2019-08-20 02:12:32
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Yizhe Zhu, Jianwen Xie, Bingchen Liu, Ahmed Elgammal
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate learning feature-to-feature translator networks by alternating back-propagation as a general-purpose solution to zero-shot learning (ZSL) problems. It is a generative model-based ZSL framework. In contrast to models based on generative adversarial networks (GAN) or variational autoencoders (VAE) that require auxiliary networks to assist the training, our model consists of a single conditional generator that maps class-level semantic features and Gaussian white noise vector accounting for instance-level latent factors to visual features, and is trained by maximum likelihood estimation. The training process is a simple yet effective alternating back-propagation process that iterates the following two steps: (i) the inferential back-propagation to infer the latent factors of each observed example, and (ii) the learning back-propagation to update the model parameters. We show that, with slight modifications, our model is capable of learning from incomplete visual features for ZSL. We conduct extensive comparisons with existing generative ZSL methods on five benchmarks, demonstrating the superiority of our method in not only ZSL performance but also convergence speed and computational cost. Specifically, our model outperforms the existing state-of-the-art methods by a remarkable margin up to 3.1% and 4.0% in ZSL and generalized ZSL settings, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10056](http://arxiv.org/abs/1904.10056)

##### PDF
[http://arxiv.org/pdf/1904.10056](http://arxiv.org/pdf/1904.10056)

