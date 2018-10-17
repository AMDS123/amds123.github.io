---
layout: post
title: "Penetrating the Fog: the Path to Efficient CNN Models"
date: 2018-10-11 00:40:37
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Kun Wan, Boyuan Feng, Shu Yang, Yufei Ding
mathjax: true
---

* content
{:toc}

##### Abstract
With the increasing demand to deploy convolutional neural networks (CNNs) on mobile platforms, the sparse kernel approach was proposed, which could save more parameters than the standard convolution while maintaining accuracy. However, despite the great potential, no prior research has pointed out how to craft an sparse kernel design with such potential (i.e., effective design), and all prior works just adopt simple combinations of existing sparse kernels such as group convolution. Meanwhile due to the large design space it is also impossible to try all combinations of existing sparse kernels. In this paper, we are the first in the field to consider how to craft an effective sparse kernel design by eliminating the large design space. Specifically, we present a sparse kernel scheme to illustrate how to reduce the space from three aspects. First, in terms of composition we remove designs composed of repeated layers. Second, to remove designs with large accuracy degradation, we find an unified property named information field behind various sparse kernel designs, which could directly indicate the final accuracy. Last, we remove designs in two cases where a better parameter efficiency could be achieved. Additionally, we provide detailed efficiency analysis on the final four designs in our scheme. Experimental results validate the idea of our scheme by showing that our scheme is able to find designs which are more efficient in using parameters and computation with similar or higher accuracy.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.04231](https://arxiv.org/abs/1810.04231)

##### PDF
[https://arxiv.org/pdf/1810.04231](https://arxiv.org/pdf/1810.04231)

