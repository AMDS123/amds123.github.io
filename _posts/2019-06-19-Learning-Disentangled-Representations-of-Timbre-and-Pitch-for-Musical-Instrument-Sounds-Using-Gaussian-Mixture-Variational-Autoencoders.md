---
layout: post
title: "Learning Disentangled Representations of Timbre and Pitch for Musical Instrument Sounds Using Gaussian Mixture Variational Autoencoders"
date: 2019-06-19 15:25:29
categories: arXiv_SD
tags: arXiv_SD Classification Quantitative
author: Yin-Jyun Luo, Kat Agres, Dorien Herremans
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we learn disentangled representations of timbre and pitch for musical instrument sounds. We adapt a framework based on variational autoencoders with Gaussian mixture latent distributions. Specifically, we use two separate encoders to learn distinct latent spaces for timbre and pitch, which form Gaussian mixture components representing instrument identity and pitch, respectively. For reconstruction, latent variables of timbre and pitch are sampled from corresponding mixture components, and are concatenated as the input to a decoder. We show the model efficacy by latent space visualization, and a quantitative analysis indicates the discriminability of these spaces, even with a limited number of instrument labels for training. The model allows for controllable synthesis of selected instrument sounds by sampling from the latent spaces. To evaluate this, we trained instrument and pitch classifiers using original labeled data. These classifiers achieve high accuracy when tested on our synthesized sounds, which verifies the model performance of controllable realistic timbre and pitch synthesis. Our model also enables timbre transfer between multiple instruments, with a single autoencoder architecture, which is evaluated by measuring the shift in posterior of instrument classification. Our in depth evaluation confirms the model ability to successfully disentangle timbre and pitch.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08152](http://arxiv.org/abs/1906.08152)

##### PDF
[http://arxiv.org/pdf/1906.08152](http://arxiv.org/pdf/1906.08152)

