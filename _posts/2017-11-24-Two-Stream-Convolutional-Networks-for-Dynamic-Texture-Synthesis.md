---
layout: post
title: "Two-Stream Convolutional Networks for Dynamic Texture Synthesis"
date: 2017-11-24 18:42:02
categories: arXiv_CV
tags: arXiv_CV Style_Transfer CNN Prediction Quantitative Recognition
author: Matthew Tesfaldet, Marcus A. Brubaker, Konstantinos G. Derpanis
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a two-stream model for dynamic texture synthesis. Our model is based on pre-trained convolutional networks (ConvNets) that target two independent tasks: (i) object recognition, and (ii) optical flow prediction. Given an input dynamic texture, statistics of filter responses from the object recognition ConvNet encapsulate the per-frame appearance of the input texture, while statistics of filter responses from the optical flow ConvNet model its dynamics. To generate a novel texture, a noise input sequence is optimized to simultaneously match the feature statistics from each stream of an example texture. Inspired by recent work on image style transfer and enabled by the two-stream model, we also apply the synthesis approach to combine the texture appearance from one texture with the dynamics of another to generate entirely novel dynamic textures. We show that our approach generates novel, high quality samples that match both the framewise appearance and temporal evolution of input texture imagery. Finally, we quantitatively evaluate our approach with a thorough user study.

##### Abstract (translated by Google)
我们介绍一个动态纹理合成的双流模型。我们的模型基于预先训练的卷积网络（ConvNets），其目标是两个独立的任务：（i）物体识别，和（ii）光流预测。给定输入动态纹理，来自对象识别的滤波器响应的统计数据ConvNet封装输入纹理的每帧外观，而来自光流ConvNet的滤波器响应的统计数据模拟其动态。为了生成新颖的纹理，优化噪声输入序列以同时匹配来自示例纹理的每个流的特征统计量。受到近期有关图像风格转换的工作的启发，并受到双流模型的启发，我们也应用综合方法将一个纹理的纹理外观与另一个纹理的动态纹理结合起来，以产生全新的动态纹理。我们表明，我们的方法生成新颖的，高质量的样本，匹配输入纹理图像的框架外观和时间演变。最后，我们通过深入的用户研究来定量评估我们的方法。

##### URL
[https://arxiv.org/abs/1706.06982](https://arxiv.org/abs/1706.06982)

##### PDF
[https://arxiv.org/pdf/1706.06982](https://arxiv.org/pdf/1706.06982)

