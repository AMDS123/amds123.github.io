---
layout: post
title: "Towards Accurate One-Stage Object Detection with AP-Loss"
date: 2019-04-12 18:58:55
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization Classification Detection
author: Kean Chen, Jianguo Li, Weiyao Lin, John See, Ji Wang, Lingyu Duan, Zhibo Chen, Changwei He, Junni Zou
mathjax: true
---

* content
{:toc}

##### Abstract
One-stage object detectors are trained by optimizing classification-loss and localization-loss simultaneously, with the former suffering much from extreme foreground-background class imbalance issue due to the large number of anchors. This paper alleviates this issue by proposing a novel framework to replace the classification task in one-stage detectors with a ranking task, and adopting the Average-Precision loss (AP-loss) for the ranking problem. Due to its non-differentiability and non-convexity, the AP-loss cannot be optimized directly. For this purpose, we develop a novel optimization algorithm, which seamlessly combines the error-driven update scheme in perceptron learning and backpropagation algorithm in deep networks. We verify good convergence property of the proposed algorithm theoretically and empirically. Experimental results demonstrate notable performance improvement in state-of-the-art one-stage detectors based on AP-loss over different kinds of classification-losses on various benchmarks, without changing the network architectures.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06373](http://arxiv.org/abs/1904.06373)

##### PDF
[http://arxiv.org/pdf/1904.06373](http://arxiv.org/pdf/1904.06373)

