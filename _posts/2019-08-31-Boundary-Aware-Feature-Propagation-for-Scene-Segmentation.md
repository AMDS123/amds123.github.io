---
layout: post
title: "Boundary-Aware Feature Propagation for Scene Segmentation"
date: 2019-08-31 09:56:09
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Henghui Ding, Xudong Jiang, Ai Qun Liu, Nadia Magnenat Thalmann, Gang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we address the challenging issue of scene segmentation. To increase the feature similarity of the same object while keeping the feature discrimination of different objects, we explore to propagate information throughout the image under the control of objects' boundaries. To this end, we first propose to learn the boundary as an additional semantic class to enable the network to be aware of the boundary layout. Then, we propose unidirectional acyclic graphs (UAGs) to model the function of undirected cyclic graphs (UCGs), which structurize the image via building graphic pixel-by-pixel connections, in an efficient and effective way. Furthermore, we propose a boundary-aware feature propagation (BFP) module to harvest and propagate the local features within their regions isolated by the learned boundaries in the UAG-structured image. The proposed BFP is capable of splitting the feature propagation into a set of semantic groups via building strong connections among the same segment region but weak connections between different segment regions. Without bells and whistles, our approach achieves new state-of-the-art segmentation performance on three challenging semantic segmentation datasets, i.e., PASCAL-Context, CamVid, and Cityscapes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00179](http://arxiv.org/abs/1909.00179)

##### PDF
[http://arxiv.org/pdf/1909.00179](http://arxiv.org/pdf/1909.00179)

