---
layout: post
title: "Generative approach to unsupervised deep local learning"
date: 2019-06-28 07:54:52
categories: arXiv_CV
tags: arXiv_CV Embedding CNN
author: Changlu Chen, Chaoxi Niu, Xia Zhan, Kun Zhan
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing feature learning methods optimize inflexible handcrafted features and the affinity matrix is constructed by shallow linear embedding methods. Different from these conventional methods, we pretrain a generative neural network by stacking convolutional autoencoders to learn the latent data representation and then construct an affinity graph with them as a prior. Based on the pretrained model and the constructed graph, we add a self-expressive layer to complete the generative model and then fine-tune it with a new loss function, including the reconstruction loss and a deliberately defined locality-preserving loss. The locality-preserving loss designed by the constructed affinity graph serves as prior to preserve the local structure during the fine-tuning stage, which in turn improves the quality of feature representation effectively. Furthermore, the self-expressive layer between the encoder and decoder is based on the assumption that each latent feature is a linear combination of other latent features, so the weighted combination coefficients of the self-expressive layer are used to construct a new refined affinity graph for representing the data structure. We conduct experiments on four datasets to demonstrate the superiority of the representation ability of our proposed model over the state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07947](http://arxiv.org/abs/1906.07947)

##### PDF
[http://arxiv.org/pdf/1906.07947](http://arxiv.org/pdf/1906.07947)

