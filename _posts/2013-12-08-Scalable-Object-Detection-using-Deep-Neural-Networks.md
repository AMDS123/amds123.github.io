---
layout: post
title: "Scalable Object Detection using Deep Neural Networks"
date: 2013-12-08 19:40:51
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection CNN Detection Recognition
author: Dumitru Erhan, Christian Szegedy, Alexander Toshev, Dragomir Anguelov
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks have recently achieved state-of-the-art performance on a number of image recognition benchmarks, including the ImageNet Large-Scale Visual Recognition Challenge (ILSVRC-2012). The winning model on the localization sub-task was a network that predicts a single bounding box and a confidence score for each object category in the image. Such a model captures the whole-image context around the objects but cannot handle multiple instances of the same object in the image without naively replicating the number of outputs for each instance. In this work, we propose a saliency-inspired neural network model for detection, which predicts a set of class-agnostic bounding boxes along with a single score for each box, corresponding to its likelihood of containing any object of interest. The model naturally handles a variable number of instances for each class and allows for cross-class generalization at the highest levels of the network. We are able to obtain competitive recognition performance on VOC2007 and ILSVRC2012, while using only the top few predicted locations in each image and a small number of neural network evaluations.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1312.2249](https://arxiv.org/abs/1312.2249)

##### PDF
[https://arxiv.org/pdf/1312.2249](https://arxiv.org/pdf/1312.2249)

