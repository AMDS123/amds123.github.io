---
layout: post
title: "Variational Recurrent Neural Machine Translation"
date: 2018-01-16 05:18:06
categories: arXiv_CL
tags: arXiv_CL NMT Inference RNN
author: Jinsong Su, Shan Wu, Deyi Xiong, Yaojie Lu, Xianpei Han, Biao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Partially inspired by successful applications of variational recurrent neural networks, we propose a novel variational recurrent neural machine translation (VRNMT) model in this paper. Different from the variational NMT, VRNMT introduces a series of latent random variables to model the translation procedure of a sentence in a generative way, instead of a single latent variable. Specifically, the latent random variables are included into the hidden states of the NMT decoder with elements from the variational autoencoder. In this way, these variables are recurrently generated, which enables them to further capture strong and complex dependencies among the output translations at different timesteps. In order to deal with the challenges in performing efficient posterior inference and large-scale training during the incorporation of latent variables, we build a neural posterior approximator, and equip it with a reparameterization technique to estimate the variational lower bound. Experiments on Chinese-English and English-German translation tasks demonstrate that the proposed model achieves significant improvements over both the conventional and variational NMT models.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1801.05119](https://arxiv.org/abs/1801.05119)

##### PDF
[https://arxiv.org/pdf/1801.05119](https://arxiv.org/pdf/1801.05119)

