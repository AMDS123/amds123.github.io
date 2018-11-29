---
layout: post
title: "Structured Binary Neural Networks for Accurate Image Classification and Semantic Segmentation"
date: 2018-11-27 03:32:02
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding CNN Image_Classification Semantic_Segmentation Classification
author: Bohan Zhuang, Chunhua Shen, Mingkui Tan, Lingqiao Liu, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose to train convolutional neural networks (CNNs) with both binarized weights and activations, leading to quantized models specifically} for mobile devices with limited power capacity and computation resources. Previous works on quantizing CNNs seek to approximate the floating-point information using a set of discrete values, which we call value approximation, but typically assume the same architecture as the full-precision networks. In this paper, however, we take a novel 'structure approximation' view for quantization---it is very likely that a different architecture may be better for best performance. In particular, we propose a `network decomposition' strategy, named \textbf{Group-Net}, in which we divide the network into groups. In this way, each full-precision group can be effectively reconstructed by aggregating a set of homogeneous binary branches. In addition, we learn effective connections among groups to improve the representational capability. Moreover, the proposed Group-Net shows strong generalization to other tasks. For instance, we extend Group-Net for highly accurate semantic segmentation by embedding rich context into the binary structure. Experiments on both classification and semantic segmentation tasks demonstrate the superior performance of the proposed methods over various popular architectures. In particular, we outperform the previous best binary neural networks in terms of accuracy and major computation savings.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.10413](https://arxiv.org/abs/1811.10413)

##### PDF
[https://arxiv.org/pdf/1811.10413](https://arxiv.org/pdf/1811.10413)

