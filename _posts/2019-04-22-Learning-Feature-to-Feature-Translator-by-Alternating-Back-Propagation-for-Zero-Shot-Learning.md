---
layout: post
title: "Learning Feature-to-Feature Translator by Alternating Back-Propagation for Zero-Shot Learning"
date: 2019-04-22 20:30:21
categories: arXiv_CV
tags: arXiv_CV GAN
author: Yizhe Zhu, Jianwen Xie, Bingchen Liu, Ahmed Elgammal
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate learning feature-to-feature translator networks by alternating back-propagation as a general-purpose solution to zero-shot learning (ZSL) problems. Our method can be categorized to a generative model-based ZSL one. In contrast to the GAN or VAE that requires auxiliary networks to assist the training, our model consists of a single conditional generator that maps the class feature and a latent vector %accounting for randomness in the output to the image feature, and is trained by maximum likelihood estimation. The training process is a simple yet effective EM-like process that iterates the following two steps: (i) the inferential back-propagation to infer the latent noise vector of each observed data, and (ii) the learning back-propagation to update the parameters of the model. With slight modifications of our model, we also provide a solution to learning from incomplete visual features for ZSL. We conduct extensive comparisons with existing generative ZSL methods on five benchmarks, demonstrating the superiority of our method in not only performance but also convergence speed and computational cost. Specifically, our model outperforms the existing state-of-the-art methods by a remarkable margin up to $3.1\%$ and $4.0\%$ in ZSL and generalized ZSL settings, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10056](http://arxiv.org/abs/1904.10056)

##### PDF
[http://arxiv.org/pdf/1904.10056](http://arxiv.org/pdf/1904.10056)

