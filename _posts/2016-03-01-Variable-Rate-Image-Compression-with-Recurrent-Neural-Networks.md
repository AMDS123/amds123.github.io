---
layout: post
title: "Variable Rate Image Compression with Recurrent Neural Networks"
date: 2016-03-01 22:13:44
categories: arXiv_CV
tags: arXiv_CV Review CNN RNN
author: George Toderici, Sean M. O'Malley, Sung Jin Hwang, Damien Vincent, David Minnen, Shumeet Baluja, Michele Covell, Rahul Sukthankar
mathjax: true
---

* content
{:toc}

##### Abstract
A large fraction of Internet traffic is now driven by requests from mobile devices with relatively small screens and often stringent bandwidth requirements. Due to these factors, it has become the norm for modern graphics-heavy websites to transmit low-resolution, low-bytecount image previews (thumbnails) as part of the initial page load process to improve apparent page responsiveness. Increasing thumbnail compression beyond the capabilities of existing codecs is therefore a current research focus, as any byte savings will significantly enhance the experience of mobile device users. Toward this end, we propose a general framework for variable-rate image compression and a novel architecture based on convolutional and deconvolutional LSTM recurrent networks. Our models address the main issues that have prevented autoencoder neural networks from competing with existing image compression algorithms: (1) our networks only need to be trained once (not per-image), regardless of input image dimensions and the desired compression rate; (2) our networks are progressive, meaning that the more bits are sent, the more accurate the image reconstruction; and (3) the proposed architecture is at least as efficient as a standard purpose-trained autoencoder for a given number of bits. On a large-scale benchmark of 32$\times$32 thumbnails, our LSTM-based approaches provide better visual quality than (headerless) JPEG, JPEG2000 and WebP, with a storage size that is reduced by 10% or more.

##### Abstract (translated by Google)
互联网流量的大部分现在是由移动设备的请求驱动的，而移动设备的屏幕相对较小，而且通常对带宽的要求很高。由于这些因素，作为初始页面加载过程的一部分，现代图形重量级网站已经成为传输低分辨率，低贝叶图像预览（缩略图）的标准，以提高明显的页面响应能力。因此，增加缩略图压缩超出现有编解码器的能力是当前研究的焦点，因为任何字节节省将显着增强移动设备用户的体验。为此，我们提出了一个基于卷积和去卷积LSTM递归网络的变速率图像压缩的一般框架和一种新颖的体系结构。我们的模型解决了防止自动编码器神经网络与现有图像压缩算法竞争的主要问题：（1）我们的网络只需要被训练一次（而不是每个图像），而不管输入图像尺寸和期望的压缩率; （2）我们的网络是渐进式的，这意味着发送的比特越多，图像重建越准确; （3）对于给定的比特数，所提出的体系结构至少与标准的目的训练的自动编码器一样高效。在基于32×32倍缩略图的大型基准测试中，基于LSTM的方法比JPEG（无标头）JPEG，JPEG2000和WebP提供更好的视觉质量，存储容量减少了10％甚至更多。

##### URL
[https://arxiv.org/abs/1511.06085](https://arxiv.org/abs/1511.06085)

##### PDF
[https://arxiv.org/pdf/1511.06085](https://arxiv.org/pdf/1511.06085)

