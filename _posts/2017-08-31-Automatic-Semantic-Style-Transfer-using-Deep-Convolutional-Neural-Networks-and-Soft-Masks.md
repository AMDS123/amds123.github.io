---
layout: post
title: "Automatic Semantic Style Transfer using Deep Convolutional Neural Networks and Soft Masks"
date: 2017-08-31 09:48:00
categories: arXiv_CV
tags: arXiv_CV Style_Transfer CNN
author: Huihuang Zhao, Paul L. Rosin, Yu-Kun Lai
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an automatic image synthesis method to transfer the style of an example image to a content image. When standard neural style transfer approaches are used, the textures and colours in different semantic regions of the style image are often applied inappropriately to the content image, ignoring its semantic layout, and ruining the transfer result. In order to reduce or avoid such effects, we propose a novel method based on automatically segmenting the objects and extracting their soft semantic masks from the style and content images, in order to preserve the structure of the content image while having the style transferred. Each soft mask of the style image represents a specific part of the style image, corresponding to the soft mask of the content image with the same semantics. Both the soft masks and source images are provided as multichannel input to an augmented deep CNN framework for style transfer which incorporates a generative Markov random field (MRF) model. Results on various images show that our method outperforms the most recent techniques.

##### Abstract (translated by Google)
本文提出了一种自动图像合成方法，将实例图像的样式转换为内容图像。当采用标准的神经风格转移方法时，风格图像不同语义区域的纹理和颜色往往不适当地应用到内容图像上，忽略其语义布局，破坏了转移结果。为了减少或避免这种效果，我们提出了一种基于自动分割对象，从样式和内容图像中提取软语义掩码的新颖方法，以保持内容图像在风格转移的同时的结构。样式图像的每个软掩码表示样式图像的特定部分，对应于具有相同语义的内容图像的软掩码。将软掩码和源图像作为多通道输入提供给用于样式转移的增强型深度CNN框架，其包含生成马尔科夫随机场（MRF）模型。各种图像的结果表明，我们的方法胜过了最新的技术。

##### URL
[https://arxiv.org/abs/1708.09641](https://arxiv.org/abs/1708.09641)

##### PDF
[https://arxiv.org/pdf/1708.09641](https://arxiv.org/pdf/1708.09641)

