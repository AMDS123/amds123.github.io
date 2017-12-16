---
layout: post
title: "SSH: Single Stage Headless Face Detector"
date: 2017-10-18 00:07:03
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Classification Detection
author: Mahyar Najibi, Pouya Samangouei, Rama Chellappa, Larry Davis
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the Single Stage Headless (SSH) face detector. Unlike two stage proposal-classification detectors, SSH detects faces in a single stage directly from the early convolutional layers in a classification network. SSH is headless. That is, it is able to achieve state-of-the-art results while removing the "head" of its underlying classification network -- i.e. all fully connected layers in the VGG-16 which contains a large number of parameters. Additionally, instead of relying on an image pyramid to detect faces with various scales, SSH is scale-invariant by design. We simultaneously detect faces with different scales in a single forward pass of the network, but from different layers. These properties make SSH fast and light-weight. Surprisingly, with a headless VGG-16, SSH beats the ResNet-101-based state-of-the-art on the WIDER dataset. Even though, unlike the current state-of-the-art, SSH does not use an image pyramid and is 5X faster. Moreover, if an image pyramid is deployed, our light-weight network achieves state-of-the-art on all subsets of the WIDER dataset, improving the AP by 2.5%. SSH also reaches state-of-the-art results on the FDDB and Pascal-Faces datasets while using a small input size, leading to a runtime of 50 ms/image on a GPU. The code is available at this https URL

##### Abstract (translated by Google)
我们介绍单级无头（SSH）人脸检测器。与两阶段提议分类检测器不同，SSH直接从分类网络中的早期卷积层检测一个阶段中的面孔。 SSH是无头的。也就是说，它能够在去除其基础分类网络的“头部”（即，包含大量参数的VGG-16中的所有完全连接的层）的同时实现最新的结果。另外，SSH不是依靠图像金字塔来检测不同尺度的人脸，而是通过设计来保持尺度不变。我们同时在网络的单个正向通道中检测具有不同尺度的面孔，但是从不同层面检测面孔。这些属性使得SSH快速和轻量级。令人惊讶的是，凭借无头VGG-16，SSH击败了WIDER数据集中基于ResNet-101的最新技术。尽管与目前的最新技术不同，SSH不使用图像金字塔，速度提高了5倍。此外，如果部署图像金字塔，我们的轻量级网络将在WIDER数据集的所有子集上实现最新技术，将AP提高2.5％。 SSH还在FDDB和Pascal-Faces数据集上实现了最新的结果，同时使用较小的输入大小，从而在GPU上实现了50 ms /图像的运行时间。该代码可在此https网址获得

##### URL
[https://arxiv.org/abs/1708.03979](https://arxiv.org/abs/1708.03979)

##### PDF
[https://arxiv.org/pdf/1708.03979](https://arxiv.org/pdf/1708.03979)

