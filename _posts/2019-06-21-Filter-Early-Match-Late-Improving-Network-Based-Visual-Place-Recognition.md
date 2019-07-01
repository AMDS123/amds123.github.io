---
layout: post
title: "Filter Early, Match Late: Improving Network-Based Visual Place Recognition"
date: 2019-06-21 06:12:27
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Recognition
author: Stephen Hausler, Adam Jacobson, Michael Milford
mathjax: true
---

* content
{:toc}

##### Abstract
CNNs have excelled at performing place recognition over time, particularly when the neural network is optimized for localization in the current environmental conditions. In this paper we investigate the concept of feature map filtering, where, rather than using all the activations within a convolutional tensor, only the most useful activations are used. Since specific feature maps encode different visual features, the objective is to remove feature maps that are detract from the ability to recognize a location across appearance changes. Our key innovation is to filter the feature maps in an early convolutional layer, but then continue to run the network and extract a feature vector using a later layer in the same network. By filtering early visual features and extracting a feature vector from a higher, more viewpoint invariant later layer, we demonstrate improved condition and viewpoint invariance. Our approach requires image pairs for training from the deployment environment, but we show that state-of-the-art performance can regularly be achieved with as little as a single training image pair. An exhaustive experimental analysis is performed to determine the full scope of causality between early layer filtering and late layer extraction. For validity, we use three datasets: Oxford RobotCar, Nordland, and Gardens Point, achieving overall superior performance to NetVLAD. The work provides a number of new avenues for exploring CNN optimizations, without full re-training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.12176](http://arxiv.org/abs/1906.12176)

##### PDF
[http://arxiv.org/pdf/1906.12176](http://arxiv.org/pdf/1906.12176)

