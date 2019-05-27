---
layout: post
title: "SCRAM: Spatially Coherent Randomized Attention Maps"
date: 2019-05-24 16:03:44
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Attention Deep_Learning
author: Dan A. Calian, Peter Roelants, Jacques Cali, Ben Carr, Krishna Dubba, John E. Reid, Dell Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Attention mechanisms and non-local mean operations in general are key ingredients in many state-of-the-art deep learning techniques. In particular, the Transformer model based on multi-head self-attention has recently achieved great success in natural language processing and computer vision. However, the vanilla algorithm computing the Transformer of an image with n pixels has O(n^2) complexity, which is often painfully slow and sometimes prohibitively expensive for large-scale image data. In this paper, we propose a fast randomized algorithm --- SCRAM --- that only requires O(n log(n)) time to produce an image attention map. Such a dramatic acceleration is attributed to our insight that attention maps on real-world images usually exhibit (1) spatial coherence and (2) sparse structure. The central idea of SCRAM is to employ PatchMatch, a randomized correspondence algorithm, to quickly pinpoint the most compatible key (argmax) for each query first, and then exploit that knowledge to design a sparse approximation to non-local mean operations. Using the argmax (mode) to dynamically construct the sparse approximation distinguishes our algorithm from all of the existing sparse approximate methods and makes it very efficient. Moreover, SCRAM is a broadly applicable approximation to any non-local mean layer in contrast to some other sparse approximations that can only approximate self-attention. Our preliminary experimental results suggest that SCRAM is indeed promising for speeding up or scaling up the computation of attention maps in the Transformer.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10308](http://arxiv.org/abs/1905.10308)

##### PDF
[http://arxiv.org/pdf/1905.10308](http://arxiv.org/pdf/1905.10308)

