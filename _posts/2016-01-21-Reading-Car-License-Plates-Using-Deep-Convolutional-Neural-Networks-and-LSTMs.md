---
layout: post
title: "Reading Car License Plates Using Deep Convolutional Neural Networks and LSTMs"
date: 2016-01-21 12:42:19
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN RNN Classification Detection Recognition
author: Hui Li, Chunhua Shen
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we tackle the problem of car license plate detection and recognition in natural scene images. Inspired by the success of deep neural networks (DNNs) in various vision applications, here we leverage DNNs to learn high-level features in a cascade framework, which lead to improved performance on both detection and recognition. Firstly, we train a $37$-class convolutional neural network (CNN) to detect all characters in an image, which results in a high recall, compared with conventional approaches such as training a binary text/non-text classifier. False positives are then eliminated by the second plate/non-plate CNN classifier. Bounding box refinement is then carried out based on the edge information of the license plates, in order to improve the intersection-over-union (IoU) ratio. The proposed cascade framework extracts license plates effectively with both high recall and precision. Last, we propose to recognize the license characters as a {sequence labelling} problem. A recurrent neural network (RNN) with long short-term memory (LSTM) is trained to recognize the sequential features extracted from the whole license plate via CNNs. The main advantage of this approach is that it is segmentation free. By exploring context information and avoiding errors caused by segmentation, the RNN method performs better than a baseline method of combining segmentation and deep CNN classification; and achieves state-of-the-art recognition accuracy.

##### Abstract (translated by Google)
在这项工作中，我们解决了自然场景图像中的车牌检测和识别问题。受各种视觉应用中深度神经网络（DNN）的成功启发，我们利用DNN在级联框架中学习高级特征，从而提高检测和识别性能。首先，我们训练一个$ 37 $类的卷积神经网络（CNN）来检测图像中的所有字符，与传统方法（如训练二进制文本/非文本分类器）相比，这将产生高回忆。然后通过第二板/非板CNN分类器消除假阳性。然后基于车牌的边缘信息进行边界框细化，以改善交叉口（IoU）比率。所提出的级联框架有效地提取牌照，具有高召回率和高精度。最后，我们建议将许可字符识别为{序列标签}问题。对具有长期短时记忆（LSTM）的递归神经网络（RNN）进行训练，以识别通过CNN从整个牌照提取的顺序特征。这种方法的主要优点是它是免费的。通过探索上下文信息，避免分割带来的误差，RNN方法的性能优于分割和深度CNN分类相结合的基线方法;并实现了最先进的识别精度。

##### URL
[https://arxiv.org/abs/1601.05610](https://arxiv.org/abs/1601.05610)

##### PDF
[https://arxiv.org/pdf/1601.05610](https://arxiv.org/pdf/1601.05610)

