---
layout: post
title: "5 Parallel Prism: A topology for pipelined implementations of convolutional neural networks using computational memory"
date: 2019-06-08 15:19:03
categories: arXiv_CV
tags: arXiv_CV CNN Inference Quantitative
author: Martino Dazzi, Abu Sebastian, Pier Andrea Francese, Thomas Parnell, Luca Benini, Evangelos Eleftheriou
mathjax: true
---

* content
{:toc}

##### Abstract
In-memory computing is an emerging computing paradigm that could enable deeplearning inference at significantly higher energy efficiency and reduced latency. The essential idea is to map the synaptic weights corresponding to each layer to one or more computational memory (CM) cores. During inference, these cores perform the associated matrix-vector multiply operations in place with O(1) time complexity, thus obviating the need to move the synaptic weights to an additional processing unit. Moreover, this architecture could enable the execution of these networks in a highly pipelined fashion. However, a key challenge is to design an efficient communication fabric for the CM cores. Here, we present one such communication fabric based on a graph topology that is well suited for the widely successful convolutional neural networks (CNNs). We show that this communication fabric facilitates the pipelined execution of all state of-the-art CNNs by proving the existence of a homomorphism between one graph representation of these networks and the proposed graph topology. We then present a quantitative comparison with established communication topologies and show that our proposed topology achieves the lowest bandwidth requirements per communication channel. Finally, we present a concrete example of mapping ResNet-32 onto an array of CM cores.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.03474](https://arxiv.org/abs/1906.03474)

##### PDF
[https://arxiv.org/pdf/1906.03474](https://arxiv.org/pdf/1906.03474)

