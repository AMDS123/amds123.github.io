---
layout: post
title: "End-to-end losses based on speaker basis vectors and all-speaker hard negative mining for speaker verification"
date: 2019-02-07 02:55:02
categories: arXiv_SD
tags: arXiv_SD Embedding
author: Hee-Soo Heo, Jee-weon Jung, IL-Ho Yang, Sung-Hyun Yoon, Hye-jin Shim, Ha-Jin Yu
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, speaker verification has been primarily performed using deep neural networks that are trained to output embeddings from input features such as spectrograms or filterbank energies. Therefore, studies have been conducted to design various loss functions, including metric learning, to train deep neural networks to make them suitable for speaker verification. We propose end-to-end loss functions for speaker verification using speaker bases, which are trainable parameters. We expect that each speaker basis will represent the corresponding speaker in the process of training deep neural networks. Conventional loss functions can only consider a limited number of speakers that are included in a mini-batch. In contrast, as the proposed loss functions are based on speaker bases, each sample can be compared against all speakers regardless of mini-batch composition. Through a speaker verification experiment performed using the VoxCeleb 1, we confirmed that the proposed loss functions could increase between-speaker variations and perform hard negative mining for each mini-batch. In particular, it was shown that the system trained through the proposed loss functions had an equal error rate of 5.55%. In addition, the proposed loss functions reduced errors by approximately 15% compared with the system trained with the conventional center loss function.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02455](http://arxiv.org/abs/1902.02455)

##### PDF
[http://arxiv.org/pdf/1902.02455](http://arxiv.org/pdf/1902.02455)

