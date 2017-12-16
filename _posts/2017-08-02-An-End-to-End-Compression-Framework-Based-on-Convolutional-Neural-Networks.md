---
layout: post
title: "An End-to-End Compression Framework Based on Convolutional Neural Networks"
date: 2017-08-02 17:26:28
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Recognition
author: Feng Jiang, Wen Tao, Shaohui Liu, Jie Ren, Xun Guo, Debin Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning, e.g., convolutional neural networks (CNNs), has achieved great success in image processing and computer vision especially in high level vision applications such as recognition and understanding. However, it is rarely used to solve low-level vision problems such as image compression studied in this paper. Here, we move forward a step and propose a novel compression framework based on CNNs. To achieve high-quality image compression at low bit rates, two CNNs are seamlessly integrated into an end-to-end compression framework. The first CNN, named compact convolutional neural network (ComCNN), learns an optimal compact representation from an input image, which preserves the structural information and is then encoded using an image codec (e.g., JPEG, JPEG2000 or BPG). The second CNN, named reconstruction convolutional neural network (RecCNN), is used to reconstruct the decoded image with high-quality in the decoding end. To make two CNNs effectively collaborate, we develop a unified end-to-end learning algorithm to simultaneously learn ComCNN and RecCNN, which facilitates the accurate reconstruction of the decoded image using RecCNN. Such a design also makes the proposed compression framework compatible with existing image coding standards. Experimental results validate that the proposed compression framework greatly outperforms several compression frameworks that use existing image coding standards with state-of-the-art deblocking or denoising post-processing methods.

##### Abstract (translated by Google)
深度学习（例如卷积神经网络（CNN））在图像处理和计算机视觉方面取得了巨大的成功，特别是在诸如识别和理解的高级视觉应用中。然而，它很少用于解决像本文研究的图像压缩等低级视觉问题。在这里，我们向前迈出了一步，并提出了一个基于CNN的新型压缩框架。为了在低比特率下实现高质量的图像压缩，两个CNN被无缝集成到一个端到端的压缩框架中。命名为紧凑卷积神经网络（ComCNN）的第一个CNN从输入图像中学习最优紧凑表示，该输入图像保留结构信息，然后使用图像编解码器（例如，JPEG，JPEG2000或BPG）进行编码。第二个CNN被称为重建卷积神经网络（RecCNN），用于在解码端重建高质量的解码图像。为了使两个CNN有效地协作，我们开发了统一的端到端学习算法，以同时学习ComCNN和RecCNN，这有助于使用RecCNN精确重建解码图像。这样的设计也使得所提出的压缩框架与现有的图像编码标准兼容。实验结果验证了所提出的压缩框架大大优于几个压缩框架，这些压缩框架使用现有的图像编码标准以及最新的去块或去噪后处理方法。

##### URL
[https://arxiv.org/abs/1708.00838](https://arxiv.org/abs/1708.00838)

##### PDF
[https://arxiv.org/pdf/1708.00838](https://arxiv.org/pdf/1708.00838)

