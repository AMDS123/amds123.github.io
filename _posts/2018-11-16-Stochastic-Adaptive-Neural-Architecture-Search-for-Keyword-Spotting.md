---
layout: post
title: "Stochastic Adaptive Neural Architecture Search for Keyword Spotting"
date: 2018-11-16 11:08:26
categories: arXiv_CV
tags: arXiv_CV NAS Inference Prediction Recognition
author: Tom Véniat, Olivier Schwander, Ludovic Denoyer
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of keyword spotting i.e. identifying keywords in a real-time audio stream is mainly solved by applying a neural network over successive sliding windows. Due to the difficulty of the task, baseline models are usually large, resulting in a high computational cost and energy consumption level. We propose a new method called SANAS (Stochastic Adaptive Neural Architecture Search) which is able to adapt the architecture of the neural network on-the-fly at inference time such that small architectures will be used when the stream is easy to process (silence, low noise, ...) and bigger networks will be used when the task becomes more difficult. We show that this adaptive model can be learned end-to-end by optimizing a trade-off between the prediction performance and the average computational cost per unit of time. Experiments on the Speech Commands dataset show that this approach leads to a high recognition level while being much faster (and/or energy saving) than classical approaches where the network architecture is static.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.06753](https://arxiv.org/abs/1811.06753)

##### PDF
[https://arxiv.org/pdf/1811.06753](https://arxiv.org/pdf/1811.06753)

