---
layout: post
title: "Adversarial Text Generation Without Reinforcement Learning"
date: 2018-10-11 22:50:38
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN Text_Generation Reinforcement_Learning
author: David Donahue, Anna Rumshisky
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) have experienced a recent surge in popularity, performing competitively in a variety of tasks, especially in computer vision. However, GAN training has shown limited success in natural language processing. This is largely because sequences of text are discrete, and thus gradients cannot propagate from the discriminator to the generator. Recent solutions use reinforcement learning to propagate approximate gradients to the generator, but this is inefficient to train. We propose to utilize an autoencoder to learn a low-dimensional representation of sentences. A GAN is then trained to generate its own vectors in this space, which decode to realistic utterances. We report both random and interpolated samples from the generator. Visualization of sentence vectors indicate our model correctly learns the latent space of the autoencoder. Both human ratings and BLEU scores show that our model generates realistic text against competitive baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.06640](http://arxiv.org/abs/1810.06640)

##### PDF
[http://arxiv.org/pdf/1810.06640](http://arxiv.org/pdf/1810.06640)

