---
layout: post
title: "Tiny SSD: A Tiny Single-shot Detection Deep Convolutional Neural Network for Real-time Embedded Object Detection"
date: 2018-02-19 01:57:46
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection
author: Alexander Wong, Mohammad Javad Shafiee, Francis Li, Brendan Chwyl
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection is a major challenge in computer vision, involving both object classification and object localization within a scene. While deep neural networks have been shown in recent years to yield very powerful techniques for tackling the challenge of object detection, one of the biggest challenges with enabling such object detection networks for widespread deployment on embedded devices is high computational and memory requirements. Recently, there has been an increasing focus in exploring small deep neural network architectures for object detection that are more suitable for embedded devices, such as Tiny YOLO and SqueezeDet. Inspired by the efficiency of the Fire microarchitecture introduced in SqueezeNet and the object detection performance of the single-shot detection macroarchitecture introduced in SSD, this paper introduces Tiny SSD, a single-shot detection deep convolutional neural network for real-time embedded object detection that is composed of a highly optimized, non-uniform Fire sub-network stack and a non-uniform sub-network stack of highly optimized SSD-based auxiliary convolutional feature layers designed specifically to minimize model size while maintaining object detection performance. The resulting Tiny SSD possess a model size of 2.3MB (~26X smaller than Tiny YOLO) while still achieving an mAP of 61.3% on VOC 2007 (~4.2% higher than Tiny YOLO). These experimental results show that very small deep neural network architectures can be designed for real-time object detection that are well-suited for embedded scenarios.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.06488](https://arxiv.org/abs/1802.06488)

##### PDF
[https://arxiv.org/pdf/1802.06488](https://arxiv.org/pdf/1802.06488)

