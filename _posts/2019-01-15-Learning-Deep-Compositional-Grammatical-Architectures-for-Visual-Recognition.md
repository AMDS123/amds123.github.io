---
layout: post
title: "Learning Deep Compositional Grammatical Architectures for Visual Recognition"
date: 2019-01-15 19:21:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Classification Detection Recognition
author: Xilai Li, Tianfu Wu, Xi Song
mathjax: true
---

* content
{:toc}

##### Abstract
Neural architectures are the foundation for improving performance of deep neural networks (DNNs). This paper presents deep compositional grammatical architectures which harness the best of two worlds: grammar models and DNNs. The proposed architectures integrate compositionality and reconfigurability of the former and the capability of learning rich features of the latter in a principled way. They also show the platform-agnostic capability in deployment (e.g., cloud vs mobile). We utilize AND-OR Grammars (AOG) in this paper and call the resulting networks AOGNets. An AOGNet consists of a number of stages each of which is composed of a number of AOG building blocks. An AOG building block splits its input feature map into N groups along feature channels and then treat it as a sentence of N words. It then jointly realizes a phrase structure grammar and a dependency grammar in bottom-up parsing the "sentence" for better feature exploration and exploitation. It provides a unified framework for the split-transform-aggregate heuristic widely used in neural architecture design. In experiments, AOGNets are tested on three highly competitive image classification benchmarks: CIFAR-10, CIFAR-100 and ImageNet-1K. AOGNets obtain better performance than ResNets and most of its variants, ResNeXts, DenseNets and DualPathNets when model sizes are comparable. AOGNets are also tested in object detection on the PASCAL VOC 2007 and 2012 using the vanilla Faster R-CNN system. AOGNets use smaller models and obtain better performance by about 3% mean average precision than the ResNets backbone.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1711.05847](http://arxiv.org/abs/1711.05847)

##### PDF
[http://arxiv.org/pdf/1711.05847](http://arxiv.org/pdf/1711.05847)

