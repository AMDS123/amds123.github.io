---
layout: post
title: "Segmentation-free Vehicle License Plate Recognition using ConvNet-RNN"
date: 2017-01-23 15:11:12
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN RNN Detection Recognition
author: Teik Koon Cheang, Yong Shean Chong, Yong Haur Tay
mathjax: true
---

* content
{:toc}

##### Abstract
While vehicle license plate recognition (VLPR) is usually done with a sliding window approach, it can have limited performance on datasets with characters that are of variable width. This can be solved by hand-crafting algorithms to prescale the characters. While this approach can work fairly well, the recognizer is only aware of the pixels within each detector window, and fails to account for other contextual information that might be present in other parts of the image. A sliding window approach also requires training data in the form of presegmented characters, which can be more difficult to obtain. In this paper, we propose a unified ConvNet-RNN model to recognize real-world captured license plate photographs. By using a Convolutional Neural Network (ConvNet) to perform feature extraction and using a Recurrent Neural Network (RNN) for sequencing, we address the problem of sliding window approaches being unable to access the context of the entire image by feeding the entire image as input to the ConvNet. This has the added benefit of being able to perform end-to-end training of the entire model on labelled, full license plate images. Experimental results comparing the ConvNet-RNN architecture to a sliding window-based approach shows that the ConvNet-RNN architecture performs significantly better.

##### Abstract (translated by Google)
虽然车牌识别（VLPR）通常使用滑动窗口方法完成，但是对于宽度可变的字符数据集，性能可能有限。这可以通过手工制定算法来预处理字符来解决。虽然这种方法可以很好地工作，但是识别器只知道每个检测器窗口内的像素，并且不能解释可能存在于图像的其他部分中的其他上下文信息。滑动窗口方法还需要以预分割字符的形式来训练数据，这可能更难以获得。在本文中，我们提出了一个统一的ConvNet-RNN模型来识别真实世界拍摄的车牌照片。通过使用卷积神经网络（ConvNet）执行特征提取并使用递归神经网络（RNN）进行排序，我们解决了通过馈送整个图像作为输入而无法访问整个图像的上下文的滑动窗口方法的问题到ConvNet。这样做还有另外一个好处，就是能够在标记完整车牌图像上执行整个模型的端到端培训。将ConvNet-RNN体系结构与基于滑动窗口的方法进行比较的实验结果表明，ConvNet-RNN体系结构的性能显着提高。

##### URL
[https://arxiv.org/abs/1701.06439](https://arxiv.org/abs/1701.06439)

##### PDF
[https://arxiv.org/pdf/1701.06439](https://arxiv.org/pdf/1701.06439)

