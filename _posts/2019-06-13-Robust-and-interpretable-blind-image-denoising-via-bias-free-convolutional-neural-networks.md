---
layout: post
title: "Robust and interpretable blind image denoising via bias-free convolutional neural networks"
date: 2019-06-13 04:48:21
categories: arXiv_CV
tags: arXiv_CV CNN
author: Sreyas Mohan, Zahra Kadkhodaie, Eero P. Simoncelli, Carlos Fernandez-Granda
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional networks often append additive constant ("bias") terms to their convolution operations, enabling a richer repertoire of functional mappings. Biases are also used to facilitate training, by subtracting mean response over batches of training images (a component of "batch normalization"). Recent state-of-the-art blind denoising methods (e.g., DnCNN) seem to require these terms for their success. Here, however, we show that these networks systematically overfit the noise levels for which they are trained: when deployed at noise levels outside the training range, performance degrades dramatically. In contrast, a bias-free architecture -- obtained by removing the constant terms in every layer of the network, including those used for batch normalization-- generalizes robustly across noise levels, while preserving state-of-the-art performance within the training range. Locally, the bias-free network acts linearly on the noisy image, enabling direct analysis of network behavior via standard linear-algebraic tools. These analyses provide interpretations of network functionality in terms of nonlinear adaptive filtering, and projection onto a union of low-dimensional subspaces, connecting the learning-based method to more traditional denoising methodology.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05478](https://arxiv.org/abs/1906.05478)

##### PDF
[https://arxiv.org/pdf/1906.05478](https://arxiv.org/pdf/1906.05478)

