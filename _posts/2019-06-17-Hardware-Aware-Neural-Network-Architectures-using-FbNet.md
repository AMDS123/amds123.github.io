---
layout: post
title: "Hardware Aware Neural Network Architectures using FbNet"
date: 2019-06-17 18:34:01
categories: arXiv_CV
tags: arXiv_CV
author: Sai Vineeth Kalluru Srinivas, Harideep Nair, Vinay Vidyasagar
mathjax: true
---

* content
{:toc}

##### Abstract
We implement a differentiable Neural Architecture Search (NAS) method inspired by FBNet for discovering neural networks that are heavily optimized for a particular target device. The FBNet NAS method discovers a neural network from a given search space by optimizing over a loss function which accounts for accuracy and target device latency. We extend this loss function by adding an energy term. This will potentially enhance the ``hardware awareness" and help us find a neural network architecture that is optimal in terms of accuracy, latency and energy consumption, given a target device (Raspberry Pi in our case). We name our trained child architecture obtained at the end of search process as Hardware Aware Neural Network Architecture (HANNA). We prove the efficacy of our approach by benchmarking HANNA against two other state-of-the-art neural networks designed for mobile/embedded applications, namely MobileNetv2 and CondenseNet for CIFAR-10 dataset. Our results show that HANNA provides a speedup of about 2.5x and 1.7x, and reduces energy consumption by 3.8x and 2x compared to MobileNetv2 and CondenseNet respectively. HANNA is able to provide such significant speedup and energy efficiency benefits over the state-of-the-art baselines at the cost of a tolerable 4-5% drop in accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07214](http://arxiv.org/abs/1906.07214)

##### PDF
[http://arxiv.org/pdf/1906.07214](http://arxiv.org/pdf/1906.07214)

