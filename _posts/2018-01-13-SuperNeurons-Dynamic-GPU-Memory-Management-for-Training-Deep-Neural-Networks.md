---
layout: post
title: "SuperNeurons: Dynamic GPU Memory Management for Training Deep Neural Networks"
date: 2018-01-13 04:11:41
categories: arXiv_CV
tags: arXiv_CV Optimization Deep_Learning
author: Linnan Wang, Jinmian Ye, Yiyang Zhao, Wei Wu, Ang Li, Shuaiwen Leon Song, Zenglin Xu, Tim Kraska
mathjax: true
---

* content
{:toc}

##### Abstract
Going deeper and wider in neural architectures improves the accuracy, while the limited GPU DRAM places an undesired restriction on the network design domain. Deep Learning (DL) practitioners either need change to less desired network architectures, or nontrivially dissect a network across multiGPUs. These distract DL practitioners from concentrating on their original machine learning tasks. We present SuperNeurons: a dynamic GPU memory scheduling runtime to enable the network training far beyond the GPU DRAM capacity. SuperNeurons features 3 memory optimizations, \textit{Liveness Analysis}, \textit{Unified Tensor Pool}, and \textit{Cost-Aware Recomputation}, all together they effectively reduce the network-wide peak memory usage down to the maximal memory usage among layers. We also address the performance issues in those memory saving techniques. Given the limited GPU DRAM, SuperNeurons not only provisions the necessary memory for the training, but also dynamically allocates the memory for convolution workspaces to achieve the high performance. Evaluations against Caffe, Torch, MXNet and TensorFlow have demonstrated that SuperNeurons trains at least 3.2432 deeper network than current ones with the leading performance. Particularly, SuperNeurons can train ResNet2500 that has $10^4$ basic network layers on a 12GB K40c.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1801.04380](https://arxiv.org/abs/1801.04380)

##### PDF
[https://arxiv.org/pdf/1801.04380](https://arxiv.org/pdf/1801.04380)

