---
layout: post
title: "Scalable Object Detection using Deep Neural Networks"
date: 2013-12-08 19:40:51
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection Recognition
author: Dumitru Erhan, Christian Szegedy, Alexander Toshev, Dragomir Anguelov
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks have recently achieved state-of-the-art performance on a number of image recognition benchmarks, including the ImageNet Large-Scale Visual Recognition Challenge (ILSVRC-2012). The winning model on the localization sub-task was a network that predicts a single bounding box and a confidence score for each object category in the image. Such a model captures the whole-image context around the objects but cannot handle multiple instances of the same object in the image without naively replicating the number of outputs for each instance. In this work, we propose a saliency-inspired neural network model for detection, which predicts a set of class-agnostic bounding boxes along with a single score for each box, corresponding to its likelihood of containing any object of interest. The model naturally handles a variable number of instances for each class and allows for cross-class generalization at the highest levels of the network. We are able to obtain competitive recognition performance on VOC2007 and ILSVRC2012, while using only the top few predicted locations in each image and a small number of neural network evaluations.

##### Abstract (translated by Google)
深卷积神经网络最近在许多图像识别基准上取得了最新的性能，包括ImageNet大规模视觉识别挑战（ILSVRC-2012）。本地化子任务的获胜模型是预测图像中每个对象类别的单个边界框和置信度分数的网络。这样的模型捕获对象周围的整个图像上下文，但不能处理图像中同一对象的多个实例，而不会天真地复制每个实例的输出数量。在这项工作中，我们提出了一个显着性神经网络模型的检测，预测一组类不可知的包围盒，每个盒子单一的分数，对应于其包含任何感兴趣的对象的可能性。该模型自然处理每个类的可变数量的实例，并允许在网络的最高级别进行跨类泛化。我们能够在VOC2007和ILSVRC2012上获得有竞争力的识别性能，同时仅使用每幅图像中最少的预测位置和少量的神经网络评估。

##### URL
[https://arxiv.org/abs/1312.2249](https://arxiv.org/abs/1312.2249)

