---
layout: post
title: "Parameter Compression of Recurrent Neural Networks and Degradation of Short-term Memory"
date: 2017-02-24 18:22:30
categories: arXiv_CV
tags: arXiv_CV CNN RNN
author: Jonathan A. Cox
mathjax: true
---

* content
{:toc}

##### Abstract
The significant computational costs of deploying neural networks in large-scale or resource constrained environments, such as data centers and mobile devices, has spurred interest in model compression, which can achieve a reduction in both arithmetic operations and storage memory. Several techniques have been proposed for reducing or compressing the parameters for feed-forward and convolutional neural networks, but less is understood about the effect of parameter compression on recurrent neural networks (RNN). In particular, the extent to which the recurrent parameters can be compressed and the impact on short-term memory performance, is not well understood. In this paper, we study the effect of complexity reduction, through singular value decomposition rank reduction, on RNN and minimal gated recurrent unit (MGRU) networks for several tasks. We show that considerable rank reduction is possible when compressing recurrent weights, even without fine tuning. Furthermore, we propose a perturbation model for the effect of general perturbations, such as a compression, on the recurrent parameters of RNNs. The model is tested against a noiseless memorization experiment that elucidates the short-term memory performance. In this way, we demonstrate that the effect of compression of recurrent parameters is dependent on the degree of temporal coherence present in the data and task. This work can guide on-the-fly RNN compression for novel environments or tasks, and provides insight for applying RNN compression in low-power devices, such as hearing aids.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1612.00891](https://arxiv.org/abs/1612.00891)

##### PDF
[https://arxiv.org/pdf/1612.00891](https://arxiv.org/pdf/1612.00891)

