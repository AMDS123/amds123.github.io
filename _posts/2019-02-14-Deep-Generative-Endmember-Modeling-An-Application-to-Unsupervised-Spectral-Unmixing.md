---
layout: post
title: "Deep Generative Endmember Modeling: An Application to Unsupervised Spectral Unmixing"
date: 2019-02-14 18:08:22
categories: arXiv_CV
tags: arXiv_CV
author: Ricardo Augusto Borsoi, Tales Imbiriba, Jos&#xe9; Carlos Moreira Bermudez
mathjax: true
---

* content
{:toc}

##### Abstract
Endmember (EM) spectral variability can greatly impact the performance of standard hyperspectral image analysis algorithms. Extended parametric models have been successfully applied to account for the EM spectral variability. However, these models still lack the compromise between flexibility and low-dimensional representation that is necessary to properly explore the fact that spectral variability is often confined to a low-dimensional manifold in real scenes. In this paper we propose to learn a spectral variability model directly form the observed data, instead of imposing it \emph{a priori}. This is achieved through a deep generative EM model, which is estimated using a variational autoencoder (VAE). The encoder and decoder that compose the generative model are trained using pure pixel information extracted directly from the observed image, what allows for an unsupervised formulation. The proposed EM model is applied to the solution of a spectral unmixing problem, which we cast as an alternating nonlinear least-squares problem that is solved iteratively with respect to the abundances and to the low-dimensional representations of the EMs in the latent space of the deep generative model. Simulations using both synthetic and real data indicate that the proposed strategy can outperform the competing state-of-the-art algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05528](http://arxiv.org/abs/1902.05528)

##### PDF
[http://arxiv.org/pdf/1902.05528](http://arxiv.org/pdf/1902.05528)

