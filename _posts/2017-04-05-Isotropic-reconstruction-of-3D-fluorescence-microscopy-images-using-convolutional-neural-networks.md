---
layout: post
title: "Isotropic reconstruction of 3D fluorescence microscopy images using convolutional neural networks"
date: 2017-04-05 16:20:36
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Segmentation CNN Quantitative
author: Martin Weigert, Loic Royer, Florian Jug, Gene Myers
mathjax: true
---

* content
{:toc}

##### Abstract
Fluorescence microscopy images usually show severe anisotropy in axial versus lateral resolution. This hampers downstream processing, i.e. the automatic extraction of quantitative biological data. While deconvolution methods and other techniques to address this problem exist, they are either time consuming to apply or limited in their ability to remove anisotropy. We propose a method to recover isotropic resolution from readily acquired anisotropic data. We achieve this using a convolutional neural network that is trained end-to-end from the same anisotropic body of data we later apply the network to. The network effectively learns to restore the full isotropic resolution by restoring the image under a trained, sample specific image prior. We apply our method to $3$ synthetic and $3$ real datasets and show that our results improve on results from deconvolution and state-of-the-art super-resolution techniques. Finally, we demonstrate that a standard 3D segmentation pipeline performs on the output of our network with comparable accuracy as on the full isotropic data.

##### Abstract (translated by Google)
荧光显微镜图像通常在轴向分辨率和横向分辨率下显示严重的各向异性。这阻碍了下游处理，即自动提取定量生物数据。虽然反卷积方法和其他技术来解决这个问题存在，他们要么消耗时间或应用或限制其去除各向异性的能力。我们提出了一种从容易获得的各向异性数据恢复各向同性分辨率的方法。我们使用一个卷积神经网络来实现这一点，这个神经网络是从我们后来应用网络的相同的各向异性数据体端到端地进行训练的。网络有效地学习恢复完全的各向同性分辨率，通过恢复图像在训练的样本特定的图像之前。我们将我们的方法应用于$ 3 $ synthetic和$ 3 $ real数据集，并显示我们的结果改进了去卷积和最先进的超分辨率技术的结果。最后，我们演示了一个标准的3D分割流水线在我们网络的输出上执行的结果与完全各向同性的数据相当的准确性。

##### URL
[https://arxiv.org/abs/1704.01510](https://arxiv.org/abs/1704.01510)

##### PDF
[https://arxiv.org/pdf/1704.01510](https://arxiv.org/pdf/1704.01510)

