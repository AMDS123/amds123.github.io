---
layout: post
title: "Learning Speaker Representations with Mutual Information"
date: 2018-12-01 21:48:28
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN Optimization Deep_Learning
author: Mirco Ravanelli, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Learning good representations is of crucial importance in deep learning. Mutual Information (MI) or similar measures of statistical dependence are promising tools for learning these representations in an unsupervised way. Even though the mutual information between two random variables is hard to measure directly in high dimensional spaces, some recent studies have shown that an implicit optimization of MI can be achieved with an encoder-discriminator architecture similar to that of Generative Adversarial Networks (GANs). In this work, we learn representations that capture speaker identities by maximizing the mutual information between the encoded representations of chunks of speech randomly sampled from the same sentence. The proposed encoder relies on the SincNet architecture and transforms raw speech waveform into a compact feature vector. The discriminator is fed by either positive samples (of the joint distribution of encoded chunks) or negative samples (from the product of the marginals) and is trained to separate them. We report experiments showing that this approach effectively learns useful speaker representations, leading to promising results on speaker identification and verification tasks. Our experiments consider both unsupervised and semi-supervised settings and compare the performance achieved with different objective functions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00271](http://arxiv.org/abs/1812.00271)

##### PDF
[http://arxiv.org/pdf/1812.00271](http://arxiv.org/pdf/1812.00271)

