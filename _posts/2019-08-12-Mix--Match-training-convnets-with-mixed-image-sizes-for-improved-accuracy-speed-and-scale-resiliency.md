---
layout: post
title: "Mix & Match: training convnets with mixed image sizes for improved accuracy, speed and scale resiliency"
date: 2019-08-12 08:27:49
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Elad Hoffer, Berry Weinstein, Itay Hubara, Tal Ben-Nun, Torsten Hoefler, Daniel Soudry
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) are commonly trained using a fixed spatial image size predetermined for a given model. Although trained on images of aspecific size, it is well established that CNNs can be used to evaluate a wide range of image sizes at test time, by adjusting the size of intermediate feature maps. In this work, we describe and evaluate a novel mixed-size training regime that mixes several image sizes at training time. We demonstrate that models trained using our method are more resilient to image size changes and generalize well even on small images. This allows faster inference by using smaller images attest time. For instance, we receive a 76.43% top-1 accuracy using ResNet50 with an image size of 160, which matches the accuracy of the baseline model with 2x fewer computations. Furthermore, for a given image size used at test time, we show this method can be exploited either to accelerate training or the final test accuracy. For example, we are able to reach a 79.27% accuracy with a model evaluated at a 288 spatial size for a relative improvement of 14% over the baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08986](http://arxiv.org/abs/1908.08986)

##### PDF
[http://arxiv.org/pdf/1908.08986](http://arxiv.org/pdf/1908.08986)

