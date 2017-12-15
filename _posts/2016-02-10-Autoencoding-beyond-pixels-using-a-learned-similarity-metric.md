---
layout: post
title: "Autoencoding beyond pixels using a learned similarity metric"
date: 2016-02-10 21:18:27
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Embedding
author: Anders Boesen Lindbo Larsen, Søren Kaae Sønderby, Hugo Larochelle, Ole Winther
mathjax: true
---

* content
{:toc}

##### Abstract
We present an autoencoder that leverages learned representations to better measure similarities in data space. By combining a variational autoencoder with a generative adversarial network we can use learned feature representations in the GAN discriminator as basis for the VAE reconstruction objective. Thereby, we replace element-wise errors with feature-wise errors to better capture the data distribution while offering invariance towards e.g. translation. We apply our method to images of faces and show that it outperforms VAEs with element-wise similarity measures in terms of visual fidelity. Moreover, we show that the method learns an embedding in which high-level abstract visual features (e.g. wearing glasses) can be modified using simple arithmetic.

##### Abstract (translated by Google)
我们提供了一个自动编码器，利用学习的表示来更好地度量数据空间的相似性。通过将变分自编码器与生成对抗网络相结合，我们可以使用GAN鉴别器中的学习特征表示作为VAE重建目标的基础。因此，我们用特征方面的错误代替了元素方面的错误，以更好地捕获数据分布，同时提供了不变性。翻译。我们将我们的方法应用于人脸图像，并显示它在视觉保真度方面优于VAE，具有基于元素的相似性度量。此外，我们显示该方法学习了一种嵌入，其中可以使用简单的算术来修改高级抽象视觉特征（例如佩戴眼镜）。

##### URL
[https://arxiv.org/abs/1512.09300](https://arxiv.org/abs/1512.09300)

##### PDF
[https://arxiv.org/pdf/1512.09300](https://arxiv.org/pdf/1512.09300)

