---
layout: post
title: "Bidirectional One-Shot Unsupervised Domain Mapping"
date: 2019-09-04 07:49:18
categories: arXiv_CV
tags: arXiv_CV
author: Tomer Cohen, Lior Wolf
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of mapping between a domain $A$, in which there is a single training sample and a domain $B$, for which we have a richer training set. The method we present is able to perform this mapping in both directions. For example, we can transfer all MNIST images to the visual domain captured by a single SVHN image and transform the SVHN image to the domain of the MNIST images. Our method is based on employing one encoder and one decoder for each domain, without utilizing weight sharing. The autoencoder of the single sample domain is trained to match both this sample and the latent space of domain $B$. Our results demonstrate convincing mapping between domains, where either the source or the target domain are defined by a single sample, far surpassing existing solutions. Our code is made publicly available at https://github.com/tomercohen11/BiOST

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01595](http://arxiv.org/abs/1909.01595)

##### PDF
[http://arxiv.org/pdf/1909.01595](http://arxiv.org/pdf/1909.01595)

