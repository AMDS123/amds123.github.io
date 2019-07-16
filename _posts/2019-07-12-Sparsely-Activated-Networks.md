---
layout: post
title: "Sparsely Activated Networks"
date: 2019-07-12 08:01:47
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: Paschalis Bizopoulos, Dimitrios Koutsouris
mathjax: true
---

* content
{:toc}

##### Abstract
Previous literature on unsupervised learning focused on designing structural priors and optimization functions with the aim of learning meaningful features, but without considering the description length of the representations. Here we present Sparsely Activated Networks (SANs), which decompose their input as a sum of sparsely reoccurring patterns of varying amplitude, and combined with a newly proposed metric $\varphi$ they learn representations with minimal description lengths. SANs consist of kernels with shared weights that during encoding are convolved with the input and then passed through a ReLU and a sparse activation function. During decoding, the same weights are convolved with the sparse activation map and the individual reconstructions from each weight are summed to reconstruct the input. We also propose a metric $\varphi$ for model selection that favors models which combine high compression ratio and low reconstruction error and we justify its definition by exploring the hyperparameter space of SANs. We compare four sparse activation functions (Identity, Max-Activations, Max-Pool indices, Peaks) on a variety of datasets and show that SANs learn interpretable kernels that combined with $\varphi$, they minimize the description length of the representations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06592](http://arxiv.org/abs/1907.06592)

##### PDF
[http://arxiv.org/pdf/1907.06592](http://arxiv.org/pdf/1907.06592)

