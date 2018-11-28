---
layout: post
title: "Deformable ConvNets v2: More Deformable, Better Results"
date: 2018-11-27 18:58:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Classification Detection
author: Xizhou Zhu, Han Hu, Stephen Lin, Jifeng Dai
mathjax: true
---

* content
{:toc}

##### Abstract
The superior performance of Deformable Convolutional Networks arises from its ability to adapt to the geometric variations of objects. Through an examination of its adaptive behavior, we observe that while the spatial support for its neural features conforms more closely than regular ConvNets to object structure, this support may nevertheless extend well beyond the region of interest, causing features to be influenced by irrelevant image content. To address this problem, we present a reformulation of Deformable ConvNets that improves its ability to focus on pertinent image regions, through increased modeling power and stronger training. The modeling power is enhanced through a more comprehensive integration of deformable convolution within the network, and by introducing a modulation mechanism that expands the scope of deformation modeling. To effectively harness this enriched modeling capability, we guide network training via a proposed feature mimicking scheme that helps the network to learn features that reflect the object focus and classification power of R-CNN features. With the proposed contributions, this new version of Deformable ConvNets yields significant performance gains over the original model and produces leading results on the COCO benchmark for object detection and instance segmentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11168](http://arxiv.org/abs/1811.11168)

##### PDF
[http://arxiv.org/pdf/1811.11168](http://arxiv.org/pdf/1811.11168)

