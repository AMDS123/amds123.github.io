---
layout: post
title: "Bayesian Optimization on Large Graphs via a Graph Convolutional Generative Model: Application in Cardiac Model Personalization"
date: 2019-07-01 17:47:21
categories: arXiv_CV
tags: arXiv_CV Knowledge GAN CNN Optimization
author: Jwala Dhamala, Sandesh Ghimire, John L. Sapp, B. Milan Horacek, Linwei Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Personalization of cardiac models involves the optimization of organ tissue properties that vary spatially over the non-Euclidean geometry model of the heart. To represent the high-dimensional (HD) unknown of tissue properties, most existing works rely on a low-dimensional (LD) partitioning of the geometrical model. While this exploits the geometry of the heart, it is of limited expressiveness to allow partitioning that is small enough for effective optimization. Recently, a variational auto-encoder (VAE) was utilized as a more expressive generative model to embed the HD optimization into the LD latent space. Its Euclidean nature, however, neglects the rich geometrical information in the heart. In this paper, we present a novel graph convolutional VAE to allow generative modeling of non-Euclidean data, and utilize it to embed Bayesian optimization of large graphs into a small latent space. This approach bridges the gap of previous works by introducing an expressive generative model that is able to incorporate the knowledge of spatial proximity and hierarchical compositionality of the underlying geometry. It further allows transferring of the learned features across different geometries, which was not possible with a regular VAE. We demonstrate these benefits of the presented method in synthetic and real data experiments of estimating tissue excitability in a cardiac electrophysiological model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01406](http://arxiv.org/abs/1907.01406)

##### PDF
[http://arxiv.org/pdf/1907.01406](http://arxiv.org/pdf/1907.01406)

