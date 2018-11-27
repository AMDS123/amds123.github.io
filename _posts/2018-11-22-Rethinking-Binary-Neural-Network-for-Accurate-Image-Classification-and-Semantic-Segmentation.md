---
layout: post
title: "Rethinking Binary Neural Network for Accurate Image Classification and Semantic Segmentation"
date: 2018-11-22 05:24:17
categories: arXiv_CV
tags: arXiv_CV Segmentation Image_Classification Semantic_Segmentation Classification Prediction
author: Bohan Zhuang, Chunhua Shen, Mingkui Tan, Lingqiao Liu, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose to train a network with both binary weights and binary activations, designed specifically for mobile devices with limited computation capacity and power consumption. Previous works on quantizing CNNs uncritically assume the same architecture with full-precision networks, which we term value approximation. Their objective is to preserve the floating-point information using a set of discrete values. However, we take a novel view---for best performance it is very likely that a different architecture may be better suited to deal with binary weights as well as binary activations. Thus we directly design such a highly accurate binary network structure, which is termed structure approximation. In particular, we propose a "network decomposition" strategy in which we divide the networks into groups and aggregate a set of homogeneous binary branches to implicitly reconstruct the full-precision intermediate feature maps. In addition, we also learn the connections between each group. We further provide a comprehensive comparison among all quantization categories. Experiments on ImageNet classification tasks demonstrate the superior performance of the proposed model, named Group-Net, over various popular architectures. In particular, we outperform the previous best binary neural network in terms of accuracy as well as saving huge computational complexity. Furthermore, the proposed Group-Net can effectively utilize task specific properties for strong generalization. In particular, we propose to extend Group-Net for \textbf{lossless} semantic segmentation. This is the first work proposed on solving dense pixels prediction based on BNNs in the literature. Actually, we claim that considering both value and structure approximation should be the future development direction of BNNs.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.10413](https://arxiv.org/abs/1811.10413)

##### PDF
[https://arxiv.org/pdf/1811.10413](https://arxiv.org/pdf/1811.10413)

