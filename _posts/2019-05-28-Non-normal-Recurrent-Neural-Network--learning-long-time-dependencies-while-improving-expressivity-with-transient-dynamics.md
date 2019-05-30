---
layout: post
title: "Non-normal Recurrent Neural Network : learning long time dependencies while improving expressivity with transient dynamics"
date: 2019-05-28 20:41:27
categories: arXiv_AI
tags: arXiv_AI RNN
author: Giancarlo Kerg, Kyle Goyette, Maximilian Puelma Touzel, Gauthier Gidel, Eugene Vorontsov, Yoshua Bengio, Guillaume Lajoie
mathjax: true
---

* content
{:toc}

##### Abstract
A recent strategy to circumvent the exploding and vanishing gradient problem in RNNs, and to allow the stable propagation of signals over long time scales, is to constrain recurrent connectivity matrices to be orthogonal or unitary. This ensures eigenvalues with unit norm and thus stable dynamics and training. However this comes at the cost of reduced expressivity due to the limited variety of orthogonal transformations. We propose a novel connectivity structure based on the Schur decomposition and a splitting of the Schur form into normal and non-normal parts. This allows to parametrize matrices with unit-norm eigenspectra without orthogonality constraints on eigenbases. The resulting architecture ensures access to a larger space of spectrally constrained matrices, of which orthogonal matrices are a subset. This crucial difference retains the stability advantages and training speed of orthogonal RNNs while enhancing expressivity, especially on tasks that require computations over ongoing input sequences.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12080](http://arxiv.org/abs/1905.12080)

##### PDF
[http://arxiv.org/pdf/1905.12080](http://arxiv.org/pdf/1905.12080)

