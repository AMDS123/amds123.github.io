---
layout: post
title: "AOGNets: Compositional Grammatical Architectures for Deep Learning"
date: 2019-04-06 14:04:30
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Segmentation Attention Classification Deep_Learning Detection
author: Xilai Li, Xi Song, Tianfu Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Neural architectures are the foundation for improving performance of deep neural networks (DNNs). This paper presents deep compositional grammatical architectures which harness the best of two worlds: grammar models and DNNs. The proposed architectures integrate compositionality and reconfigurability of the former and the capability of learning rich features of the latter in a principled way. We utilize AND-OR Grammar (AOG) as network generator in this paper and call the resulting networks AOGNets. An AOGNet consists of a number of stages each of which is composed of a number of AOG building blocks. An AOG building block splits its input feature map into N groups along feature channels and then treat it as a sentence of N words. It then jointly realizes a phrase structure grammar and a dependency grammar in bottom-up parsing the "sentence" for better feature exploration and reuse. It provides a unified framework for the best practices developed in state-of-the-art DNNs. In experiments, AOGNet is tested in the CIFAR-10, CIFAR-100 and ImageNet-1K classification benchmark and the MS-COCO object detection and segmentation benchmark. In CIFAR-10, CIFAR-100 and ImageNet-1K, AOGNet obtains better performance than ResNet and most of its variants, ResNeXt and its attention based variants such as SENet, DenseNet and DualPathNet. AOGNet also obtains the best model interpretability score using network dissection. AOGNet further shows better potential in adversarial defense. In MS-COCO, AOGNet obtains better performance than the ResNet and ResNeXt backbones in Mask R-CNN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1711.05847](http://arxiv.org/abs/1711.05847)

##### PDF
[http://arxiv.org/pdf/1711.05847](http://arxiv.org/pdf/1711.05847)

