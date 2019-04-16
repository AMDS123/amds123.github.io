---
layout: post
title: "Optimizing the F-measure for Threshold-free Salient Object Detection"
date: 2018-05-19 10:54:43
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Optimization Prediction Detection
author: Kai Zhao, Shanghua Gao, Qibin Hou, Dan-Dan Li, Ming-Ming Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
Current CNN-based solutions to salient object detection (SOD) mainly rely on the optimization of cross-entropy loss (CELoss). Then the quality of detected saliency maps is often evaluated in terms of F-measure. In this paper, we investigate an interesting issue: can we consistently use the F-measure formulation in both training and evaluation for SOD? By reformulating the standard F-measure we propose the relaxed F-measure which is differentiable w.r.t the posterior and can be easily appended to the back of CNNs as the loss function. Compared to the conventional cross-entropy loss of which the gradients decrease dramatically in the saturated area, our loss function, named FLoss, holds considerable gradients even when the activation approaches the target. Consequently, the FLoss can continuously force the network to produce polarized activations. Comprehensive benchmarks on several popular datasets show that FLoss outperforms the state- of-the-arts with a considerable margin. More specifically, due to the polarized predictions, our method is able to obtain high quality saliency maps without carefully tuning the optimal threshold, showing significant advantages in real world applications.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.07567](https://arxiv.org/abs/1805.07567)

##### PDF
[https://arxiv.org/pdf/1805.07567](https://arxiv.org/pdf/1805.07567)

