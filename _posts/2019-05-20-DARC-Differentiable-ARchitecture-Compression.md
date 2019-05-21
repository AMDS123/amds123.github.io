---
layout: post
title: "DARC: Differentiable ARchitecture Compression"
date: 2019-05-20 15:30:06
categories: arXiv_CV
tags: arXiv_CV NAS CNN Image_Classification Inference Classification
author: Shashank Singh, Ashish Khetan, Zohar Karnin
mathjax: true
---

* content
{:toc}

##### Abstract
In many learning situations, resources at inference time are significantly more constrained than resources at training time. This paper studies a general paradigm, called Differentiable ARchitecture Compression (DARC), that combines model compression and architecture search to learn models that are resource-efficient at inference time. Given a resource-intensive base architecture, DARC utilizes the training data to learn which sub-components can be replaced by cheaper alternatives. The high-level technique can be applied to any neural architecture, and we report experiments on state-of-the-art convolutional neural networks for image classification. For a WideResNet with $97.2\%$ accuracy on CIFAR-10, we improve single-sample inference speed by $2.28\times$ and memory footprint by $5.64\times$, with no accuracy loss. For a ResNet with $79.15\%$ Top1 accuracy on ImageNet, we improve batch inference speed by $1.29\times$ and memory footprint by $3.57\times$ with $1\%$ accuracy loss. We also give theoretical Rademacher complexity bounds in simplified cases, showing how DARC avoids overfitting despite over-parameterization.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08170](http://arxiv.org/abs/1905.08170)

##### PDF
[http://arxiv.org/pdf/1905.08170](http://arxiv.org/pdf/1905.08170)

