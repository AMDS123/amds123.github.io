---
layout: post
title: "A Classification Supervised Auto-Encoder Based on Predefined Evenly-Distributed Class Centroids"
date: 2019-02-01 08:26:47
categories: arXiv_CV
tags: arXiv_CV Classification Gradient_Descent
author: Qiuyu Zhu, Ruixin Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Classic Autoencoders and variational autoencoders are used to learn complex data distributions, that are built on standard function approximators, such as neural networks, which can be trained by stochastic gradient descent methods. Especially, VAE has shown promise on a lot of complex task. In this paper, a new autoencoder model - classification supervised autoencoder (CSAE) based on predefined evenly-distributed class centroids (PEDCC) is proposed. To carry out the supervised learning for autoencoder, we use PEDCC of latent variables to train the network to ensure the maximization of inter-class distance and the minimization of inner-class distance. Instead of learning mean/variance of latent variables distribution and taking reparameterization of VAE, latent variables of CSAE are directly used to classify and as input of decoder. In addition, a new loss function is proposed to combine the loss function of classification, the loss function of image codec quality and the loss function for enhancing subjective quality of decoded image. Based on the basic structure of the universal autoencoder, we realized the comprehensive optimal results of encoding, decoding and classification, and good model generalization performance at the same time. Theoretical advantages are reflected in experimental results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.00220](http://arxiv.org/abs/1902.00220)

##### PDF
[http://arxiv.org/pdf/1902.00220](http://arxiv.org/pdf/1902.00220)

