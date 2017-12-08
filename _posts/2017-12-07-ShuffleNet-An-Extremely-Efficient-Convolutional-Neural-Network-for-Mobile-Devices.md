---
layout: post
title: "ShuffleNet: An Extremely Efficient Convolutional Neural Network for Mobile Devices"
date: 2017-12-07 18:06:34
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection
author: Xiangyu Zhang, Xinyu Zhou, Mengxiao Lin, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an extremely computation-efficient CNN architecture named ShuffleNet, which is designed specially for mobile devices with very limited computing power (e.g., 10-150 MFLOPs). The new architecture utilizes two new operations, pointwise group convolution and channel shuffle, to greatly reduce computation cost while maintaining accuracy. Experiments on ImageNet classification and MS COCO object detection demonstrate the superior performance of ShuffleNet over other structures, e.g. lower top-1 error (absolute 7.8%) than recent MobileNet on ImageNet classification task, under the computation budget of 40 MFLOPs. On an ARM-based mobile device, ShuffleNet achieves ~13x actual speedup over AlexNet while maintaining comparable accuracy.

##### Abstract (translated by Google)
我们引入了一个非常计算高效的CNN架构，名为ShuffleNet，专门设计用于计算能力非常有限的移动设备（例如10-150 MFLOPs）。新的架构利用了两个新的操作，点群卷积和信道混洗，在保证精度的同时大大降低了计算成本。在ImageNet分类和MS COCO对象检测上的实验证明了ShuffleNet优于其他结构的性能，例如，在40个MFLOP的计算预算下，比ImageNet分类任务上的最新MobileNet更低的前1个错误（绝对7.8％）。在基于ARM的移动设备上，ShuffleNet在AlexNet上实现了13倍的实际加速，同时保持了相当的精度。

##### URL
[http://arxiv.org/abs/1707.01083](http://arxiv.org/abs/1707.01083)

##### PDF
[http://arxiv.org/pdf/1707.01083](http://arxiv.org/pdf/1707.01083)

