---
layout: post
title: "PSDNet and DPDNet: Efficient channel expansion, Depthwise-Pointwise-Depthwise Inverted Bottleneck Block"
date: 2019-09-03 09:53:31
categories: arXiv_CV
tags: arXiv_CV
author: Guoqing Li, Meng Zhang, Qianru Zhang, Ziyang Chen, Wenzhao Liu, Jiaojie Li, Xuzhao Shen, Jianjun Li, Zhenyu Zhu, Chau Yuen
mathjax: true
---

* content
{:toc}

##### Abstract
In many real-time applications, the deployment of deep neural networks is constrained by high computational cost and efficient lightweight neural networks are widely concerned. In this paper, we propose that depthwise convolution (DWC) is used to expand the number of channels in a bottleneck block, which is more efficient than 1 x 1 convolution. The proposed Pointwise-Standard-Depthwise network (PSDNet) based on channel expansion with DWC has fewer number of parameters, less computational cost and higher accuracy than corresponding ResNet on CIFAR datasets. To design more efficient lightweight concolutional neural netwok, Depthwise-Pointwise-Depthwise inverted bottleneck block (DPD block) is proposed and DPDNet is designed by stacking DPD block. Meanwhile, the number of parameters of DPDNet is only about 60% of that of MobileNetV2 for networks with the same number of layers, but can achieve approximated accuracy. Additionally, two hyperparameters of DPDNet can make the trade-off between accuracy and computational cost, which makes DPDNet suitable for diverse tasks. Furthermore, we find the networks with more DWC layers outperform the networks with more 1x1 convolution layers, which indicates that extracting spatial information is more important than combining channel information.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1909.01026](https://arxiv.org/abs/1909.01026)

##### PDF
[https://arxiv.org/pdf/1909.01026](https://arxiv.org/pdf/1909.01026)

