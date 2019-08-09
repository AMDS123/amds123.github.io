---
layout: post
title: "One Model To Rule Them All"
date: 2019-08-08 11:07:22
categories: arXiv_AI
tags: arXiv_AI Classification
author: Felix Berkhahn, Richard Keys, Wajih Ouertani, Nikhil Shetty, Dominik Gei&#xdf;ler
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new flavor of Variational Autoencoder (VAE) that interpolates seamlessly between unsupervised, semi-supervised and fully supervised learning domains. We show that unlabeled datapoints not only boost unsupervised tasks, but also the classification performance. Vice versa, every label not only improves classification, but also unsupervised tasks. The proposed architecture is simple: A classification layer is connected to the topmost encoder layer, and then combined with the resampled latent layer for the decoder. The usual evidence lower bound (ELBO) loss is supplemented with a supervised loss target on this classification layer that is only applied for labeled datapoints. This simplicity allows for extending any existing VAE model to our proposed semi-supervised framework with minimal effort. In the context of classification, we found that this approach even outperforms a direct supervised setup.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.03015](http://arxiv.org/abs/1908.03015)

##### PDF
[http://arxiv.org/pdf/1908.03015](http://arxiv.org/pdf/1908.03015)

