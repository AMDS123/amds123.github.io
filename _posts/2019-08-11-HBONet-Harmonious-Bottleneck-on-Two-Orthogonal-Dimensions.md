---
layout: post
title: "HBONet: Harmonious Bottleneck on Two Orthogonal Dimensions"
date: 2019-08-11 11:37:39
categories: arXiv_CV
tags: arXiv_CV Re-identification Object_Detection Person_Re-identification CNN Classification Detection
author: Duo Li, Aojun Zhou, Anbang Yao
mathjax: true
---

* content
{:toc}

##### Abstract
MobileNets, a class of top-performing convolutional neural network architectures in terms of accuracy and efficiency trade-off, are increasingly used in many resourceaware vision applications. In this paper, we present Harmonious Bottleneck on two Orthogonal dimensions (HBO), a novel architecture unit, specially tailored to boost the accuracy of extremely lightweight MobileNets at the level of less than 40 MFLOPs. Unlike existing bottleneck designs that mainly focus on exploring the interdependencies among the channels of either groupwise or depthwise convolutional features, our HBO improves bottleneck representation while maintaining similar complexity via jointly encoding the feature interdependencies across both spatial and channel dimensions. It has two reciprocal components, namely spatial contraction-expansion and channel expansion-contraction, nested in a bilaterally symmetric structure. The combination of two interdependent transformations performing on orthogonal dimensions of feature maps enhances the representation and generalization ability of our proposed module, guaranteeing compelling performance with limited computational resource and power. By replacing the original bottlenecks in MobileNetV2 backbone with HBO modules, we construct HBONets which are evaluated on ImageNet classification, PASCAL VOC object detection and Market-1501 person re-identification. Extensive experiments show that with the severe constraint of computational budget our models outperform MobileNetV2 counterparts by remarkable margins of at most 6.6%, 6.3% and 5.0% on the above benchmarks respectively. Code and pretrained models are available at this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.03888](https://arxiv.org/abs/1908.03888)

##### PDF
[https://arxiv.org/pdf/1908.03888](https://arxiv.org/pdf/1908.03888)

