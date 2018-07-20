---
layout: post
title: "CT Image Enhancement Using Stacked Generative Adversarial Networks and Transfer Learning for Lesion Segmentation Improvement"
date: 2018-07-18 21:01:37
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN Image_Enhancement Transfer_Learning
author: Youbao Tang, Jinzheng Cai, Le Lu, Adam P. Harrison, Ke Yan, Jing Xiao, Lin Yang, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Automated lesion segmentation from computed tomography (CT) is an important and challenging task in medical image analysis. While many advancements have been made, there is room for continued improvements. One hurdle is that CT images can exhibit high noise and low contrast, particularly in lower dosages. To address this, we focus on a preprocessing method for CT images that uses stacked generative adversarial networks (SGAN) approach. The first GAN reduces the noise in the CT image and the second GAN generates a higher resolution image with enhanced boundaries and high contrast. To make up for the absence of high quality CT images, we detail how to synthesize a large number of low- and high-quality natural images and use transfer learning with progressively larger amounts of CT images. We apply both the classic GrabCut method and the modern holistically nested network (HNN) to lesion segmentation, testing whether SGAN can yield improved lesion segmentation. Experimental results on the DeepLesion dataset demonstrate that the SGAN enhancements alone can push GrabCut performance over HNN trained on original images. We also demonstrate that HNN + SGAN performs best compared against four other enhancement methods, including when using only a single GAN.

##### Abstract (translated by Google)
计算机断层扫描（CT）的自动病变分割是医学图像分析中的一项重要且具有挑战性的任务。虽然取得了许多进展，但仍有继续改进的余地。一个障碍是CT图像可以表现出高噪声和低对比度，特别是在较低剂量下。为了解决这个问题，我们专注于使用堆叠生成对抗网络（SGAN）方法的CT图像预处理方法。第一个GAN降低CT图像中的噪声，第二个GAN生成具有增强边界和高对比度的更高分辨率图像。为了弥补高质量CT图像的缺失，我们详细介绍了如何合成大量低质量和高质量的自然图像，并使用逐渐增大的CT图像进行转移学习。我们将经典GrabCut方法和现代整体嵌套网络（HNN）应用于病变分割，测试SGAN是否可以产生改进的病变分割。 DeepLesion数据集上的实验结果表明，单独的SGAN增强功能可以在原始图像上训练的HNN上推动GrabCut性能。我们还证明，与其他四种增强方法相比，HNN + SGAN的性能最佳，包括仅使用一个GAN时。

##### URL
[https://arxiv.org/abs/1807.07144](https://arxiv.org/abs/1807.07144)

##### PDF
[https://arxiv.org/pdf/1807.07144](https://arxiv.org/pdf/1807.07144)

