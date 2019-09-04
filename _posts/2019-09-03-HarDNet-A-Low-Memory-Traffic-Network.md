---
layout: post
title: "HarDNet: A Low Memory Traffic Network"
date: 2019-09-03 04:34:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Inference Detection
author: Ping Chao, Chao-Yang Kao, Yu-Shan Ruan, Chien-Hsiang Huang, Youn-Long Lin
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art neural network architectures such as ResNet, MobileNet, and DenseNet have achieved outstanding accuracy over low MACs and small model size counterparts. However, these metrics might not be accurate for predicting the inference time. We suggest that memory traffic for accessing intermediate feature maps can be a factor dominating the inference latency, especially in such tasks as real-time object detection and semantic segmentation of high-resolution video. We propose a Harmonic Densely Connected Network to achieve high efficiency in terms of both low MACs and memory traffic. The new network achieves 35%, 36%, 30%, 32%, and 45% inference time reduction compared with FC-DenseNet-103, DenseNet-264, ResNet-50, ResNet-152, and SSD-VGG, respectively. We use tools including Nvidia profiler and ARM Scale-Sim to measure the memory traffic and verify that the inference latency is indeed proportional to the memory traffic consumption and the proposed network consumes low memory traffic. We conclude that one should take memory traffic into consideration when designing neural network architectures for high-resolution applications at the edge.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00948](http://arxiv.org/abs/1909.00948)

##### PDF
[http://arxiv.org/pdf/1909.00948](http://arxiv.org/pdf/1909.00948)

