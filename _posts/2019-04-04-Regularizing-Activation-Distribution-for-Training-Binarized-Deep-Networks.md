---
layout: post
title: "Regularizing Activation Distribution for Training Binarized Deep Networks"
date: 2019-04-04 23:20:09
categories: arXiv_CV
tags: arXiv_CV Regularization Inference
author: Ruizhou Ding, Ting-Wu Chin, Zeye Liu, Diana Marculescu
mathjax: true
---

* content
{:toc}

##### Abstract
Binarized Neural Networks (BNNs) can significantly reduce the inference latency and energy consumption in resource-constrained devices due to their pure-logical computation and fewer memory accesses. However, training BNNs is difficult since the activation flow encounters degeneration, saturation, and gradient mismatch problems. Prior work alleviates these issues by increasing activation bits and adding floating-point scaling factors, thereby sacrificing BNN's energy efficiency. In this paper, we propose to use distribution loss to explicitly regularize the activation flow, and develop a framework to systematically formulate the loss. Our experiments show that the distribution loss can consistently improve the accuracy of BNNs without losing their energy benefits. Moreover, equipped with the proposed regularization, BNN training is shown to be robust to the selection of hyper-parameters including optimizer and learning rate.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02823](https://arxiv.org/abs/1904.02823)

##### PDF
[https://arxiv.org/pdf/1904.02823](https://arxiv.org/pdf/1904.02823)

