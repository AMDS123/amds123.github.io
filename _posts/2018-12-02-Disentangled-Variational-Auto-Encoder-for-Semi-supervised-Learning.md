---
layout: post
title: "Disentangled Variational Auto-Encoder for Semi-supervised Learning"
date: 2018-12-02 07:42:21
categories: arXiv_AI
tags: arXiv_AI Attention Reinforcement_Learning
author: Yang Li, Quan Pan, Suhang Wang, Haiyun Peng, Tao Yang, Erik Cambria
mathjax: true
---

* content
{:toc}

##### Abstract
Semi-supervised learning is attracting increasing attention due to the fact that datasets of many domains lack enough labeled data. Variational Auto-Encoder (VAE), in particular, has demonstrated the benefits of semi-supervised learning. The majority of existing semi-supervised VAEs utilize a classifier to exploit label information, where the parameters of the classifier are introduced to the VAE. Given the limited labeled data, learning the parameters for the classifiers may not be an optimal solution for exploiting label information. Therefore, in this paper, we develop a novel approach for semi-supervised VAE without classifier. Specifically, we propose a new model called Semi-supervised Disentangled VAE (SDVAE), which encodes the input data into disentangled representation and non-interpretable representation, then the category information is directly utilized to regularize the disentangled representation via the equality constraint. To further enhance the feature learning ability of the proposed VAE, we incorporate reinforcement learning to relieve the lack of data. The dynamic framework is capable of dealing with both image and text data with its corresponding encoder and decoder networks. Extensive experiments on image and text datasets demonstrate the effectiveness of the proposed framework.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1709.05047](http://arxiv.org/abs/1709.05047)

##### PDF
[http://arxiv.org/pdf/1709.05047](http://arxiv.org/pdf/1709.05047)

