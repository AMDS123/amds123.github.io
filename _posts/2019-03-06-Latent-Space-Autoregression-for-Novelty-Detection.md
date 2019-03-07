---
layout: post
title: "Latent Space Autoregression for Novelty Detection"
date: 2019-03-06 09:53:59
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Davide Abati, Angelo Porrello, Simone Calderara, Rita Cucchiara
mathjax: true
---

* content
{:toc}

##### Abstract
Novelty detection is commonly referred to as the discrimination of observations that do not conform to a learned model of regularity. Despite its importance in different application settings, designing a novelty detector is utterly complex due to the unpredictable nature of novelties and its inaccessibility during the training procedure, factors which expose the unsupervised nature of the problem. In our proposal, we design a general framework where we equip a deep autoencoder with a parametric density estimator that learns the probability distribution underlying its latent representations through an autoregressive procedure. We show that a maximum likelihood objective, optimized in conjunction with the reconstruction of normal samples, effectively acts as a regularizer for the task at hand, by minimizing the differential entropy of the distribution spanned by latent vectors. In addition to providing a very general formulation, extensive experiments of our model on publicly available datasets deliver on-par or superior performances if compared to state-of-the-art methods in one-class and video anomaly detection settings. Differently from prior works, our proposal does not make any assumption about the nature of the novelties, making our work readily applicable to diverse contexts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.01653](http://arxiv.org/abs/1807.01653)

##### PDF
[http://arxiv.org/pdf/1807.01653](http://arxiv.org/pdf/1807.01653)

