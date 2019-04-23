---
layout: post
title: "An Energy and GPU-Computation Efficient Backbone Network for Real-Time Object Detection"
date: 2019-04-22 05:45:57
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Youngwan Lee, Joong-won Hwang, Sangrok Lee, Yuseok Bae, Jongyoul Park
mathjax: true
---

* content
{:toc}

##### Abstract
As DenseNet conserves intermediate features with diverse receptive fields by aggregating them with dense connection, it shows good performance on the object detection task. Although feature reuse enables DenseNet to produce strong features with a small number of model parameters and FLOPs, the detector with DenseNet backbone shows rather slow speed and low energy efficiency. We find the linearly increasing input channel by dense connection leads to heavy memory access cost, which causes computation overhead and more energy consumption. To solve the inefficiency of DenseNet, we propose an energy and computation efficient architecture called VoVNet comprised of One-Shot Aggregation (OSA). The OSA not only adopts the strength of DenseNet that represents diversified features with multi receptive fields but also overcomes the inefficiency of dense connection by aggregating all features only once in the last feature maps. To validate the effectiveness of VoVNet as a backbone network, we design both lightweight and large-scale VoVNet and apply them to one-stage and two-stage object detectors. Our VoVNet based detectors outperform DenseNet based ones with 2x faster speed and the energy consumptions are reduced by 1.6x - 4.1x. In addition to DenseNet, VoVNet also outperforms widely used ResNet backbone with faster speed and better energy efficiency. In particular, the small object detection performance has been significantly improved over DenseNet and ResNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09730](http://arxiv.org/abs/1904.09730)

##### PDF
[http://arxiv.org/pdf/1904.09730](http://arxiv.org/pdf/1904.09730)

