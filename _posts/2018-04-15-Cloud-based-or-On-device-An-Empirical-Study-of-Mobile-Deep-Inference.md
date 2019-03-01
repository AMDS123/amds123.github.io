---
layout: post
title: "Cloud-based or On-device: An Empirical Study of Mobile Deep Inference"
date: 2018-04-15 17:48:20
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Inference Deep_Learning Recognition
author: Tian Guo
mathjax: true
---

* content
{:toc}

##### Abstract
Modern mobile applications are benefiting significantly from the advancement in deep learning, e.g., implementing real-time image recognition and conversational system. Given a trained deep learning model, applications usually need to perform a series of matrix operations based on the input data, in order to infer possible output values. Because of computational complexity and size constraints, these trained models are often hosted in the cloud. To utilize these cloud-based models, mobile apps will have to send input data over the network. While cloud-based deep learning can provide reasonable response time for mobile apps, it restricts the use case scenarios, e.g. mobile apps need to have network access. With mobile specific deep learning optimizations, it is now possible to employ on-device inference. However, because mobile hardware, such as GPU and memory size, can be very limited when compared to its desktop counterpart, it is important to understand the feasibility of this new on-device deep learning inference architecture. In this paper, we empirically evaluate the inference performance of three Convolutional Neural Networks (CNNs) using a benchmark Android application we developed. Our measurement and analysis suggest that on-device inference can cost up to two orders of magnitude greater response time and energy when compared to cloud-based inference, and that loading model and computing probability are two performance bottlenecks for on-device deep inferences.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1707.04610](http://arxiv.org/abs/1707.04610)

##### PDF
[http://arxiv.org/pdf/1707.04610](http://arxiv.org/pdf/1707.04610)

