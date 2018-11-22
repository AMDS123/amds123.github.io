---
layout: post
title: "Graph-Adaptive Pruning for Efficient Inference of Convolutional Neural Networks"
date: 2018-11-21 03:43:38
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Inference
author: Mengdi Wang, Qing Zhang, Jun Yang, Xiaoyuan Cui, Wei Lin
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a graph-adaptive pruning (GAP) method for efficient inference of convolutional neural networks (CNNs). In this method, the network is viewed as a computational graph, in which the vertices denote the computation nodes and edges represent the information flow. Through topology analysis, GAP is capable of adapting to different network structures, especially the widely used cross connections and multi-path data flow in recent novel convolutional models. The models can be adaptively pruned at vertex-level as well as edge-level without any post-processing, thus GAP can directly get practical model compression and inference speed-up. Moreover, it does not need any customized computation library or hardware support. Finetuning is conducted after pruning to restore the model performance. In the finetuning step, we adopt a self-taught knowledge distillation (KD) strategy by utilizing information from the original model, through which, the performance of the optimized model can be sufficiently improved, without introduction of any other teacher model. Experimental results show the proposed GAP can achieve promising result to make inference more efficient, e.g., for ResNeXt-29 on CIFAR10, it can get 13X model compression and 4.3X practical speed-up with marginal loss of accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08589](http://arxiv.org/abs/1811.08589)

##### PDF
[http://arxiv.org/pdf/1811.08589](http://arxiv.org/pdf/1811.08589)

