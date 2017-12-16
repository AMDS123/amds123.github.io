---
layout: post
title: "Pixel Recursive Super Resolution"
date: 2017-03-22 16:13:21
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Ryan Dahl, Mohammad Norouzi, Jonathon Shlens
mathjax: true
---

* content
{:toc}

##### Abstract
We present a pixel recursive super resolution model that synthesizes realistic details into images while enhancing their resolution. A low resolution image may correspond to multiple plausible high resolution images, thus modeling the super resolution process with a pixel independent conditional model often results in averaging different details--hence blurry edges. By contrast, our model is able to represent a multimodal conditional distribution by properly modeling the statistical dependencies among the high resolution image pixels, conditioned on a low resolution input. We employ a PixelCNN architecture to define a strong prior over natural images and jointly optimize this prior with a deep conditioning convolutional network. Human evaluations indicate that samples from our proposed model look more photo realistic than a strong L2 regression baseline.

##### Abstract (translated by Google)
我们提出一个像素递归超分辨率模型，合成现实的细节成图像，同时提高他们的决议。低分辨率的图像可能对应于多个合理的高分辨率图像，因此使用独立于像素的条件模型对超分辨率处理进行建模通常导致平均不同的细节 - 因此模糊的边缘。相比之下，我们的模型能够通过对高分辨率图像像素之间的统计相关性进行适当建模来表示多模态条件分布，这取决于低分辨率输入。我们采用PixelCNN体系结构来定义超过自然图像的先验优先性，并通过深度调节卷积网络进行联合优化。人类评估表明，我们提出的模型中的样本比强回归基线更接近真实感。

##### URL
[https://arxiv.org/abs/1702.00783](https://arxiv.org/abs/1702.00783)

##### PDF
[https://arxiv.org/pdf/1702.00783](https://arxiv.org/pdf/1702.00783)

