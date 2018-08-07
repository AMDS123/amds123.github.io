---
layout: post
title: "Diverse and Accurate Image Description Using a Variational Auto-Encoder with an Additive Gaussian Encoding Space"
date: 2017-11-19 20:12:43
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN
author: Liwei Wang, Alexander G. Schwing, Svetlana Lazebnik
mathjax: true
---

* content
{:toc}

##### Abstract
This paper explores image caption generation using conditional variational auto-encoders (CVAEs). Standard CVAEs with a fixed Gaussian prior yield descriptions with too little variability. Instead, we propose two models that explicitly structure the latent space around $K$ components corresponding to different types of image content, and combine components to create priors for images that contain multiple types of content simultaneously (e.g., several kinds of objects). Our first model uses a Gaussian Mixture model (GMM) prior, while the second one defines a novel Additive Gaussian (AG) prior that linearly combines component means. We show that both models produce captions that are more diverse and more accurate than a strong LSTM baseline or a "vanilla" CVAE with a fixed Gaussian prior, with AG-CVAE showing particular promise.

##### Abstract (translated by Google)
本文探讨了使用条件变分自动编码器（CVAE）生成图像标题。标准CVAE具有固定的高斯先验产率描述，具有太小的可变性。相反，我们提出了两个模型，它们明确地构造了与不同类型的图像内容相对应的$ K $组件周围的潜在空间，并组合组件以同时为包含多种类型内容的图像（例如，几种对象）创建先验。我们的第一个模型使用高斯混合模型（GMM）先验，而第二个模型定义了一个新的加性高斯（AG）先验，线性组合组件均值。我们证明两种模型都产生比强LSTM基线或具有固定高斯先验的“香草”CVAE更多样化和更准确的字幕，其中AG-CVAE显示出特别的前景。

##### URL
[https://arxiv.org/abs/1711.07068](https://arxiv.org/abs/1711.07068)

##### PDF
[https://arxiv.org/pdf/1711.07068](https://arxiv.org/pdf/1711.07068)

