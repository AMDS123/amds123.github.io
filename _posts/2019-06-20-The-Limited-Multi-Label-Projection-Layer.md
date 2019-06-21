---
layout: post
title: "The Limited Multi-Label Projection Layer"
date: 2019-06-20 15:51:24
categories: arXiv_CV
tags: arXiv_CV Classification Prediction
author: Brandon Amos, Vladlen Koltun, J. Zico Kolter
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the Limited Multi-Label (LML) projection layer as a new primitive operation for end-to-end learning systems. The LML layer provides a probabilistic way of modeling multi-label predictions limited to having exactly k labels. We derive efficient forward and backward passes for this layer and show how the layer can be used to optimize the top-k recall for multi-label tasks with incomplete label information. We evaluate LML layers on top-k CIFAR-100 classification and scene graph generation. We show that LML layers add a negligible amount of computational overhead, strictly improve the model's representational capacity, and improve accuracy. We also revisit the truncated top-k entropy method as a competitive baseline for top-k classification.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08707](http://arxiv.org/abs/1906.08707)

##### PDF
[http://arxiv.org/pdf/1906.08707](http://arxiv.org/pdf/1906.08707)

