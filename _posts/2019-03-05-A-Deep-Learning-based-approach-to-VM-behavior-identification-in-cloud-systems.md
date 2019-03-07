---
layout: post
title: "A Deep Learning based approach to VM behavior identification in cloud systems"
date: 2019-03-05 16:49:00
categories: arXiv_AI
tags: arXiv_AI CNN Classification Deep_Learning
author: Matteo Stefanini, Riccardo Lancellotti, Lorenzo Baraldi, Simone Calderara
mathjax: true
---

* content
{:toc}

##### Abstract
Cloud computing data centers are growing in size and complexity to the point where monitoring and management of the infrastructure become a challenge due to scalability issues. A possible approach to cope with the size of such data centers is to identify VMs exhibiting a similar behavior. Existing literature demonstrated that clustering together VMs that show a similar behavior may improve the scalability of both monitoring andmanagement of a data center. However, available techniques suffer from a trade-off between accuracy and time to achieve this result. Throughout this paper we propose a different approach where, instead of an unsupervised clustering, we rely on classifiers based on deep learning techniques to assigna newly deployed VMs to a cluster of already-known VMs. The two proposed classifiers, namely DeepConv and DeepFFT use a convolution neural network and (in the latter model) exploits Fast Fourier Transformation to classify the VMs. Our proposal is validated using a set of traces describing the behavior of VMs from a realcloud data center. The experiments compare our proposal with state-of-the-art solutions available in literature, demonstrating that our proposal achieve better performance. Furthermore, we show that our solution issignificantly faster than the alternatives as it can produce a perfect classification even with just a few samples of data, making our proposal viable also toclassify on-demand VMs that are characterized by a short life span.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.01930](http://arxiv.org/abs/1903.01930)

##### PDF
[http://arxiv.org/pdf/1903.01930](http://arxiv.org/pdf/1903.01930)

