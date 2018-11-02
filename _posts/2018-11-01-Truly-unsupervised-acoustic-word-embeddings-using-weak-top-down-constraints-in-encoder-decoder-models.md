---
layout: post
title: "Truly unsupervised acoustic word embeddings using weak top-down constraints in encoder-decoder models"
date: 2018-11-01 14:17:01
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Herman Kamper
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate unsupervised models that can map a variable-duration speech segment to a fixed-dimensional representation. In settings where unlabelled speech is the only available resource, such acoustic word embeddings can form the basis for "zero-resource" speech search, discovery and indexing systems. Most existing unsupervised embedding methods still use some supervision, such as word or phoneme boundaries. Here we propose the encoder-decoder correspondence autoencoder (EncDec-CAE), which, instead of true word segments, uses automatically discovered segments: an unsupervised term discovery system finds pairs of words of the same unknown type, and the EncDec-CAE is trained to reconstruct one word given the other as input. We compare it to a standard encoder-decoder autoencoder (AE), a variational AE with a prior over its latent embedding, and downsampling. EncDec-CAE outperforms its closest competitor by 24% relative in average precision on two languages in a word discrimination task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00403](http://arxiv.org/abs/1811.00403)

##### PDF
[http://arxiv.org/pdf/1811.00403](http://arxiv.org/pdf/1811.00403)

