---
layout: post
title: "Inspirational Adversarial Image Generation"
date: 2019-06-17 06:52:40
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN Face Optimization Gradient_Descent
author: Morgane Riviere, Olivier Teytaud, J&#xe9;r&#xe9;my Rapin, Yann LeCun, Camille Couprie
mathjax: true
---

* content
{:toc}

##### Abstract
The task of image generation started to receive some attention from artists and designers to inspire them in new creations. However, exploiting the results of deep generative models such as Generative Adversarial Networks can be long and tedious given the lack of existing tools. In this work, we propose a simple strategy to inspire creators with new generations learned from a dataset of their choice, while providing some control on them. We design a simple optimization method to find the optimal latent parameters corresponding to the closest generation to any input inspirational image. Specifically, we allow the generation given an inspirational image of the user choice by performing several optimization steps to recover optimal parameters from the model's latent space. We tested several exploration methods starting with classic gradient descents to gradient-free optimizers. Many gradient-free optimizers just need comparisons (better/worse than another image), so that they can even be used without numerical criterion, without inspirational image, but with only with human preference. Thus, by iterating on one's preferences we could make robust Facial Composite or Fashion Generation algorithms. High resolution of the produced design generations are obtained using progressive growing of GANs. Our results on four datasets of faces, fashion images, and textures show that satisfactory images are effectively retrieved in most cases.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11661](http://arxiv.org/abs/1906.11661)

##### PDF
[http://arxiv.org/pdf/1906.11661](http://arxiv.org/pdf/1906.11661)

