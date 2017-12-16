---
layout: post
title: "Efficient and Scalable View Generation from a Single Image using Fully Convolutional Networks"
date: 2017-05-10 13:02:24
categories: arXiv_CV
tags: arXiv_CV CNN
author: Sung-Ho Bae, Mohamed Elgharib, Mohamed Hefeeda, Wojciech Matusik
mathjax: true
---

* content
{:toc}

##### Abstract
Single-image-based view generation (SIVG) is important for producing 3D stereoscopic content. Here, handling different spatial resolutions as input and optimizing both reconstruction accuracy and processing speed is desirable. Latest approaches are based on convolutional neural network (CNN), and they generate promising results. However, their use of fully connected layers as well as pre-trained VGG forces a compromise between reconstruction accuracy and processing speed. In addition, this approach is limited to the use of a specific spatial resolution. To remedy these problems, we propose exploiting fully convolutional networks (FCN) for SIVG. We present two FCN architectures for SIVG. The first one is based on combination of an FCN and a view-rendering network called DeepView$_{ren}$. The second one consists of decoupled networks for luminance and chrominance signals, denoted by DeepView$_{dec}$. To train our solutions we present a large dataset of 2M stereoscopic images. Results show that both of our architectures improve accuracy and speed over the state of the art. DeepView$_{ren}$ generates competitive accuracy to the state of the art, however, with the fastest processing speed of all. That is x5 times faster speed and x24 times lower memory consumption compared to the state of the art. DeepView$_{dec}$ has much higher accuracy, but with x2.5 times faster speed and x12 times lower memory consumption. We evaluated our approach with both objective and subjective studies.

##### Abstract (translated by Google)
基于单个图像的视图生成（SIVG）对于生成3D立体内容非常重要。这里，处理不同的空间分辨率作为输入并优化重构精度和处理速度是所希望的。最新的方法是基于卷积神经网络（CNN），并且它们产生了有希望的结果。然而，他们使用完全连接的层以及预先训练的VGG在重建准确性和处理速度之间折衷。另外，这种方法仅限于使用特定的空间分辨率。为了弥补这些问题，我们建议为SIVG开发完全卷积网络（FCN）。我们为SIVG提供两个FCN架构。第一个是基于FCN和称为DeepView $ _ {ren} $的视图渲染网络的组合。第二个包括用于亮度和色度信号的解耦网络，由DeepView $ _ {dec} $表示。为了训练我们的解决方案，我们提供了一个2M立体图像的大型数据集。结果显示，我们的两种架构都能提高现有技术的准确性和速度。 DeepView $ _ {ren} $产生竞争的准确性，但是，最快的处理速度。与现有技术相比，速度提高了5倍，内存消耗降低了24倍。 DeepView $ _ {dec} $具有更高的精确度，但速度提高了x2.5倍，内存消耗降低了x12倍。我们用客观和主观的研究来评估我们的方法。

##### URL
[https://arxiv.org/abs/1705.03737](https://arxiv.org/abs/1705.03737)

##### PDF
[https://arxiv.org/pdf/1705.03737](https://arxiv.org/pdf/1705.03737)

