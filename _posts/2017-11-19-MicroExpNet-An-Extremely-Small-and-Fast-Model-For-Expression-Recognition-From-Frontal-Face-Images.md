---
layout: post
title: "MicroExpNet: An Extremely Small and Fast Model For Expression Recognition From Frontal Face Images"
date: 2017-11-19 12:31:09
categories: arXiv_CV
tags: arXiv_CV Knowledge Face CNN Recognition
author: İlke Çuğu, Eren Şener, Emre Akbaş
mathjax: true
---

* content
{:toc}

##### Abstract
This paper is aimed at creating extremely small and fast convolutional neural networks (CNN) for the problem of facial expression recognition (FER) from frontal face images. We show that, for this problem, translation invariance (achieved through max-pooling layers) degrades performance, especially when the network is small, and that the knowledge distillation method can be used to obtain extremely compressed CNNs. Extensive comparisons on two widely-used FER datasets, CK+ and Oulu-CASIA, demonstrate that our largest model sets the new state-of-the-art by yielding 1.8% and 12.7% relative improvement over the previous best results, on CK+ and Oulu-CASIA datasets, respectively. In addition, our smallest model (MicroExpNet), obtained using knowledge distillation, is less than 1MB in size and works at 1408 frames per second on an Intel i7 CPU. Being slightly less accurate than our largest model, MicroExpNet still achieves a 8.3% relative improvement, on the Oulu-CASIA dataset, over the previous state-of-the-art, much larger network; and on the CK+ dataset, it performs on par with a previous state-of-the-art network but with 154x fewer parameters.

##### Abstract (translated by Google)
本文旨在为正面人脸图像中的面部表情识别（FER）问题创建极小的快速卷积神经网络（CNN）。我们表明，对于这个问题，翻译不变性（通过最大池层来实现）降低了性能，特别是当网络较小时，并且知识蒸馏方法可以用来获得极度压缩的CNN。对两个广泛使用的FER数据集CK +和Oulu-CASIA的广泛比较表明，我们最大的模型设置了最新的最新技术，比CK +和Oulu先前的最佳结果分别提高了1.8％和12.7％ -CASIA数据集，分别。此外，我们使用知识蒸馏技术获得的最小型号（MicroExpNet），尺寸小于1MB，在Intel i7 CPU上以每秒1408帧的速度工作。与我们最大的模型相比，MicroExpNet的准确度稍差，但在Oulu-CASIA数据集上，相对于以前最先进的大型网络，MicroExpNet仍然实现了8.3％的相对改进。并且在CK +数据集上，它与之前的最先进的网络相提并论，但参数少了154倍。

##### URL
[https://arxiv.org/abs/1711.07011](https://arxiv.org/abs/1711.07011)

##### PDF
[https://arxiv.org/pdf/1711.07011](https://arxiv.org/pdf/1711.07011)

