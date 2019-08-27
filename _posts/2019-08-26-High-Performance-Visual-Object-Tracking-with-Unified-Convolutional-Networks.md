---
layout: post
title: "High Performance Visual Object Tracking with Unified Convolutional Networks"
date: 2019-08-26 03:09:03
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Object_Tracking Optimization
author: Zheng Zhu, Wei Zou, Guan Huang, Dalong Du, Chang Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNN) based tracking approaches have shown favorable performance in recent benchmarks. Nonetheless, the chosen CNN features are always pre-trained in different tasks and individual components in tracking systems are learned separately, thus the achieved tracking performance may be suboptimal. Besides, most of these trackers are not designed towards real-time applications because of their time-consuming feature extraction and complex optimization details. In this paper, we propose an end-to-end framework to learn the convolutional features and perform the tracking process simultaneously, namely, a unified convolutional tracker (UCT). Specifically, the UCT treats feature extractor and tracking process both as convolution operation and trains them jointly, which enables learned CNN features are tightly coupled with tracking process. During online tracking, an efficient model updating method is proposed by introducing peak-versus-noise ratio (PNR) criterion, and scale changes are handled efficiently by incorporating a scale branch into network. Experiments are performed on four challenging tracking datasets: OTB2013, OTB2015, VOT2015 and VOT2016. Our method achieves leading performance on these benchmarks while maintaining beyond real-time speed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09445](http://arxiv.org/abs/1908.09445)

##### PDF
[http://arxiv.org/pdf/1908.09445](http://arxiv.org/pdf/1908.09445)

