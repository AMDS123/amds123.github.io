---
layout: post
title: "Conditional Adversarial Generative Flow for Controllable Image Synthesis"
date: 2019-04-03 05:58:01
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Rui Liu, Yu Liu, Xinyu Gong, Xiaogang Wang, Hongsheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
Flow-based generative models show great potential in image synthesis due to its reversible pipeline and exact log-likelihood target, yet it suffers from weak ability for conditional image synthesis, especially for multi-label or unaware conditions. This is because the potential distribution of image conditions is hard to measure precisely from its latent variable $z$. In this paper, based on modeling a joint probabilistic density of an image and its conditions, we propose a novel flow-based generative model named conditional adversarial generative flow (CAGlow). Instead of disentangling attributes from latent space, we blaze a new trail for learning an encoder to estimate the mapping from condition space to latent space in an adversarial manner. Given a specific condition $c$, CAGlow can encode it to a sampled $z$, and then enable robust conditional image synthesis in complex situations like combining person identity with multiple attributes. The proposed CAGlow can be implemented in both supervised and unsupervised manners, thus can synthesize images with conditional information like categories, attributes, and even some unknown properties. Extensive experiments show that CAGlow ensures the independence of different conditions and outperforms regular Glow to a significant extent.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.01782](https://arxiv.org/abs/1904.01782)

##### PDF
[https://arxiv.org/pdf/1904.01782](https://arxiv.org/pdf/1904.01782)

