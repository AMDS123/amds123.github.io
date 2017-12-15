---
layout: post
title: "Multiple Hypothesis Colorization"
date: 2017-03-01 17:02:29
categories: arXiv_CV
tags: arXiv_CV
author: Mohammad Haris Baig, Lorenzo Torresani
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we focus on the problem of colorization for image compression. Since color information occupies a large proportion of the total storage size of an image, a method that can predict accurate color from its grayscale version can produce dramatic reduction in image file size. But colorization for compression poses several challenges. First, while colorization for artistic purposes simply involves predicting plausible chroma, colorization for compression requires generating output colors that are as close as possible to the ground truth. Second, many objects in the real world exhibit multiple possible colors. Thus, to disambiguate the colorization problem some additional information must be stored to reproduce the true colors with good accuracy. To account for the multimodal color distribution of objects we propose a deep tree-structured network that generates multiple color hypotheses for every pixel from a grayscale picture (as opposed to a single color produced by most prior colorization approaches). We show how to leverage the multimodal output of our model to reproduce with high fidelity the true colors of an image by storing very little additional information. In the experiments we show that our proposed method outperforms traditional JPEG color coding by a large margin, producing colors that are nearly indistinguishable from the ground truth at the storage cost of just a few hundred bytes for high-resolution pictures!

##### Abstract (translated by Google)
在这项工作中，我们专注于图像压缩的着色问题。由于颜色信息在图像总存储容量中所占的比例很大，因此可以从灰度版本中预测准确颜色的方法会大大降低图像文件的大小。但是，压缩着色带来了几个挑战。首先，虽然用于艺术目的的着色只涉及预测可能的色度，但用于压缩的着色需要生成尽可能接近真实的输出颜色。其次，现实世界中的许多物体呈现出多种可能的颜色。因此，为了消除彩色化问题，必须存储一些附加信息以高精度地再现真实的色彩。为了说明物体的多模态色彩分布，我们提出了一个深层的树形网络，它为灰度图像中的每个像素生成多个色彩假设（与之前大多数彩色化方法生成的单一色彩相对）。我们展示了如何利用我们模型的多模式输出，通过存储非常少的附加信息，以高保真度重现图像的真实色彩。在实验中，我们表明，我们提出的方法比传统的JPEG颜色编码大大优于传统的JPEG颜色编码，产生的颜色与地面真实度几乎没有区别，高分辨率图片的存储成本只有几百字节！

##### URL
[https://arxiv.org/abs/1606.06314](https://arxiv.org/abs/1606.06314)

##### PDF
[https://arxiv.org/pdf/1606.06314](https://arxiv.org/pdf/1606.06314)

