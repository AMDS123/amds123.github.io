---
layout: post
title: "The Reversible Residual Network: Backpropagation Without Storing Activations"
date: 2017-07-14 03:05:43
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification
author: Aidan N. Gomez, Mengye Ren, Raquel Urtasun, Roger B. Grosse
mathjax: true
---

* content
{:toc}

##### Abstract
Deep residual networks (ResNets) have significantly pushed forward the state-of-the-art on image classification, increasing in performance as networks grow both deeper and wider. However, memory consumption becomes a bottleneck, as one needs to store the activations in order to calculate gradients using backpropagation. We present the Reversible Residual Network (RevNet), a variant of ResNets where each layer's activations can be reconstructed exactly from the next layer's. Therefore, the activations for most layers need not be stored in memory during backpropagation. We demonstrate the effectiveness of RevNets on CIFAR-10, CIFAR-100, and ImageNet, establishing nearly identical classification accuracy to equally-sized ResNets, even though the activation storage requirements are independent of depth.

##### Abstract (translated by Google)
深度残差网络（ResNets）极大地推动了图像分类技术的发展，随着网络越来越深入，网络性能也越来越好。然而，内存消耗成为瓶颈，因为需要存储激活以便使用反向传播计算梯度。我们提出可逆残余网络（RevNet），ResNet的一个变体，其中每一层的激活可以从下一层精确重建。因此，在反向传播期间，大多数层的激活不需要存储在存储器中。我们展示了Revit在CIFAR-10，CIFAR-100和ImageNet上的有效性，即使激活存储要求与深度无关，也可以建立与同样大小的ResNets几乎相同的分类精度。

##### URL
[https://arxiv.org/abs/1707.04585](https://arxiv.org/abs/1707.04585)

##### PDF
[https://arxiv.org/pdf/1707.04585](https://arxiv.org/pdf/1707.04585)

