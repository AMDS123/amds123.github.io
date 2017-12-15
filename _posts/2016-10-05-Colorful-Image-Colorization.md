---
layout: post
title: "Colorful Image Colorization"
date: 2016-10-05 18:01:05
categories: arXiv_CV
tags: arXiv_CV Classification
author: Richard Zhang, Phillip Isola, Alexei A. Efros
mathjax: true
---

* content
{:toc}

##### Abstract
Given a grayscale photograph as input, this paper attacks the problem of hallucinating a plausible color version of the photograph. This problem is clearly underconstrained, so previous approaches have either relied on significant user interaction or resulted in desaturated colorizations. We propose a fully automatic approach that produces vibrant and realistic colorizations. We embrace the underlying uncertainty of the problem by posing it as a classification task and use class-rebalancing at training time to increase the diversity of colors in the result. The system is implemented as a feed-forward pass in a CNN at test time and is trained on over a million color images. We evaluate our algorithm using a "colorization Turing test," asking human participants to choose between a generated and ground truth color image. Our method successfully fools humans on 32% of the trials, significantly higher than previous methods. Moreover, we show that colorization can be a powerful pretext task for self-supervised feature learning, acting as a cross-channel encoder. This approach results in state-of-the-art performance on several feature learning benchmarks.

##### Abstract (translated by Google)
以灰度照片作为输入，本文攻击幻觉的合理色彩版本的照片的问题。这个问题显然是不受约束的，所以以前的方法要么依赖于重要的用户交互，要么导致不饱和的着色。我们提出了一种全自动的方法，可以生成鲜明逼真的色彩。我们通过把它作为一个分类任务，并在训练时间使用类别重新平衡来解决问题的潜在不确定性，以增加结果中颜色的多样性。该系统在测试时间在CNN中作为前馈通道实施，并接受超过一百万个彩色图像的训练。我们使用“彩色化图灵测试”来评估我们的算法，要求人类参与者在生成的和地面的真实彩色图像之间进行选择。我们的方法在32％的试验中成功愚弄人类，显着高于以前的方法。此外，我们表明，彩色化可以是一个强有力的借口任务自我监督的特征学习，作为一个跨渠道的编码器。这种方法可以在几个功能学习基准上获得最先进的性能。

##### URL
[https://arxiv.org/abs/1603.08511](https://arxiv.org/abs/1603.08511)

##### PDF
[https://arxiv.org/pdf/1603.08511](https://arxiv.org/pdf/1603.08511)

