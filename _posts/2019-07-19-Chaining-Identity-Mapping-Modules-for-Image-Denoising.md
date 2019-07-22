---
layout: post
title: "Chaining Identity Mapping Modules for Image Denoising"
date: 2019-07-19 01:35:32
categories: arXiv_CV
tags: arXiv_CV CNN
author: Saeed Anwar, Cong Phouc Huynh, Fatih Porikli
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to learn a fully-convolutional network model that consists of a Chain of Identity Mapping Modules (CIMM) for image denoising. The CIMM structure possesses two distinctive features that are important for the noise removal task. Firstly, each residual unit employs identity mappings as the skip connections and receives pre-activated input in order to preserve the gradient magnitude propagated in both the forward and backward directions. Secondly, by utilizing dilated kernels for the convolution layers in the residual branch, in other words within an identity mapping module, each neuron in the last convolution layer can observe the full receptive field of the first layer. After being trained on the BSD400 dataset, the proposed network produces remarkably higher numerical accuracy and better visual image quality than the state-of-the-art when being evaluated on conventional benchmark images and the BSD68 dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.02933](http://arxiv.org/abs/1712.02933)

##### PDF
[http://arxiv.org/pdf/1712.02933](http://arxiv.org/pdf/1712.02933)

